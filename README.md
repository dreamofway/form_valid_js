# JS form 유효성 체크 스크립트

## html

```
<script type="text/javascript" src="/public/js/view.form.valid.js"></script>

<form id="form_write" method="post" enctype="multipart/form-data"  action="" > 
  ...
</form>
```

## 호출
```
  // alert type 설정 ( view.form.valid.js > 25라인 참조 )
  viewFormValid.alert_type = 'add';
  
  // form id 를 string 으로 전달.
  if( viewFormValid.run( 'form_write' ) === true ) {
      // submit
      $('#form_write').submit();
  }
```
