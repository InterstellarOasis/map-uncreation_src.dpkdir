Uncreation
----------

This is a map ported from the [Tremulous](http://tremulous.net/) game to the [Unvanquished](https://www.unvanquished.net/) game. It features the hellish landscape of a deranged map creator's mind, sould be uncreated.

Ported from Tremulous gpp package from [http://ingar.satgnu.net/files/tremulous/base/](http://ingar.satgnu.net/files/tremulous/base/).

This port is an Interstellar Oasis initiative: [https://github.com/InterstellarOasis/InterstellarOasis](https://github.com/InterstellarOasis/InterstellarOasis).

Levelshot
---------

![Levelshot](meta/uncreation/uncreation.webp)

How-to
------

* Get the source

```
git clone https://github.com/InterstellarOasis/map-uncreation_src.dpkdir.git
cd map-uncreation_src.dpkdir/
```

* Build

You need the [Urcheon](https://github.com/illwieckz/Urcheon) tool.  
You will find the dpkdir in `build/test`.

```
urcheon build
```

* Package

You will find the dpk in `build/pkg`.

```
urcheon package
```

Run the map:

```
daemon -pakpath build/pkg +devmap uncreation
```

Credits
-------

Unvanquished port:

* Thomas “illwieckz” Debesse <dev@illwieckz.net> (http://gg.illwieckz.net)

Mapping:

* Who-[Soup]

Textures & Shaders:

* Matthew “Lunaran” Breit (http://lunaran.com/)
* Simon “sock” O'Callaghan (http://www.simonoc.com/)

Special thanks:

* Gordon “Godmil” Miller <godmil@gmail.com> (http://godmil.com/)
* Nicolas “Jex“ Jansens <jex@orodu.net>
* Stijn “Ingar“ Buys <ingar@osirion.org>
* Tim “Timbo” Angus <tim@ngus.net>
* cu-kai
* StalKermit

Legal
-----

Changes by Thomas Debesse fall under the Internet Systems Consortium License:  
http://directory.fsf.org/wiki/License:ISC

Assets by Tremulous contributors fall under the Creative Commons Attribution-ShareAlike 2.5 Generic License:  
http://creativecommons.org/licenses/by-sa/2.5/

Textures from Matthew Breit are subject to the terms of this notice:  
You may: Use the included custom textures & shaders, or modifications thereof, provided you give note of such in an attached readme (and please let me know). Distribute this pak file and/or its contents by any electronic means, provided you leave the contents unaltered and include this text file, also unaltered. You may not: Commercially exploit this file or its contents in any way. Distribute this pak file and/or its contents on any hard media whatsoever, including but not limited to magazine coverdisks or level compilations, without prior consent of and negotiation with the author.

History
-------

* 2015-08-16:	Uncreation 1.2 (Unvanquished community map)
* 2009-12-04:	Tremulous 1.2 Beta (Gameplay preview)
* 2006-03-31:	Tremulous 1.1.0 (Standalone)
