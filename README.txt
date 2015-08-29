jquery-micro
===============

sometimes all you need is $(document).ready and onClick

the absolute minimalistic @ 205 bytes

IE9+, chrome, firefox, opera
selector supports '#id' / dom objects only!

example usage:
--------------

    $(document).ready(function() {
        $('#button').onClick(function () {
            // do stuff
        });
    });
