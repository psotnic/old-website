---
title: "TODO"
permalink: "/todo/"
layout: page
---
## for 0.2.14:
[x] fix customData ([C]167)<br>
[x] new module support, port all modules and remove framework (patrick)<br>
[x] rename protect-chmodes to mode-lock and get old protect-chmodes back (patrick)<br>
[x] .mpart should not remove the channel as .-chan does (patrick)<br>
[x] AUTHORS file instead of credits at the top of CHANGELOG (patrick)<br>
[x] slaves/leafs should be able to request shit, especially for modules (patrick)<br>
[x] analyse 005, at least CHANMODES (patrick)<br>
[x] who(is) after connecting for ircds which don't send hostmask in 001 (patrick)<br>
[x] config file generator, ./psotnic -n ([C]167)<br>
[x] remove module.cpp and modules/module.h, all these wrapper functions are not needed anymore (patrick, [C]167)<br>
[x] variable synlevels for ircds that don't support eIR (patrick)<br>
<br>

## 0.3.0 or later:
[ ] new branch without compatibility toggles<br>
[ ] modules must be able to add variables to config file - hashtable?<br>
? [ ] remove some unnecessary features like away, anti-idle, ctcp spoofing (default version reply should be the psotnic version), oidentd spoofing and make modules for that<br>
[ ] checkKeepout() should not be executed every time<br>
[ ] use chars instead of static FLAG_* and save its arguments too<br>
[ ] rewrite mode-lock: entString and a parser like in class-chan-gotmode.cpp<br>
[ ] remove entChattr class<br>
[ ] remove debug/dynamic/static from Makefile, default must be dynamic, maybe ./configure --debug, what about static?<br>
[/] make install ([C]167)<br>
[ ] use calculatePenalty() function, currenty in "raw" module (patrick)<br>
[ ] unify +/-shit,exempt,invite,reop syntax (#chan as first or last parameter?)<br>
[ ] make a module to support euIRC-like modes (! and *) or set +c on connect ([C]167)<br>
