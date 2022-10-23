---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: .                                                      
layout: single
classes: wide
author_profile: true
# excerpt: Welcome!!
header:
  overlay_image: /assets/images/banner.jpg
actions:
  - label: "Resume"
    url: "https://github.com"
tags:
  pdf
---

> A sample code using Java double produces surprising results.
<br/>

```UNEXPECTED Result: 0.1d + 0.2d - 0.3d = 5.551115123125783E-17 ```

<script src="https://gist.github.com/viraj-vs/041d25ef3fd2913e8e99f3731d06aca9.js?file=doubledemo-java"></script>

> Same code using Java float does not.
<br/>

```EXPECTED Result: 0.1d + 0.2d - 0.3d = 0 ```
<script src="https://gist.github.com/viraj-vs/b7816ec8892a12c82aba4535aa90cb5b.js"></script>


<br/>

Below is the first of a couple of videos to follow on floating point numbers

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/u8WjMyR6Xh4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>
<br/>


<div id="adobe-dc-view" style="width: 1024px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
	var adobeDCView = new AdobeDC.View({clientId: "665fe064bf6f425bb15ccc4da4bf9faf", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://viraj-vs.github.io/docs/computer-science/floating-point/Floating_Point.pdf"}},
			metaData:{fileName: "Floating_Point.pdf"}
	  }, {embedMode: "IN_LINE"});
	});
</script>
