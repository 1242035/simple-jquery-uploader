# simple-jquery-uploader

usage:
<script src="path/to/uploader"></script>
<script>
( function($){
  // modify default options here
  var options = {
        "name": "UploadFile", // name of element uploader
        "postUrl": "", // upload server url
        "elTarget": null, // drop target
        "onDrop": null, on file drop event
        "onBegin": null, // begin process upload
        "onChange": null, //file upload change
        "onClientAbort": null, //wrap of onabort event
        "onClientError": null,//wrap of onerror  event
        "onClientLoad": null, //wrap of onload  event
        "onClientLoadEnd": null,//wrap of onloadend  event
        "onClientLoadStart": null,//wrap of onloadstart  event
        "onClientProgress": null,//wrap of onprogress  event
        "onServerAbort": null, // wrap of server onabort
        "onServerError": null,// wrap of server onerror
        "onServerLoad": null,// wrap of server onload
        "onServerLoadStart": null,// wrap of server onstart
        "onServerProgress": null,// wrap of server onprogress
        "onServerReadyStateChange": null,// wrap of server onready
        "onSuccess": null //success callback
  };
  $('.id-or-class-element-to-bind').ajaxUploader(options);
})(jQuery);
</script>
