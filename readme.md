
# QR Codes plugin for CKeditor

This plugin add QR codes to your text editor, you write an URL and it will automatically generate an image and insert it in your editor using the Google QR Code API.

# Installation Instruction

1.Upload qrcodes folder to  ckeditor/plugins/

2.Open ckeditor/config.js, Add to config.toolbar the value 'qrcodes'

    config.toolbar = 
    [
        [ 'Source', '-', 'Bold', 'Italic', 'qrcodes' ]
    ];


3.In the same file, add the extra plugin 'qrcodes':

    config.extraPlugins='myplugin1,myplugin2,qrcodes';




