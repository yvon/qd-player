QDPlayer
========

Requirements:
-------------

Adobe Flex SDK 3.5 with mxmlc in PATH.

Compilation:
--------------

    $ cd build/
    $ rake flash:debug && rake flash:release

Test:
-----

    $ cd test/
    $ ./sintra_server.rb # Require Ruby and the sinatra gem
    
Open http://localhost:4567 in your browser.

Integration:
------------

Read test/public/index.html ; the only flashvar required is 'playlist'.