# APM

APM is the package manager for the Lua distribution [ComEXE](https://github.com/pascalcombier/comexe). It comes with a curated collection of Lua-only modules &mdash; all source code, no binaries &mdash; and is still a work in progress. It offers a subset of what's available on [LuaRocks](https://luarocks.org), focused exclusively on PUC Lua 5.5. That means modules for Awesome-WM, LuaJIT, OpenResty, Kong, TeX/LaTeX, Torch, and the like have been excluded.

[The index](https://github.com/pascalcombier/comlib/blob/main/packages/lua/5.5/index.lua) is available, more modules are on the way...

# Usage on Windows and Linux

```console
lua55ce.exe -x --apm list
lua55ce.exe -x --apm install uint-0.186
```

# Modules

| Module | License | Summary | Zip |
|--------|---------|---------|-----|
| [accessor-1.0.0](https://github.com/Tieske/accessor.lua) | MIT/X11 | Access arbitrary depth table keys | [accessor.zip](./packages/lua/5.5/accessor.zip) |
| [adf2md-0.2.0](https://github.com/quiqueporta/adf2md) | MIT | Convert Atlassian Document Format (ADF) to Markdown | [adf2md.zip](./packages/lua/5.5/adf2md.zip) |
| [adtp-1.0](https://applepiecodes.github.io/adtp) | MIT | The ADTP Protocol | [adtp.zip](./packages/lua/5.5/adtp.zip) |
| [alib.eventbus-0.1.0](https://gitlab.com/lua_rocks/eventbus) | MIT | A library for providing an Event Bus with Sections and Channels | [alib.eventbus.zip](./packages/lua/5.5/alib.eventbus.zip) |
| [alien-signals-3.1.1](https://github.com/YanqingXu/alien-signals-in-lua) | MIT | Alien Signals - Reactive programming system for Lua | [alien-signals.zip](./packages/lua/5.5/alien-signals.zip) |
| [alogger-0.6.0](https://gitlab.com/lua_rocks/alogger) | MIT | simple logger | [alogger.zip](./packages/lua/5.5/alogger.zip) |
| [alt-getopt-0.8.0](https://github.com/cheusov/lua-alt-getopt) | MIT/X11 | Process application arguments the same way as getopt_long | [alt-getopt.zip](./packages/lua/5.5/alt-getopt.zip) |
| [amqp-client-rpc-1.0](https://github.com/helmutb82/amqp-client) | Apache | Lua AMQP 0.9.1 client | [amqp-client-rpc.zip](./packages/lua/5.5/amqp-client-rpc.zip) |
| [amqp-1.1](https://github.com/cybermaggedon/amqp) | Apache | RabbitMQ / AMQP 0.9.1 client | [amqp.zip](./packages/lua/5.5/amqp.zip) |
| [ansicolors-1.0.2](https://github.com/kikito/ansicolors.lua) | MIT | Library for color Manipulation. | [ansicolors.zip](./packages/lua/5.5/ansicolors.zip) |
| [ansikit-1.0](https://github.com/daelvn/ansikit) |  | Use ANSI escape sequences easily. | [ansikit.zip](./packages/lua/5.5/ansikit.zip) |
| [app_scheduler-1.0](https://github.com/lalawue/app_scheduler) | MIT/X11 | Process Group Manager | [app_scheduler.zip](./packages/lua/5.5/app_scheduler.zip) |
| [arbiter-1.0](https://darkwiiplayer.github.io/arbiter) | Unlicense |  | [arbiter.zip](./packages/lua/5.5/arbiter.zip) |
| argmatcher-0.1.1 | LGPLv3 | Simple command line argument matcher for Lua | [argmatcher.zip](./packages/lua/5.5/argmatcher.zip) |
| [array-1.3.6](https://github.com/EvandroLG/array.lua) | MIT | A small library with useful methods to handle Lua's table when it's working like an Array | [array.zip](./packages/lua/5.5/array.zip) |
| [arrr-3.0.1](https://github.com/darkwiiplayer/arrr) | Public | A minimalistic commandline argument parser for Lua | [arrr.zip](./packages/lua/5.5/arrr.zip) |
| [async.lua-0.2.1](https://github.com/sclu1034/async.lua) | GPLv3 | Utilities for callback-style asynchronous Lua | [async.lua.zip](./packages/lua/5.5/async.lua.zip) |
| [atpath-1.0](https://github.com/Rinkaa/atpath.lua) | MIT |  | [atpath.zip](./packages/lua/5.5/atpath.zip) |
| [bakalang-1.1.1](https://github.com/Tomas3w/bakalang) | MIT/X11 | A basic libary for making baka preprocessors | [bakalang.zip](./packages/lua/5.5/bakalang.zip) |
| [balance-tree-1.0.0](https://github.com/lalawue/balance-tree.lua) | MIT/X11 | Self-balancing Binary Search Tree for Lua | [balance-tree.zip](./packages/lua/5.5/balance-tree.zip) |
| [base-2.0](https://github.com/okabsd/base) | MIT | Derivative Object-oriented Programming | [base.zip](./packages/lua/5.5/base.zip) |
| [base2base-2.0](http://github.com/oploadk/base2base) | MIT/X11 | A Teal / Lua base-to-base converter | [base2base.zip](./packages/lua/5.5/base2base.zip) |
| [base45-1.0.0](https://github.com/Neph-Oo/lua-base45) | WTFPL | Lua base45 encoder/decoder | [base45.zip](./packages/lua/5.5/base45.zip) |
| [base64-1.5](https://github.com/iskolbin/lbase64) | MIT/Public | Pure Lua base64 encoder/decoder | [base64.zip](./packages/lua/5.5/base64.zip) |
| [based-0.2.2](https://github.com/darkwiiplayer/based) | Unlicense | Collection of string encoders and decoders | [based.zip](./packages/lua/5.5/based.zip) |
| [basename-0.1.0](https://github.com/mah0x211/lua-basename) | MIT/X11 | extract the base portion of a pathname. | [basename.zip](./packages/lua/5.5/basename.zip) |
| [basexx-0.4.1](https://github.com/aiq/basexx) | MIT | A base2, base16, base32, base64 and base85 library for Lua | [basexx.zip](./packages/lua/5.5/basexx.zip) |
| [beancount-0.2.0](https://github.com/f4z3r/beancount/tree/main) | MIT | A library to interact with beancount objects directly in Lua. | [beancount.zip](./packages/lua/5.5/beancount.zip) |
| [beemovie-1.0.1](https://github.com/roosterchicken/beemovie-lua) | MIT | beemovie text generator | [beemovie.zip](./packages/lua/5.5/beemovie.zip) |
| [benchy-1.0](https://github.com/ryanplusplus/benchy.lua/) | MIT | Quick and dirty benchmarking. | [benchy.zip](./packages/lua/5.5/benchy.zip) |
| [bencode-2.2.0](https://bitbucket-archive.softwareheritage.org/projects/wi/wilhelmy/lua-bencode.html) | MIT/X11 | library for encoding and decoding bencoded data | [bencode.zip](./packages/lua/5.5/bencode.zip) |
| [BetterPrint-2.0.0](https://github.com/somutoja/BetterPrint/) | BSD-3-Clause | An easy to use library that allows for easier print debugging and adds many print utilities. | [betterprint.zip](./packages/lua/5.5/betterprint.zip) |
| [binaryheap-0.4](https://github.com/Tieske/binaryheap.lua) | MIT/X11 | Binary heap implementation in pure Lua | [binaryheap.zip](./packages/lua/5.5/binaryheap.zip) |
| [binarytree-0.0.2](https://github.com/Blequi/binarytree) | MIT | Binary Tree data structure written in pure Lua | [binarytree.zip](./packages/lua/5.5/binarytree.zip) |
| [binser-0.0](https://github.com/bakpakin/binser) | MIT | Customizable Lua Serializer | [binser.zip](./packages/lua/5.5/binser.zip) |
| [bint-0.5.2](https://github.com/edubart/lua-bint) | MIT | Arbitrary precision integer arithmetic library in pure Lua | [bint.zip](./packages/lua/5.5/bint.zip) |
| [bintrees-1.3](https://github.com/guicaulada/lua-bintrees) | MIT/X11 | This package provides Binary and Red-Black Search Trees written in Lua. | [bintrees.zip](./packages/lua/5.5/bintrees.zip) |
| [BioLua-0.15](https://sweetpalma.github.io/biolua) | MIT | Computational biology for Lua. | [biolua.zip](./packages/lua/5.5/biolua.zip) |
| [bk-tree-1.0.3](http://profan.github.io/lua-bk-tree/) | MIT/X11 | BK-trees, commonly used for finding near matches to strings. | [bk-tree.zip](./packages/lua/5.5/bk-tree.zip) |
| [bolt-1.2](https://github.com/stefanak-michal/lua-neo4j) | MIT | Bolt protocol library for communication with graph databases. | [bolt.zip](./packages/lua/5.5/bolt.zip) |
| [bump-3dpd-0.2.0](http://github.com/oniietzschan/bump-3dpd) | MIT | A 3D collision detection library for Lua | [bump-3dpd.zip](./packages/lua/5.5/bump-3dpd.zip) |
| [bump-3.1.7](http://github.com/kikito/bump.lua) | MIT | A collision detection library for Lua | [bump.zip](./packages/lua/5.5/bump.zip) |
| [c3-1.0](https://github.com/saucisson/lua-c3) | MIT/X11 | C3 linearization algoritm | [c3.zip](./packages/lua/5.5/c3.zip) |
| [Caelum-1.1](https://github.com/zLouis043/Caelum-lua) | MIT | Lua Library that adds Classes, Structs, Enums, validators, type-checking system, and a easy reflection system | [caelum.zip](./packages/lua/5.5/caelum.zip) |
| calky-1.0 | MIT | A lua library that helps making small calculations while following along in class | [calky.zip](./packages/lua/5.5/calky.zip) |
| [call-2024.3.6.5](https://github.com/hajekmi/call.lua) | MIT | Autoload modules | [call.zip](./packages/lua/5.5/call.zip) |
| [callbag-0.0.2](https://github.com/prabirshrestha/lua-callbag) | MIT | Callbag for Lua | [callbag.zip](./packages/lua/5.5/callbag.zip) |
| [callgraph-0.3.0](https://github.com/gszr/lua-call-graph) | MIT | Generate the call graph of a Lua program | [callgraph.zip](./packages/lua/5.5/callgraph.zip) |
| [canny-redis-0.1](https://github.com/royratcliffe/canny-redis) | MIT | Redis Wire Protocol in Lua | [canny-redis.zip](./packages/lua/5.5/canny-redis.zip) |
| [catchify-1.0.0](https://github.com/stein197/lua-catchify) | MIT | Tiny try-catch-finally implementation for Lua | [catchify.zip](./packages/lua/5.5/catchify.zip) |
| [chain-1.0](https://github.com/ryanplusplus/chain.lua/) | MIT |  Library for easily building chained calls in Lua. | [chain.zip](./packages/lua/5.5/chain.zip) |
| [chalk-0.1.0](https://github.com/Desvelao/chalk) | MIT | Colorize strings to create nice messages in terminal | [chalk.zip](./packages/lua/5.5/chalk.zip) |
| [chandra-toml-2.1](https://codeberg.org/veer66/chandra-toml) | MIT | toml decoder/encoder for Lua (lua-toml fork) | [chandra-toml.zip](./packages/lua/5.5/chandra-toml.zip) |
| [chroma-0.1.2](https://github.com/ldrumm/lua-chroma) | MIT/X11 | Simple ANSI colors for Lua | [chroma.zip](./packages/lua/5.5/chroma.zip) |
| [cirru-parser-0.1](https://github.com/Cirru/parser.moon) | MIT | Cirru Parser in Lua(MoonScript) | [cirru-parser.zip](./packages/lua/5.5/cirru-parser.zip) |
| [class-0.7](https://github.com/javalikescript/luajls) | MIT | class creation with inheritance and constructor | [class.zip](./packages/lua/5.5/class.zip) |
| [classic-0.1.0](https://github.com/emartech/classic) | MIT | Tiny class module for Lua. | [classic.zip](./packages/lua/5.5/classic.zip) |
| [cli-app-base-0.10.0](https://gitlab.com/lua_rocks/cli-app-base) | MIT | library to create cli-apps based on cmd4lua and alogger | [cli-app-base.zip](./packages/lua/5.5/cli-app-base.zip) |
| [cli-1.0.2](https://github.com/gustavo-hms/cli) | LGPL-3 | Declaratively build command line interfaces. | [cli.zip](./packages/lua/5.5/cli.zip) |
| [clopt-0.1.1](https://github.com/mattmc3/clopt.lua) | MIT | A simple Lua command-line option parser with callbacks. | [clopt.zip](./packages/lua/5.5/clopt.zip) |
| [CognitioLogger-0.0.3](https://github.com/Kuaralaboratories/CognitioLogger) | MIT | Made with löve by Kuaralaboratories_ | [cognitiologger.zip](./packages/lua/5.5/cognitiologger.zip) |
| [color-1.1](https://github.com/andOrlando/color) | MIT |  | [color.zip](./packages/lua/5.5/color.zip) |
| [Colorise-1.0](https://github.com/Perkovec/colorise-lua) | MIT | Color converter (RGB, RGBA, HEX) | [colorise.zip](./packages/lua/5.5/colorise.zip) |
| [colorize-0.1](https://www.github.com/code-nuage/colorize) | MIT |  | [colorize.zip](./packages/lua/5.5/colorize.zip) |
| [Colors-8.05.26](http://sputnik.freewisdom.org/lib/colors/) | MIT/X11 | HSL Color Theory Computation in Lua | [colors.zip](./packages/lua/5.5/colors.zip) |
| [configer-0.3.1](https://github.com/RiskoZoSlovenska/configer) | MIT | A configuration merger for Lua | [configer.zip](./packages/lua/5.5/configer.zip) |
| [contract-1.2](https://github.com/mrrogge/contract) | MIT | A function argument type-checker. | [contract.zip](./packages/lua/5.5/contract.zip) |
| [coro-channel-3.0](https://www.github.com/code-nuage/coro-channel) | MIT |  | [coro-channel.zip](./packages/lua/5.5/coro-channel.zip) |
| [coro-fs-2.2](https://www.github.com/code-nuage/coro-fs) | MIT |  | [coro-fs.zip](./packages/lua/5.5/coro-fs.zip) |
| [coro-split-2.0](https://www.github.com/code-nuage/coro-split) | MIT |  | [coro-split.zip](./packages/lua/5.5/coro-split.zip) |
| [coro-wrapper-3.1](https://www.github.com/code-nuage/coro-wrapper) | MIT |  | [coro-wrapper.zip](./packages/lua/5.5/coro-wrapper.zip) |
| [corowatch-1.1.0](https://github.com/Tieske/corowatch) | MIT | Watching and killing coroutines. | [corowatch.zip](./packages/lua/5.5/corowatch.zip) |
| [Coxpcall-1.17.0](http://keplerproject.github.io/coxpcall) | MIT/X11 | Coroutine safe xpcall and pcall | [coxpcall.zip](./packages/lua/5.5/coxpcall.zip) |
| [csv-1](http://github.com/geoffleyland/lua-csv) | MIT/X11 | CSV and other delimited file reading | [csv.zip](./packages/lua/5.5/csv.zip) |
| [date-2.2.1](https://github.com/Tieske/date) | MIT | Date & Time module for Lua 5.x | [date.zip](./packages/lua/5.5/date.zip) |
| [delaunay-0.1](http://yonaba.github.io/delaunay) | MIT | Lua module for Delaunay triangulation of convex polygons | [delaunay.zip](./packages/lua/5.5/delaunay.zip) |
| [dev-roshangeorge-ljsonschema-1.0.0](https://github.com/roshan/lua-resty-ljsonschema) | MIT/X11 | JSON Schema data validator | [dev-roshangeorge-ljsonschema.zip](./packages/lua/5.5/dev-roshangeorge-ljsonschema.zip) |
| [dirname-0.1.0](https://github.com/mah0x211/lua-dirname) | MIT/X11 | extract the directory part of a pathname. | [dirname.zip](./packages/lua/5.5/dirname.zip) |
| [dkjson-2.8](https://dkolf.de/dkjson-lua/) | MIT/X11 | David Kolf's JSON module for Lua | [dkjson.zip](./packages/lua/5.5/dkjson.zip) |
| [dprint-0.4.3](https://gitlab.com/lua_rocks/dprint) | MIT | dprint is a debugging print tool | [dprint.zip](./packages/lua/5.5/dprint.zip) |
| [dromozoa-amalgamate-1.4](https://github.com/dromozoa/dromozoa-amalgamate/) | GPL-3 | Amalgamation of Lua modules and scripts | [dromozoa-amalgamate.zip](./packages/lua/5.5/dromozoa-amalgamate.zip) |
| [dromozoa-calendar-1.13](https://github.com/dromozoa/dromozoa-calendar/) | GPL-3 | Date functions and Japanese calendar | [dromozoa-calendar.zip](./packages/lua/5.5/dromozoa-calendar.zip) |
| [dromozoa-chunk-1.0](https://github.com/dromozoa/dromozoa-chunk/) | GPL-3 | Binary chunk reader and writer | [dromozoa-chunk.zip](./packages/lua/5.5/dromozoa-chunk.zip) |
| [dromozoa-commons-1.64](https://github.com/dromozoa/dromozoa-commons/) | GPL-3 | Reusable Lua components | [dromozoa-commons.zip](./packages/lua/5.5/dromozoa-commons.zip) |
| [dromozoa-dom-1.9](https://github.com/dromozoa/dromozoa-dom/) | GPL-3 | DOM DSL and serialization | [dromozoa-dom.zip](./packages/lua/5.5/dromozoa-dom.zip) |
| [dromozoa-graph-1.41](https://github.com/dromozoa/dromozoa-graph/) | GPL-3 | Graph data structures and algorithms | [dromozoa-graph.zip](./packages/lua/5.5/dromozoa-graph.zip) |
| [dromozoa-http-1.12](https://github.com/dromozoa/dromozoa-http/) | GPL-3 | Portable HTTP client | [dromozoa-http.zip](./packages/lua/5.5/dromozoa-http.zip) |
| [dromozoa-image-1.0](https://github.com/dromozoa/dromozoa-image/) | GPL-3 | Portable toolkit for manipulation of graphics images | [dromozoa-image.zip](./packages/lua/5.5/dromozoa-image.zip) |
| [dromozoa-regexp-1.10](https://github.com/dromozoa/dromozoa-regexp/) | GPL-3 | Regular expressions toolkit | [dromozoa-regexp.zip](./packages/lua/5.5/dromozoa-regexp.zip) |
| [dromozoa-serializer-1.5](https://github.com/dromozoa/dromozoa-serializer/) | GPL-3 | Lua serialization utility | [dromozoa-serializer.zip](./packages/lua/5.5/dromozoa-serializer.zip) |
| [dromozoa-shlex-1.2](https://github.com/dromozoa/dromozoa-shlex/) | GPL-3 | Simple lexical analyzer like Python's shlex | [dromozoa-shlex.zip](./packages/lua/5.5/dromozoa-shlex.zip) |
| [dromozoa-tree-1.13](https://github.com/dromozoa/dromozoa-tree/) | GPL-3 | Tree data structures and algorithms | [dromozoa-tree.zip](./packages/lua/5.5/dromozoa-tree.zip) |
| [dromozoa-utf8-1.19](https://github.com/dromozoa/dromozoa-utf8/) | GPL-3 | Lua 5.3 compatible pure-Lua UTF-8 implementation | [dromozoa-utf8.zip](./packages/lua/5.5/dromozoa-utf8.zip) |
| [dromozoa-vecmath-1.17](https://github.com/dromozoa/dromozoa-vecmath/) | GPL-3 | Pure-Lua implementation of javax.vecmath package | [dromozoa-vecmath.zip](./packages/lua/5.5/dromozoa-vecmath.zip) |
| [dromozoa-xml-1.6](https://github.com/dromozoa/dromozoa-xml/) | GPL-3 | XML parser and toolkit | [dromozoa-xml.zip](./packages/lua/5.5/dromozoa-xml.zip) |
| [dump-0.1.3](https://github.com/mah0x211/lua-dump) | MIT/X11 | convert lua data to string. | [dump.zip](./packages/lua/5.5/dump.zip) |
| [dyana-0.1.0](https://github.com/sicusa/Dyana) | BSD-3-Clause | A functional tweening library for Lua | [dyana.zip](./packages/lua/5.5/dyana.zip) |
| [eansi-1.2](https://github.com/smi11/eansi-lua) | MIT | Easy ANSI Color Maker | [eansi.zip](./packages/lua/5.5/eansi.zip) |
| [eclass-1.0](https://github.com/liaozhaoyan/eclass) | MIT | eclass is a simple object-oriented implementation of Lua | [eclass.zip](./packages/lua/5.5/eclass.zip) |
| [enkoder-1.0](https://github.com/RixInGithub/enkoder) | AGPL-v3.0 |  | [enkoder.zip](./packages/lua/5.5/enkoder.zip) |
| [enum-0.1.3](git+https://github.com/stefano-m/lua-enum) | Apache | Simulate enumerations in Lua | [enum.zip](./packages/lua/5.5/enum.zip) |
| [ergonomic_seed-1.0](https://github.com/StephenCathcart/ergonomic-seed) | MIT | A tiny human-readable seed generator for Lua. | [ergonomic_seed.zip](./packages/lua/5.5/ergonomic_seed.zip) |
| [etlua-1.3.0](https://github.com/leafo/etlua) | MIT | Embedded templates for Lua | [etlua.zip](./packages/lua/5.5/etlua.zip) |
| [evolved.lua-1.10.0](https://github.com/BlackMATov/evolved.lua) | MIT | Evolved ECS (Entity-Component-System) for Lua | [evolved.lua.zip](./packages/lua/5.5/evolved.lua.zip) |
| [expect-1.0](https://github.com/sveyret/expect) | MIT | BDD expect notation for LUA tests | [expect.zip](./packages/lua/5.5/expect.zip) |
| [extname-0.1.0](https://github.com/mah0x211/lua-extname) | MIT/X11 | extract the extension part of a pathname. | [extname.zip](./packages/lua/5.5/extname.zip) |
| [f-strings-0.2](http://github.com/hishamhm/f-strings) | MIT | String interpolation for Lua. | [f-strings.zip](./packages/lua/5.5/f-strings.zip) |
| [f-0.1.0](https://github.com/Desvelao/f) | MIT | Functional methods for tables and strings.    Included oop tables (like-array) too.     | [f.zip](./packages/lua/5.5/f.zip) |
| [fifo-0.2](https://github.com/daurnimator/fifo.lua) | MIT/X11 | A lua library/'class' that implements a FIFO | [fifo.zip](./packages/lua/5.5/fifo.zip) |
| [figurate-numbers-0.8.0](https://github.com/edelveart/figurate-numbers) | MIT | Generates 235 multidimensional figurate number sequences. | [figurate-numbers.zip](./packages/lua/5.5/figurate-numbers.zip) |
| [finita-1.0](https://github.com/NickFlexer/finita) | MIT | Finite State Machine implementation for Lua | [finita.zip](./packages/lua/5.5/finita.zip) |
| [fp-0.0.1](https://github.com/dawee/lua-fp) | MIT | Functional programming library for Lua | [fp.zip](./packages/lua/5.5/fp.zip) |
| [fsm-1.1.0](https://github.com/unindented/lua-fsm) | MIT | Simple FSM implementation. | [fsm.zip](./packages/lua/5.5/fsm.zip) |
| [ftcsv-1.5.0](https://github.com/FourierTransformer/ftcsv) | MIT | A fast pure lua csv library (parser and encoder) | [ftcsv.zip](./packages/lua/5.5/ftcsv.zip) |
| [fun-0.1.3](https://luafun.github.io/) | MIT/X11 | High-performance functional programming library for Lua | [fun.zip](./packages/lua/5.5/fun.zip) |
| [guardia-3.0.3](https://github.com/daelvn/guardia) |  | Guards for Lua and MoonScript | [guardia.zip](./packages/lua/5.5/guardia.zip) |
| [hjson-lua-0.3.0](https://github.com/hjson/hjson-lua) | MIT | A lightweight H/JSON library for Lua. | [hjson-lua.zip](./packages/lua/5.5/hjson-lua.zip) |
| [html-entities-1.3.1](https://TiagoDanin.github.io/htmlEntities-for-lua/) | MIT | Module for lua, decoding HTML entities :) | [html-entities.zip](./packages/lua/5.5/html-entities.zip) |
| [html-tags-0.2.20211012](https://github.com/lalawue/lua-html-tags.git) | X11/MIT | Lua base DSL for writing HTML documents | [html-tags.zip](./packages/lua/5.5/html-tags.zip) |
| [htmlparser-0.3.9](https://msva.github.io/lua-htmlparser/) | LGPL+ | Parse HTML text into a tree of elements with selectors | [htmlparser.zip](./packages/lua/5.5/htmlparser.zip) |
| [httoolsp-0.3.0](https://github.com/un-def/httoolsp) | MIT | A collection of HTTP-related pure Lua helper functions | [httoolsp.zip](./packages/lua/5.5/httoolsp.zip) |
| [httpclient-0.1.0](https://github.com/lusis/lua-httpclient) | Apache | Unified http client wrapper | [httpclient.zip](./packages/lua/5.5/httpclient.zip) |
| [huntable-0.9](https://github.com/olueiro/huntable) | MIT | Comparator function for tables with dynamic values | [huntable.zip](./packages/lua/5.5/huntable.zip) |
| [i18n-0.9.2](https://github.com/kikito/i18n.lua) | MIT | A very complete internationalization library for Lua | [i18n.zip](./packages/lua/5.5/i18n.zip) |
| [inspect-3.1.3](https://github.com/kikito/inspect.lua) | MIT | Lua table visualizer, ideal for debugging | [inspect.zip](./packages/lua/5.5/inspect.zip) |
| [json-lua-0.1](https://github.com/tiye/json-lua) | CC | JSON encoder/decoder | [json-lua.zip](./packages/lua/5.5/json-lua.zip) |
| [jumper-1.8.1](http://github.com/Yonaba/Jumper) | MIT | Fast and easy-to-use pathfinding library for grid-based games | [jumper.zip](./packages/lua/5.5/jumper.zip) |
| [lgetopt-2.0.2](http://lgetopt.daelvn.ga/) |  | Command-line argument parser | [lgetopt.zip](./packages/lua/5.5/lgetopt.zip) |
| [linked-list-1.0.1](https://github.com/lalawue/linked-list.lua) | MIT/X11 | double linked list for Lua | [linked-list.zip](./packages/lua/5.5/linked-list.zip) |
| [loadchunk-0.1.2](https://github.com/mah0x211/lua-loadchunk) | MIT/X11 | Lua chunk loader module | [loadchunk.zip](./packages/lua/5.5/loadchunk.zip) |
| [loadkit-1.1.0](https://github.com/leafo/loadkit) | MIT | Loadkit allows you to load arbitrary files within the Lua package path | [loadkit.zip](./packages/lua/5.5/loadkit.zip) |
| [lodash-0.02](https://github.com/axmat/lodash.lua) | MIT | A functional programming library for lua in respect to the javascript library lodash. | [lodash.zip](./packages/lua/5.5/lodash.zip) |
| [log.lua-0.1.0](https://github.com/StephenCathcart/log.lua) | MIT | A tiny logging module for Lua. | [log.lua.zip](./packages/lua/5.5/log.lua.zip) |
| [logface-0.0.2](https://github.com/azdle/logface) | CC0 | A generic logging interface for lua | [logface.zip](./packages/lua/5.5/logface.zip) |
| [logit-1.0.0](https://github.com/Miqueas/Logit) | zlib | Easy logging for Lua and Nim | [logit.zip](./packages/lua/5.5/logit.zip) |
| [lrunkit-2.1](https://github.com/daelvn/lrunkit) |  | Small library for running commands | [lrunkit.zip](./packages/lua/5.5/lrunkit.zip) |
| [ltext-1.1.0](https://github.com/daelvn/ltext) |  | Text util functions for Lua | [ltext.zip](./packages/lua/5.5/ltext.zip) |
| [lua-basex-0.2.0](https://github.com/un-def/lua-basex) | 2-clause | Base encoding/decoding of any given alphabet using bitcoin style leading zero compression | [lua-basex.zip](./packages/lua/5.5/lua-basex.zip) |
| [lua-circuit-breaker-1.0.2](https://github.com/dream11/lua-circuit-breaker/tree/luarocks-upload) | MIT | Lua library to implement wrap logic in a circuit breaker | [lua-circuit-breaker.zip](./packages/lua/5.5/lua-circuit-breaker.zip) |
| [lua-csv-1.1](http://github.com/isage/lua-csv) | MIT/X11 | CSV and other delimited file reading | [lua-csv.zip](./packages/lua/5.5/lua-csv.zip) |
| [lua-glob-pattern-0.2.1.20120406](https://github.com/davidm/lua-glob-pattern) | MIT/X11 | Convert glob to Lua string pattern | [lua-glob-pattern.zip](./packages/lua/5.5/lua-glob-pattern.zip) |
| [lua-jsonpatch-0](https://github.com/diegogub/lua-jsonpatch.git) | MIT | json-patch implementation for lua | [lua-jsonpatch.zip](./packages/lua/5.5/lua-jsonpatch.zip) |
| [lua-lace-1.4](https://github.com/lunarmodules/lua-lace) | BSD | Lace is a simple access control engine modelled on Squid's acl syntax. | [lua-lace.zip](./packages/lua/5.5/lua-lace.zip) |
| [lua-logger-0.1](https://chickennuggers.github.io/lua-logger) | MIT/X11 | An IRC color compatible logging library | [lua-logger.zip](./packages/lua/5.5/lua-logger.zip) |
| [lua-lru-1.0](https://github.com/starius/lua-lru) | MIT | LRU cache in Lua | [lua-lru.zip](./packages/lua/5.5/lua-lru.zip) |
| [lua-string-test-1.0](https://github.com/ldeveloperl1985/lua-string-test) | MIT | lua string | [lua-string-test.zip](./packages/lua/5.5/lua-string-test.zip) |
| [lua-string-1.2.1](https://github.com/stein197/lua-string) | MIT | Lua standard string library extension | [lua-string.zip](./packages/lua/5.5/lua-string.zip) |
| [lua-tinyyaml-1.0](https://github.com/peposso/lua-tinyyaml) | MIT | a tiny yaml (subset) parser for pure lua | [lua-tinyyaml.zip](./packages/lua/5.5/lua-tinyyaml.zip) |
| [lua-toml-2.0](https://github.com/jonstoler/lua-toml) | MIT | toml decoder/encoder for Lua | [lua-toml.zip](./packages/lua/5.5/lua-toml.zip) |
| [lua-typeof-0.1](https://github.com/iresty/lua-typeof) | Apache | Check the data type for Lua variable | [lua-typeof.zip](./packages/lua/5.5/lua-typeof.zip) |
| lua_cliargs-3.0.2 | MIT | A command-line argument parsing module for Lua | [lua_cliargs.zip](./packages/lua/5.5/lua_cliargs.zip) |
| [lualog-0.1](https://github.com/Desvelao/lualog) | MIT | Simple logger for Lua. | [lualog.zip](./packages/lua/5.5/lualog.zip) |
| [lualogging-1.8.2](https://github.com/lunarmodules/lualogging) | MIT/X11 | A simple API to use logging features | [lualogging.zip](./packages/lua/5.5/lualogging.zip) |
| [luarray-1.0.0](https://github.com/stein197/luarray) | MIT | Instantiatable flexible array implementation with familiar methods for Lua | [luarray.zip](./packages/lua/5.5/luarray.zip) |
| [luassert-1.9.0](https://lunarmodules.github.io/busted/) | MIT | Lua assertions extension | [luassert.zip](./packages/lua/5.5/luassert.zip) |
| [luastruct-1.1](https://github.com/UlisseMini/luastruct) | MIT | Type safe data structures in lua | [luastruct.zip](./packages/lua/5.5/luastruct.zip) |
| luatz-0.4 | MIT | library for time and date manipulation. | [luatz.zip](./packages/lua/5.5/luatz.zip) |
| [lunajson-1.2.3](https://github.com/grafi-tt/lunajson) | MIT/X11 | A strict and fast JSON parser/decoder/encoder written in pure Lua | [lunajson.zip](./packages/lua/5.5/lunajson.zip) |
| [mach-5.1](https://github.com/ryanplusplus/mach.lua/) | MIT | Simple mocking framework for Lua inspired by CppUMock and designed for readability. | [mach.zip](./packages/lua/5.5/mach.zip) |
| [mako-0.1.0](https://github.com/mtdowling/mako) | MIT | Task reactor for Lua and Teal, used to schedule and run tasks | [mako.zip](./packages/lua/5.5/mako.zip) |
| [map-1.0.0](https://github.com/EvandroLG/Map) | MIT | Map works like a hashtable but preserving the key insertion order | [map.zip](./packages/lua/5.5/map.zip) |
| [maple-0.4.1](https://gitlab.com/seven88/maple) | MIT | Maple is a simple, yet extensible logging library inspired by WinstonJS | [maple.zip](./packages/lua/5.5/maple.zip) |
| [md-0.0](https://github.com/bakpakin/luamd) | MIT | Markdown to HTML in pure Lua. | [md.zip](./packages/lua/5.5/md.zip) |
| [microlight-1.0](http://stevedonovan.github.com/microlight/) | MIT/X11 | A compact set of Lua utility functions. | [microlight.zip](./packages/lua/5.5/microlight.zip) |
| [mimetypes-1.1.0](https://github.com/lunarmodules/lua-mimetypes) | MIT/X11 | A simple library for looking up the MIME types of files. | [mimetypes.zip](./packages/lua/5.5/mimetypes.zip) |
| [minheap-0.2.0](https://github.com/mah0x211/lua-minheap) | MIT/X11 | min-heap module | [minheap.zip](./packages/lua/5.5/minheap.zip) |
| mm-1.2.0 | MIT | A delicious Lua inspector | [mm.zip](./packages/lua/5.5/mm.zip) |
| [moonjson-0.1.2](http://github.com/hnimminh/moonjson) | MIT | A lightweight JavaScript Object Notation library for Lua | [moonjson.zip](./packages/lua/5.5/moonjson.zip) |
| [multipart-formdata-lib-1.0](https://github.com/lalawue/multipart-formdata-lib) | MIT | HTTP multipart/form-data parser/builder | [multipart-formdata-lib.zip](./packages/lua/5.5/multipart-formdata-lib.zip) |
| [multipart-0.5.11](https://github.com/Kong/lua-multipart) | MIT | A simple HTTP multipart encoder/decoder for Lua | [multipart.zip](./packages/lua/5.5/multipart.zip) |
| [net-url-1.2](https://github.com/golgote/neturl) | MIT/X11 | URL and Query string parser, builder, normalizer for Lua. | [net-url.zip](./packages/lua/5.5/net-url.zip) |
| [netstring-1.0.6](https://github.com/jprjr/netstring.lua) | MIT | Implementation of DJB's netstring for lua | [netstring.zip](./packages/lua/5.5/netstring.zip) |
| [oop-0.6.0](https://gitlab.com/lua_rocks/oop) | MIT | Oop for Lua | [oop.zip](./packages/lua/5.5/oop.zip) |
| [oops-0.2](https://github.com/blacktaxi/oops) | BSD | Lightweight class-based OOP with concise syntax and local class support. | [oops.zip](./packages/lua/5.5/oops.zip) |
| [pathjoin-2.0](https://www.github.com/code-nuage/pathjoin) | MIT |  | [pathjoin.zip](./packages/lua/5.5/pathjoin.zip) |
| [promise-lua-0.4.1](https://github.com/pyericz/promise-lua) | MIT | An es6 Promise mechanism in Lua. | [promise-lua.zip](./packages/lua/5.5/promise-lua.zip) |
| [router-2.1](https://github.com/APItools/router.lua) | MIT | A barebones router for Lua. It matches urls and executes lua functions | [router.zip](./packages/lua/5.5/router.zip) |
| [say-1.4.1](https://lunarmodules.github.io/say) | MIT | Lua string hashing/indexing library | [say.zip](./packages/lua/5.5/say.zip) |
| [set-lua-1.2.0](https://github.com/EvandroLG/set-lua) | MIT | `set-lua` is a complete implementation of the Set data structure | [set-lua.zip](./packages/lua/5.5/set-lua.zip) |
| [sllog-0.2](https://github.com/smi11/sllog-lua) | MIT | Simple line logger | [sllog.zip](./packages/lua/5.5/sllog.zip) |
| [slowAES-0.1](https://github.com/viegg69/slowAES) | CC |  | [slowaes.zip](./packages/lua/5.5/slowaes.zip) |
| [SlowJson-1.0](https://github.com/Yiwen-Chan/SlowJson) | Apache | A JSON decoder and encoder written in pure Lua | [slowjson.zip](./packages/lua/5.5/slowjson.zip) |
| [split-3.2.1](https://github.com/telemachus/split) | BSD | String split function and iterator for Lua | [split.zip](./packages/lua/5.5/split.zip) |
| [string-contains-0.1.0](https://github.com/mah0x211/lua-string-contains) | MIT | tests whether a substring is contained in a string or not. | [string-contains.zip](./packages/lua/5.5/string-contains.zip) |
| [string-replace-0.1.0](https://github.com/mah0x211/lua-string-replace) | MIT/X11 | replaces a specified string with another specified string. | [string-replace.zip](./packages/lua/5.5/string-replace.zip) |
| [string-split-0.3.0](https://github.com/mah0x211/lua-string-split) | MIT/X11 | split a string into an array of substrings. | [string-split.zip](./packages/lua/5.5/string-split.zip) |
| [string-trim-0.2.0](https://github.com/mah0x211/lua-string-trim) | MIT/X11 | trims the specified string or spaces from the string. | [string-trim.zip](./packages/lua/5.5/string-trim.zip) |
| [table-flatten-0.4.0](https://github.com/mah0x211/lua-table-flatten) | MIT/X11 | flatten a table into a table of specified depth. | [table-flatten.zip](./packages/lua/5.5/table-flatten.zip) |
| [tiny-ecs-1.3](https://github.com/bakpakin/tiny-ecs) | MIT | Entity Component System for Lua. | [tiny-ecs.zip](./packages/lua/5.5/tiny-ecs.zip) |
| [treap-0.1.0](http://yonaba.github.com/treap.lua) | MIT | a simple treap data stucture | [treap.zip](./packages/lua/5.5/treap.zip) |
| [tween-2.1.1](http://github.com/kikito/tween.lua) | MIT | tweening functions for lua | [tween.zip](./packages/lua/5.5/tween.zip) |
| [uint-0.186](https://github.com/SupTan85/lua-uint.git) | MIT | Enable large-number arithmetic (bignum) in Lua, Pure Lua number library! | [uint.zip](./packages/lua/5.5/uint.zip) |
| [version-1.0.1](https://github.com/Kong/version.lua) | Apache | Version comparison library | [version.zip](./packages/lua/5.5/version.zip) |
| [wtf-action-log-0.1](https://github.com/honeybot/wtf-action-log) | MIT |  | [wtf-action-log.zip](./packages/lua/5.5/wtf-action-log.zip) |
| [xmlparser-2.2](https://github.com/jonathanpoelen/lua-xmlparser) | MIT | XML parser written entirely in Lua 5. | [xmlparser.zip](./packages/lua/5.5/xmlparser.zip) |
| [xpcall.lua-1.0.1](https://github.com/BlackMATov/xpcall.lua) | MIT | A pure Lua implementation of xpcall with support for passing arguments | [xpcall.lua.zip](./packages/lua/5.5/xpcall.lua.zip) |
| [xpcall-0.2.0](https://github.com/mah0x211/lua-xpcall) | MIT/X11 | this is a polyfill module that provides an xpcall API that allows passing arguments to functions in lua versions less than 5.2. | [xpcall.zip](./packages/lua/5.5/xpcall.zip) |
