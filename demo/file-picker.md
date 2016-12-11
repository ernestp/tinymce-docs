---
layout: default
title: Basic Local File Picker
title_nav: Basic Local File Picker
description: This example shows how to add a local file picker to Image dialog.
keywords: example demo image local-file-picker file_picker_callback
---

While we demonstrate how you could add local file picker to the *Image* dialog, in order for it to be useful in real world scenario, you should also enable [Image Uploading functionality]({{ siteurl.base_url }}/get-started/upload-images) - as a way to transport those local images to a server.

*Note: The following code relies on `URL.createObjectURL()`. The level of support across modern browsers can be checked [here](http://caniuse.com/#search=createObjectURL).*


{% include codepen.html id="yVqpjq" tab="js" height="930" %}