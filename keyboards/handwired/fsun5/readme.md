A selfmade clone of a sun5 keyboard, with some tweaks.

The .json file for http://www.keyboard-layout-editor.com:

~~~
[{a:7,w:2},"Help",{x:0.5},"",{x:1},"F1","F2","F3","F4",{x:0.5},"F5","F6","F7","F8",{x:0.5},"F9","F10","F11","F12",{x:0.5,a:4},"Print\n\n\n\n\n\nScreen","Scroll\n\n\n\n\n\nLock",{a:5},"Pause",{x:0.5,a:7},"Mute","V-","V+","Power"],
[{y:0.25,a:4},"Stop","Redo",{x:0.5,a:5},"ESC",{a:4},"!\n\n\n\n\n\n1","@\n\n\n\n\n\n2","#\n\n\n\n\n\n3","$\n\n\n\n\n\n4","%\n\n\n\n\n\n5","^\n\n\n\n\n\n6","&\n\n\n\n\n\n7","*\n\n\n\n\n\n8","(\n\n\n\n\n\n9",")\n\n\n\n\n\n0",{sm:"cherry",sb:"cherry"},"_\n\n\nß\n\n\n-","+\n\n\n\n\n\n=","|\n\n\n\n\n\n\\","~\n\n\n\n\n\n`",{x:0.5},"Insert","Home","Page\n\n\n\n\n\nUp",{x:0.5},"Num\n\n\n\n\n\nLock","/","*","-"],
["Props","Undo",{x:0.5,w:1.5},"TAB","Q","W","E","R","T","Y","U","I","O","P","{\n\n\nÜ\n\n\n[","}\n\n\n\n\n\n]",{w:1.5},"\n\nBackspace",{x:0.5},"Del","End","Page\n\n\n\n\n\nDown",{x:0.5},"7","8","9",{h:2},"+"],
["Front","Copy",{x:0.5,a:7,w:1.75},"",{a:4},"A","S","D","F","G","H","J","K","L",":\n\n\nÖ\n\n\n;","\"\n\n\nÄ\n\n\n'",{w:2.25},"\n\nReturn",{x:4},"4","5","6"],
["Open","Paste",{x:0.5,w:2.25},"Shift","Z","X","C","V","B","N","M","<\n\n\n\n\n\n,",">\n\n\n\n\n\n.","?\n\n\n\n\n\n/",{w:2.75},"\n\nShift",{x:1.5,a:7},"",{x:1.5,a:4},"1","2","3",{h:2},"Enter"],
["Find","Cut",{x:0.5,w:1.25},"Ctrl",{w:1.25},"Alt\nOption",{w:1.25},"Win\nCommand",{a:7,w:6.25},"",{w:1.25},"",{a:4,w:1.25},"Win\nCommand",{w:1.25},"Comp\nOption",{w:1.25},"Alt\n\n\n\n\n\nGr",{x:0.5,a:7},"","","",{x:0.5,a:4,w:2},"0\n\n\n\n\n\nIns",".\n\n\n\n\n\nDEL"]
~~~

Layer 0 (1) encodes the left-side sun specific keys as:

- Stop: F13 (KC_STOP)
- Again: F14 (KC_AGAIN)
- Props: F15 (KC_CRSL)
- Undo: F16 (KC_UNDO)
- Front: F17 (KC_SLCT)
- Copy: F18 (KC_COPY)
- Open: F19 (KC_EXEC)
- Paste: F20 (KC_PASTE)
- Find: F21 (KC_FIND)
- Cut: F22 (KC_CUT)
- Help: F23 (KC_HELP)
- Empty key: F24 (unused)

The power key is generally unused. I usually use layer 0 and remap the F13..F23 keys
using the Hotkeys (Windows) or Karabiner (MacOS) tools.
