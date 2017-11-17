[//]: # Idea borrowed from [galaxyproject/readthedocs-redirect](https://github.com/galaxyproject/readthedocs-redirect/)

<script type="text/javascript">

  var currentHost = window.location.hostname;
  var path = currentHost.substring(0, currentHost.indesOf("."));
    
  if currentHost.includes("readthedocs") {window.location.assign("http://clouddocs.f5.com" + path);}
  
</script>

<a href="http://clouddocs.f5.com">
    F5's documentation has moved from Read The Docs to [clouddocs.f5.com](http://clouddocs.f5.com).
</a>
