
# GoogleMap plugin for CKeditor

This plugin add GoogleMap to your text editor, you write an URL and it will automatically generate an image and insert it in your editor.

# Installation Instruction

1.Upload gmap folder to  ckeditor/plugins/

2.Open ckeditor/config.js, Add to config.toolbar the value 'gmap'

    config.toolbar = 
    [
        [ 'Source', '-', 'Bold', 'Italic', 'gmap' ]
    ];


3.In the same file, add the extra plugin 'qrcodes':

    config.extraPlugins='myplugin1,myplugin2,gmap';




