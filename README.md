# simple-jquery-uploader

usage:<br />
<script src="path/to/uploader"></script><br />
<br />
<script><br />
( function($){<br />  
  // modify default options here  <br />
  var options = {  <br />
        "name": "UploadFile", // name of element uploader  <br />
        "postUrl": "", // upload server url  <br />
        "elTarget": null, // drop target  <br />
        "onDrop": null, on file drop event  <br />
        "onBegin": null, // begin process upload  <br />
        "onChange": null, //file upload change  <br />
        "onClientAbort": null, //wrap of onabort event <br />  
        "onClientError": null,//wrap of onerror  event  <br />
        "onClientLoad": null, //wrap of onload  event  <br />
        "onClientLoadEnd": null,//wrap of onloadend  event  <br />
        "onClientLoadStart": null,//wrap of onloadstart  event  <br />
        "onClientProgress": null,//wrap of onprogress  event  <br />
        "onServerAbort": null, // wrap of server onabort  <br />
        "onServerError": null,// wrap of server onerror  <br />
        "onServerLoad": null,// wrap of server onload  <br />
        "onServerLoadStart": null,// wrap of server onstart  <br />
        "onServerProgress": null,// wrap of server onprogress  <br />
        "onServerReadyStateChange": null,// wrap of server onready  <br />
        "onSuccess": null //success callback  <br />
  };  <br />
  $('.id-or-class-element-to-bind').ajaxUploader(options);  <br />
})(jQuery);  <br />
</script>  <br />
