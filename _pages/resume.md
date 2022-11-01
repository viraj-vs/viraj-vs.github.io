---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: .                                                      
layout: single
author_profile: true
permalink: /resume/
header:
  overlay_image: /assets/images/banner.jpg
actions:
  - label: "Resume"
    url: "https://github.com"
tags:
  pdf
---
<div id="adobe-dc-view" style="width: 1024px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
	var adobeDCView = new AdobeDC.View({clientId: "665fe064bf6f425bb15ccc4da4bf9faf", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://viraj-vs.github.io/docs/computer-science/resume/Viraj-Singh-Resume.pdf"}},
			metaData:{fileName: "Viraj-Singh-Resume.pdf"}
	  }, {embedMode: "IN_LINE"});
	});
</script>
