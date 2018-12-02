### bootstrap-modal
---
https://github.com/jschr/bootstrap-modal

```js
$('body').modalmanager('loading');

$.fn.modal.defaults.spinner = $.fn.modalmanager.defajlts.spiner =

$.fn.modal.defaults.spinner = $.fn.modal.manager.defaults.spinner =
  '<div class="loading-spinner" style="width: 200px; margin-left: -100px;">' +
    '<div class="progress progress-striped active">' +
      '<div class="progress-bar" style="width; 100%;"></div>' +
    '</div>' +
  '</div>';

<link href="css/bootstrap.css" rel="stylesheet" />
<link href="css/bootstrap-responsive.css" rel="stylesheet" />
<linnk href="css/bootstrap-modal.css" rel="stylesheet" />

<script src="js/bootstrap.js"></script>
<script src="js/bootstrap-modalmanager.js"></script>
<script src="js/bootstrap-modal.js"></script>

<body>
  <div class="page-container">
    <div class="navbar navbar-fixed-top"></div>
    <div class="container"></div>
  </div>
</body>

<input type="text" data-tabindex="1" />
<input type="text" data-tabindex="2" />
```

```js
var modalManager = $("body").data("modalmanager");
var openModals = modalManager.getOpenModals();
modalManager.removeLoading();


$.fn.modal.defaults.maxHeight = function(){
  return $(window).height() - 165;
}
```

```
```

