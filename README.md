# base64imagedrop
Drag and Drop image into CKEditor to create Base64 image tag

This plugin will allow Drag and Drop for Images in CKEditor. It will automatically encode the image to Base64 and add it to the editor.

This is supposed to be used with a base64 image plugin like this: https://github.com/nmmf/base64image

<b>Installation:</b>
<br/>Drop the "base64imagedrop" folder into "ckeditor/plugins".
<br/>Add this line to the  "ckeditor/config.js" (inside the function):
<br/><code>config.extraPlugins = 'base64imagedrop';</code>
