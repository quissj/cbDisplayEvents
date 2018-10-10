DisplayEvents plugin

http://wiki.codeblocks.org/index.php/DisplayEvents_plugin

DisplayEvents records every time a Code::Blocks event registered with RegisterEventSink is sent, printing in the Code::Blocks Debug log. This is useful for determining: which events to register during plugin development, at what points in time the events are triggered, and in what order the events are triggered.

Forum thread for discussion: http://forums.codeblocks.org/index.php/topic,15210.msg102134.html#msg102134


Usage:

Unpack it into src/plugins subdirectory of C::B's sources (not in contrib !!).
Don't forget to run src/update[.bat] afterwards, to copy the plugin from devel- to output-folder.

The Makefile.am is not tested, so it might or might not work after integrating it into automake-system.
