# JoyChorder
An interface for chording text inputs with a standard gamepad's thumbsticks.

Instead of awkwardly positioning a cursor over a virtual keyboard to select individual characters, JoyChorder allows users to quickly and comfortably select from over 200 character sequences by combining motions of the thumbsticks and using the triggers as quasimodal modifiers.

By relying on about 80 distinct motions (64 pairs of directions plus 16 individual directions, 8 per stick) instead of grid-navigating or menu-diving, with practice the simple-to-execute inputs should become strongly associated with the character sequences they produce through muscle memory.

It's not too dissimilar in theory from the [Daisywheel](http://likethemammal.github.io/daisywheeljs/) UI featured in Steam's Big Picture mode, but with each input having its own kinesthetic "shape", each character selection requiring only one simultaneous action (rather than indicating a group of letters and then confirming a selection from that subset), room on the controller left over for handy editing commands, and the ability to select individual characters as well as bigrams, trigrams, and 4-grams, JoyChorder takes full advantage of the affordances of the gamepad to provide a powerful typing interface.

## Controls

The layout below corresponds with a standard Xbox 360 controller.

**Note:** while one trigger is depressed, pressing the other will execute a distinct command.

| Input | Output |
|---|---|
| LS 🡤 + RS 🡤 | qu |
| LS 🡤 + RS 🡡 | wh |
| LS 🡤 + RS 🡥 | i  |
| LS 🡤 + RS 🡢 | sh |
| LS 🡤 + RS 🡦 | k  |
| LS 🡤 + RS 🡣 | be |
| LS 🡤 + RS 🡧 | nt |
| LS 🡤 + RS 🡠 | co |
| LS 🡡 + RS 🡤 | on |
| LS 🡡 + RS 🡡 | w  |
| LS 🡡 + RS 🡥 | l  |
| LS 🡡 + RS 🡢 | nd |
| LS 🡡 + RS 🡦 | r  |
| LS 🡡 + RS 🡣 | n  |
| LS 🡡 + RS 🡧 | b  |
| LS 🡡 + RS 🡠 | in |
| LS 🡥 + RS 🡤 | ch |
| LS 🡥 + RS 🡡 | ea |
| LS 🡥 + RS 🡥 | ou |
| LS 🡥 + RS 🡢 | no |
| LS 🡥 + RS 🡦 | z  |
| LS 🡥 + RS 🡣 | an |
| LS 🡥 + RS 🡧 | y  |
| LS 🡥 + RS 🡠 | ti |
| LS 🡢 + RS 🡤 | al |
| LS 🡢 + RS 🡡 | of |
| LS 🡢 + RS 🡥 | f  |
| LS 🡢 + RS 🡢 | p  |
| LS 🡢 + RS 🡦 | he |
| LS 🡢 + RS 🡣 | to |
| LS 🡢 + RS 🡧 | hi |
| LS 🡢 + RS 🡠 | a  |
| LS 🡦 + RS 🡤 | x  |
| LS 🡦 + RS 🡡 | th |
| LS 🡦 + RS 🡥 | me |
| LS 🡦 + RS 🡢 | se |
| LS 🡦 + RS 🡦 | ck |
| LS 🡦 + RS 🡣 | ei |
| LS 🡦 + RS 🡧 | en |
| LS 🡦 + RS 🡠 | ng |
| LS 🡣 + RS 🡤 | v  |
| LS 🡣 + RS 🡡 | e  |
| LS 🡣 + RS 🡥 | g  |
| LS 🡣 + RS 🡢 | d  |
| LS 🡣 + RS 🡦 | le |
| LS 🡣 + RS 🡣 | m  |
| LS 🡣 + RS 🡧 | ur |
| LS 🡣 + RS 🡠 | ve |
| LS 🡧 + RS 🡤 | do |
| LS 🡧 + RS 🡡 | u  |
| LS 🡧 + RS 🡥 | s  |
| LS 🡧 + RS 🡢 | re |
| LS 🡧 + RS 🡦 | o  |
| LS 🡧 + RS 🡣 | c  |
| LS 🡧 + RS 🡧 | as |
| LS 🡧 + RS 🡠 | it |
| LS 🡠 + RS 🡤 | or |
| LS 🡠 + RS 🡡 | is |
| LS 🡠 + RS 🡥 | j  |
| LS 🡠 + RS 🡢 | t  |
| LS 🡠 + RS 🡦 | if |
| LS 🡠 + RS 🡣 | h  |
| LS 🡠 + RS 🡧 | st |
| LS 🡠 + RS 🡠 | q  |
| LS 🡤 | { |
| LS 🡡 | & |
| LS 🡥 | } |
| LS 🡢 | ) |
| LS 🡦 | # |
| LS 🡣 | : |
| LS 🡧 | $ |
| LS 🡠 | ( |
| LSB | `copy` |
| RS 🡤 | ! |
| RS 🡡 | ' |
| RS 🡥 | ? |
| RS 🡢 | ; |
| RS 🡦 | , |
| RS 🡣 | . |
| RS 🡧 | / |
| RS 🡠 | " |
| RSB | `cycle case` |
| LT + LS 🡤 | ¿ |
| LT + LS 🡡 | µ |
| LT + LS 🡥 | ° |
| LT + LS 🡢 | » |
| LT + LS 🡦 | · |
| LT + LS 🡣 | 0 |
| LT + LS 🡧 | ¬ |
| LT + LS 🡠 | « |
| LT + LSB | `cut` |
| LT + RS 🡤 | 7 |
| LT + RS 🡡 | 8 |
| LT + RS 🡥 | 9 |
| LT + RS 🡢 | 6 |
| LT + RS 🡦 | 3 |
| LT + RS 🡣 | 2 |
| LT + RS 🡧 | 1 |
| LT + RS 🡠 | 4 |
| LT + RS * | 5 |
| RT + LS 🡤 | \  |
| RT + LS 🡡 | \| |
| RT + LS 🡥 | %  |
| RT + LS 🡢 | >  |
| RT + LS 🡦 | +  |
| RT + LS 🡣 | =  |
| RT + LS 🡧 | -  |
| RT + LS 🡠 | <  |
| RT + LSB | `paste` |
| RT + RS 🡤 | ` |
| RT + RS 🡡 | ^ |
| RT + RS 🡥 | ~ |
| RT + RS 🡢 | ] |
| RT + RS 🡦 | ¡ |
| RT + RS 🡣 | _ |
| RT + RS 🡧 | @ |
| RT + RS 🡠 | [ |
| RT + RSB | * |
| LT + LS 🡤 + RS 🡤 | non |
| LT + LS 🡤 + RS 🡡 | why |
| LT + LS 🡤 + RS 🡥 | get |
| LT + LS 🡤 + RS 🡢 | day |
| LT + LS 🡤 + RS 🡦 | its |
| LT + LS 🡤 + RS 🡣 | was |
| LT + LS 🡤 + RS 🡧 | ion |
| LT + LS 🡤 + RS 🡠 | him |
| LT + LS 🡡 + RS 🡤 | yes |
| LT + LS 🡡 + RS 🡡 | now |
| LT + LS 🡡 + RS 🡥 | new |
| LT + LS 🡡 + RS 🡢 | the |
| LT + LS 🡡 + RS 🡦 | any |
| LT + LS 🡡 + RS 🡣 | one |
| LT + LS 🡡 + RS 🡧 | ain |
| LT + LS 🡡 + RS 🡠 | too |
| LT + LS 🡥 + RS 🡤 | has |
| LT + LS 🡥 + RS 🡡 | san |
| LT + LS 🡥 + RS 🡥 | off |
| LT + LS 🡥 + RS 🡢 | log |
| LT + LS 🡥 + RS 🡦 | how |
| LT + LS 🡥 + RS 🡣 | ing |
| LT + LS 🡥 + RS 🡧 | eve |
| LT + LS 🡥 + RS 🡠 | ted |
| LT + LS 🡢 + RS 🡤 | ive |
| LT + LS 🡢 + RS 🡡 | let |
| LT + LS 🡢 + RS 🡥 | con |
| LT + LS 🡢 + RS 🡢 | com |
| LT + LS 🡢 + RS 🡦 | map |
| LT + LS 🡢 + RS 🡣 | for |
| LT + LS 🡢 + RS 🡧 | int |
| LT + LS 🡢 + RS 🡠 | ess |
| LT + LS 🡦 + RS 🡤 | rea |
| LT + LS 🡦 + RS 🡡 | see |
| LT + LS 🡦 + RS 🡥 | ion |
| LT + LS 🡦 + RS 🡢 | her |
| LT + LS 🡦 + RS 🡦 | ere |
| LT + LS 🡦 + RS 🡣 | out |
| LT + LS 🡦 + RS 🡧 | pro |
| LT + LS 🡦 + RS 🡠 | his |
| LT + LS 🡣 + RS 🡤 | ons |
| LT + LS 🡣 + RS 🡡 | and |
| LT + LS 🡣 + RS 🡥 | tio |
| LT + LS 🡣 + RS 🡢 | gen |
| LT + LS 🡣 + RS 🡦 | ent |
| LT + LS 🡣 + RS 🡣 | all |
| LT + LS 🡣 + RS 🡧 | ter |
| LT + LS 🡣 + RS 🡠 | use |
| LT + LS 🡧 + RS 🡤 | art |
| LT + LS 🡧 + RS 🡡 | var |
| LT + LS 🡧 + RS 🡥 | ect |
| LT + LS 🡧 + RS 🡢 | per |
| LT + LS 🡧 + RS 🡦 | our |
| LT + LS 🡧 + RS 🡣 | lot |
| LT + LS 🡧 + RS 🡧 | are |
| LT + LS 🡧 + RS 🡠 | did |
| LT + LS 🡠 + RS 🡤 | way |
| LT + LS 🡠 + RS 🡡 | ith |
| LT + LS 🡠 + RS 🡥 | ear |
| LT + LS 🡠 + RS 🡢 | end |
| LT + LS 🡠 + RS 🡦 | try |
| LT + LS 🡠 + RS 🡣 | not |
| LT + LS 🡠 + RS 🡧 | can |
| LT + LS 🡠 + RS 🡠 | you |
| RT + LS 🡤 + R 🡤 | than |
| RT + LS 🡤 + R 🡡 | lect |
| RT + LS 🡤 + R 🡥 | each |
| RT + LS 🡤 + R 🡢 | grad |
| RT + LS 🡤 + R 🡦 | they |
| RT + LS 🡤 + R 🡣 | give |
| RT + LS 🡤 + R 🡧 | auto |
| RT + LS 🡤 + R 🡠 | anti |
| RT + LS 🡡 + R 🡤 | reme |
| RT + LS 🡡 + R 🡡 | over |
| RT + LS 🡡 + R 🡥 | long |
| RT + LS 🡡 + R 🡢 | when |
| RT + LS 🡡 + R 🡦 | turn |
| RT + LS 🡡 + R 🡣 | what |
| RT + LS 🡡 + R 🡧 | mand |
| RT + LS 🡡 + R 🡠 | main |
| RT + LS 🡥 + R 🡤 | said |
| RT + LS 🡥 + R 🡡 | sign |
| RT + LS 🡥 + R 🡥 | else |
| RT + LS 🡥 + R 🡢 | char |
| RT + LS 🡥 + R 🡦 | port |
| RT + LS 🡥 + R 🡣 | used |
| RT + LS 🡥 + R 🡧 | tual |
| RT + LS 🡥 + R 🡠 | into |
| RT + LS 🡢 + R 🡤 | city |
| RT + LS 🡢 + R 🡡 | only |
| RT + LS 🡢 + R 🡥 | then |
| RT + LS 🡢 + R 🡢 | ther |
| RT + LS 🡢 + R 🡦 | that |
| RT + LS 🡢 + R 🡣 | have |
| RT + LS 🡢 + R 🡧 | ness |
| RT + LS 🡢 + R 🡠 | know |
| RT + LS 🡦 + R 🡤 | were |
| RT + LS 🡦 + R 🡡 | also |
| RT + LS 🡦 + R 🡥 | ical |
| RT + LS 🡦 + R 🡢 | been |
| RT + LS 🡦 + R 🡦 | ight |
| RT + LS 🡦 + R 🡣 | ough |
| RT + LS 🡦 + R 🡧 | both |
| RT + LS 🡦 + R 🡠 | site |
| RT + LS 🡣 + R 🡤 | more |
| RT + LS 🡣 + R 🡡 | from |
| RT + LS 🡣 + R 🡥 | comp |
| RT + LS 🡣 + R 🡢 | form |
| RT + LS 🡣 + R 🡦 | list |
| RT + LS 🡣 + R 🡣 | able |
| RT + LS 🡣 + R 🡧 | cond |
| RT + LS 🡣 + R 🡠 | with |
| RT + LS 🡧 + R 🡤 | just |
| RT + LS 🡧 + R 🡡 | ated |
| RT + LS 🡧 + R 🡥 | like |
| RT + LS 🡧 + R 🡢 | part |
| RT + LS 🡧 + R 🡦 | ould |
| RT + LS 🡧 + R 🡣 | page |
| RT + LS 🡧 + R 🡧 | will |
| RT + LS 🡧 + R 🡠 | this |
| RT + LS 🡠 + R 🡤 | fore |
| RT + LS 🡠 + R 🡡 | time |
| RT + LS 🡠 + R 🡥 | ture |
| RT + LS 🡠 + R 🡢 | some |
| RT + LS 🡠 + R 🡦 | your |
| RT + LS 🡠 + R 🡣 | ance |
| RT + LS 🡠 + R 🡧 | been |
| RT + LS 🡠 + R 🡠 | here |
| D-pad🡡 | `move cursor up one line` |
| D-pad🡢 | `move cursor right` |
| D-pad🡣 | `move cursor down one line` |
| D-pad🡠 | `move cursor left` |
| LB | `backspace` |
| RB | `enter` |
| A  | `cycle autocomplete suggestions` |
| B  | `escape` |
| X  | `apply autocomplete` |
| Y  | `space` |
| LT + D-pad🡡 | `page up` |
| LT + D-pad🡢 | `move cursor to end of line` |
| LT + D-pad🡣 | `page down` |
| LT + D-pad🡠 | `move cursor to start of line` |
| RT + D-pad🡡 | `select up` |
| RT + D-pad🡢 | `select right` |
| RT + D-pad🡣 | `select down` |
| RT + D-pad🡠 | `select left` |
| LT + LB | `delete line` |
| LT + RB | `newline` |
| RT + LB | `delete word` |
| RT + RB | `join lines` |
| LT + A  | `transpose 2 characters` |
| LT + B  | `undo` |
| LT + X  | `find` |
| LT + Y  | `tab forward` |
| RT + A  | `repeat` |
| RT + B  | `redo` |
| RT + X  | `replace` |
| RT + Y  | `tab back` |
| LT + RT | `jump to start of current word or end of prev. word` |
| RT + LT | `jump to end of current word or start of next word` |
