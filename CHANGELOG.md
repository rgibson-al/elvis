# Change Log

## [0.2.5-beta2](https://github.com/inaka/elvis/tree/0.2.5-beta2) (2015-06-19)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.5-beta...0.2.5-beta2)

**Implemented enhancements:**

- Improve git\_for\_deps\_erlang\_mk and git\_for\_deps\_rebar [\#199](https://github.com/inaka/elvis/issues/199)

- Add --version option [\#174](https://github.com/inaka/elvis/issues/174)

**Fixed bugs:**

- Non spacing not detected [\#221](https://github.com/inaka/elvis/issues/221)

**Closed issues:**

- exception error: undefined function [\#230](https://github.com/inaka/elvis/issues/230)

- Order line results by line\_num [\#219](https://github.com/inaka/elvis/issues/219)

- Instead of using master, use the current branch for elvis.config [\#216](https://github.com/inaka/elvis/issues/216)

- White output [\#209](https://github.com/inaka/elvis/issues/209)

**Merged pull requests:**

- Updated license [\#235](https://github.com/inaka/elvis/pull/235) ([spike886](https://github.com/spike886))

- \[Close \#174\] add version option [\#231](https://github.com/inaka/elvis/pull/231) ([Euen](https://github.com/Euen))

- WIP \[Close \#178\] add no spaces rule [\#229](https://github.com/inaka/elvis/pull/229) ([Euen](https://github.com/Euen))

- \[Fix \#209\] add output-format option to show result without colors [\#228](https://github.com/inaka/elvis/pull/228) ([Euen](https://github.com/Euen))

- Fix bad type [\#227](https://github.com/inaka/elvis/pull/227) ([Euen](https://github.com/Euen))

- \[\#219\] order line results [\#226](https://github.com/inaka/elvis/pull/226) ([Euen](https://github.com/Euen))

- \[Close \#199\] improve protocol for deps [\#225](https://github.com/inaka/elvis/pull/225) ([Euen](https://github.com/Euen))

- \[\#221\] fix bug non spacing not detected [\#223](https://github.com/inaka/elvis/pull/223) ([Euen](https://github.com/Euen))

- \[Fix \#216\] take elvis.config from current branch [\#222](https://github.com/inaka/elvis/pull/222) ([Euen](https://github.com/Euen))

- \[\#28\] Updated zipper functions after renaming edit\_all to fmap [\#220](https://github.com/inaka/elvis/pull/220) ([jfacorro](https://github.com/jfacorro))

- WIP \[\#28\] DRY rule [\#218](https://github.com/inaka/elvis/pull/218) ([jfacorro](https://github.com/jfacorro))

## [0.2.5-beta](https://github.com/inaka/elvis/tree/0.2.5-beta) (2015-04-24)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.5-alpha...0.2.5-beta)

**Implemented enhancements:**

- Add an elvis:rock\_this/1 function to rock specific modules [\#159](https://github.com/inaka/elvis/issues/159)

- Investigate erl\_tidy [\#38](https://github.com/inaka/elvis/issues/38)

**Fixed bugs:**

- Ignored variable in spec [\#206](https://github.com/inaka/elvis/issues/206)

- Rebar master deps undetected [\#202](https://github.com/inaka/elvis/issues/202)

- operator\_spaces: fails with $, [\#181](https://github.com/inaka/elvis/issues/181)

**Closed issues:**

- Cloning getopt problem [\#201](https://github.com/inaka/elvis/issues/201)

- Specify source file on the command line [\#170](https://github.com/inaka/elvis/issues/170)

- Fix the specs on elvis\_style and elvis\_project [\#162](https://github.com/inaka/elvis/issues/162)

**Merged pull requests:**

- Add rule checking for trailing whitespace [\#215](https://github.com/inaka/elvis/pull/215) ([dvaergiller](https://github.com/dvaergiller))

- \[Closes \#206\] Ignored variable in spec [\#214](https://github.com/inaka/elvis/pull/214) ([jfacorro](https://github.com/jfacorro))

- \[\#162\] Fixed left behind spec. [\#213](https://github.com/inaka/elvis/pull/213) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#162\] Fix specs [\#212](https://github.com/inaka/elvis/pull/212) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#170\] Test case for the rock\_this/1 function. [\#211](https://github.com/inaka/elvis/pull/211) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#181\] Operator spaces bug [\#210](https://github.com/inaka/elvis/pull/210) ([jfacorro](https://github.com/jfacorro))

- waffle.io Badge [\#208](https://github.com/inaka/elvis/pull/208) ([waffle-iron](https://github.com/waffle-iron))

- Add an option to skip comments when checking line length rule [\#207](https://github.com/inaka/elvis/pull/207) ([kolorahl](https://github.com/kolorahl))

- \[Closes \#202\] Webhook not adding project rules comments [\#204](https://github.com/inaka/elvis/pull/204) ([jfacorro](https://github.com/jfacorro))

- Replaced tildes for dahses since GitGub shows sections as code. [\#203](https://github.com/inaka/elvis/pull/203) ([jfacorro](https://github.com/jfacorro))

## [0.2.5-alpha](https://github.com/inaka/elvis/tree/0.2.5-alpha) (2015-01-14)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.4...0.2.5-alpha)

**Closed issues:**

- Guys, please stop deleting/changing tags [\#198](https://github.com/inaka/elvis/issues/198)

- "elvis git-hook" should not check deleted file [\#193](https://github.com/inaka/elvis/issues/193)

**Merged pull requests:**

- Revert "Bypass operator\_spaces when unable to find node type" [\#196](https://github.com/inaka/elvis/pull/196) ([elbrujohalcon](https://github.com/elbrujohalcon))

- Ensure that 'elvis git-hook' does not check deleted files [\#194](https://github.com/inaka/elvis/pull/194) ([bullno1](https://github.com/bullno1))

- Bypass operator\_spaces when unable to find node type [\#189](https://github.com/inaka/elvis/pull/189) ([andreineculau](https://github.com/andreineculau))

## [0.2.4](https://github.com/inaka/elvis/tree/0.2.4) (2015-01-05)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.3...0.2.4)

**Implemented enhancements:**

- New command: install [\#144](https://github.com/inaka/elvis/issues/144)

- Add a make install [\#143](https://github.com/inaka/elvis/issues/143)

- Have all rules take a map as the configuration parameter [\#160](https://github.com/inaka/elvis/issues/160)

- Documentation for all Elvis rules [\#154](https://github.com/inaka/elvis/issues/154)

- Use ktn\_code and delete duplicated code from elvis\_code [\#150](https://github.com/inaka/elvis/issues/150)

- Add exceptions to no\_deps\_master\_rebar and no\_deps\_erlankg\_mk [\#149](https://github.com/inaka/elvis/issues/149)

- The god modules rule needs exceptions [\#148](https://github.com/inaka/elvis/issues/148)

- Only return failures when running elvis:rock/1 from the shell [\#142](https://github.com/inaka/elvis/issues/142)

**Fixed bugs:**

- Think Bin's element with size is a module [\#172](https://github.com/inaka/elvis/issues/172)

- Problems with printing UTF in comments. [\#179](https://github.com/inaka/elvis/issues/179)

**Closed issues:**

- Make commandline 'rock' invocation with FAIL notices return 1 to the shell. [\#175](https://github.com/inaka/elvis/issues/175)

- I think it tried to parse my Makefile [\#168](https://github.com/inaka/elvis/issues/168)

- Erlang.mk Plugin [\#96](https://github.com/inaka/elvis/issues/96)

- Bump to 0.2.4 [\#191](https://github.com/inaka/elvis/issues/191)

- Fulfill the open-source checklist [\#127](https://github.com/inaka/elvis/issues/127)

- Allow user defined rules to be run from the escript [\#100](https://github.com/inaka/elvis/issues/100)

**Merged pull requests:**

- \[\#191\] Bump to 0.2.4 [\#192](https://github.com/inaka/elvis/pull/192) ([jfacorro](https://github.com/jfacorro))

- Use git:// instead of ssh remotes [\#188](https://github.com/inaka/elvis/pull/188) ([andreineculau](https://github.com/andreineculau))

- \[Closes \#179\] Correctly print and quote lines with cyrilic chars. [\#180](https://github.com/inaka/elvis/pull/180) ([jfacorro](https://github.com/jfacorro))

- Stricter match for macros as module/function names [\#177](https://github.com/inaka/elvis/pull/177) ([dvaergiller](https://github.com/dvaergiller))

- halt\(1\) after 'elvis rock' invocation fails. [\#176](https://github.com/inaka/elvis/pull/176) ([emauton](https://github.com/emauton))

- \[Closes \#172\] Check node type is 'remote'. [\#173](https://github.com/inaka/elvis/pull/173) ([jfacorro](https://github.com/jfacorro))

- Fix escript generation with rebar. [\#171](https://github.com/inaka/elvis/pull/171) ([pvalsecc](https://github.com/pvalsecc))

- \[\#100\] Fixed typo. [\#165](https://github.com/inaka/elvis/pull/165) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#100\] Support user defined rules [\#164](https://github.com/inaka/elvis/pull/164) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#160\] Rules config as maps [\#161](https://github.com/inaka/elvis/pull/161) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#148\] Ignore modules configuration to god\_modules rule [\#158](https://github.com/inaka/elvis/pull/158) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#149\] Ignore deps list for no\_deps\_\* rules. [\#157](https://github.com/inaka/elvis/pull/157) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#142\] Removed all files and rules that don't fail from rock/1 return value [\#156](https://github.com/inaka/elvis/pull/156) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#154\] Links to wiki in README [\#155](https://github.com/inaka/elvis/pull/155) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#150\] Use ktn\_code. [\#151](https://github.com/inaka/elvis/pull/151) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#144\] 'install git-hook' command [\#146](https://github.com/inaka/elvis/pull/146) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#143\] Added install target [\#145](https://github.com/inaka/elvis/pull/145) ([jfacorro](https://github.com/jfacorro))

## [0.2.3](https://github.com/inaka/elvis/tree/0.2.3) (2014-10-16)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.2...0.2.3)

**Implemented enhancements:**

- Update version of erlang-github dependency to 0.1.1 [\#140](https://github.com/inaka/elvis/issues/140)

**Fixed bugs:**

- Update version of erlang-github dependency to 0.1.1 [\#140](https://github.com/inaka/elvis/issues/140)

**Closed issues:**

- Elvis should only list Erlang repos [\#137](https://github.com/inaka/elvis/issues/137)

**Merged pull requests:**

- \[Closes \#140\] Udpated erlang-github version and rebar.config. [\#141](https://github.com/inaka/elvis/pull/141) ([jfacorro](https://github.com/jfacorro))

## [0.2.2](https://github.com/inaka/elvis/tree/0.2.2) (2014-09-26)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.1...0.2.2)

**Implemented enhancements:**

- Github: For public repos don't add the Services Group [\#128](https://github.com/inaka/elvis/issues/128)

- Use inaka/erlang-github as a dependency  [\#87](https://github.com/inaka/elvis/issues/87)

**Fixed bugs:**

- Wrong detection of macro as function name with ?MODULE [\#133](https://github.com/inaka/elvis/issues/133)

- Reports of lines that include ~p [\#130](https://github.com/inaka/elvis/issues/130)

- Elvis fails when trying to add @elvisinaka as a collaborator… [\#129](https://github.com/inaka/elvis/issues/129)

- Webhook error: 'undef' while applying rule 'used\_ignored\_variable'. [\#122](https://github.com/inaka/elvis/issues/122)

- Elvis webhook is not working [\#120](https://github.com/inaka/elvis/issues/120)

**Closed issues:**

- Add link to service on README.md [\#125](https://github.com/inaka/elvis/issues/125)

- Question: R16 [\#124](https://github.com/inaka/elvis/issues/124)

**Merged pull requests:**

- \[Closes \#87\] Use erlang-github [\#136](https://github.com/inaka/elvis/pull/136) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#133\] Added ?MODULE as an exception for function dynamic calls. [\#135](https://github.com/inaka/elvis/pull/135) ([jfacorro](https://github.com/jfacorro))

- Add missing , in Readme example config. [\#134](https://github.com/inaka/elvis/pull/134) ([sedrik](https://github.com/sedrik))

- \[inaka/elvis-server\#25\] Check team membership GitHub API call. [\#132](https://github.com/inaka/elvis/pull/132) ([jfacorro](https://github.com/jfacorro))

- \[\#130\] Escape tilde before printing result message. [\#131](https://github.com/inaka/elvis/pull/131) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#125\] Added website link and description. [\#126](https://github.com/inaka/elvis/pull/126) ([jfacorro](https://github.com/jfacorro))

- \[\#122\] Added zipper as application so that it is included in release. [\#123](https://github.com/inaka/elvis/pull/123) ([jfacorro](https://github.com/jfacorro))

- \[\#120\] Webhook not working [\#121](https://github.com/inaka/elvis/pull/121) ([jfacorro](https://github.com/jfacorro))

## [0.2.1](https://github.com/inaka/elvis/tree/0.2.1) (2014-09-15)

[Full Changelog](https://github.com/inaka/elvis/compare/0.2.0...0.2.1)

**Implemented enhancements:**

- Improve error handling and reporting [\#107](https://github.com/inaka/elvis/issues/107)

**Fixed bugs:**

- Error when source file contains non ASCII chars [\#113](https://github.com/inaka/elvis/issues/113)

- Unhandled abstract form error on OTP stdlib [\#112](https://github.com/inaka/elvis/issues/112)

- git-hook is not detecting files that are not erlang modules [\#101](https://github.com/inaka/elvis/issues/101)

**Merged pull requests:**

- \[Closes \#107\] Improve error handling and reporting. [\#118](https://github.com/inaka/elvis/pull/118) ([jfacorro](https://github.com/jfacorro))

- \[Fixes \#101\] Modified test case, adding non erlang files. [\#116](https://github.com/inaka/elvis/pull/116) ([jfacorro](https://github.com/jfacorro))

- \[Fixes \#113\] Added support for unicode characters. [\#115](https://github.com/inaka/elvis/pull/115) ([jfacorro](https://github.com/jfacorro))

- \[Fixes \#112\] Added abstract form. [\#114](https://github.com/inaka/elvis/pull/114) ([jfacorro](https://github.com/jfacorro))

## [0.2.0](https://github.com/inaka/elvis/tree/0.2.0) (2014-09-11)

[Full Changelog](https://github.com/inaka/elvis/compare/0.1.1...0.2.0)

**Implemented enhancements:**

- Update README with new configuration format [\#105](https://github.com/inaka/elvis/issues/105)

**Fixed bugs:**

- Elvis tries to parse all files, even non erlang ones [\#108](https://github.com/inaka/elvis/issues/108)

**Merged pull requests:**

- \[Fixes \#108\] Avoid parsing non erlang files [\#111](https://github.com/inaka/elvis/pull/111) ([jfacorro](https://github.com/jfacorro))

- \[\#105\] Updated README. Fixed typos. [\#110](https://github.com/inaka/elvis/pull/110) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#103\] Check old Elvis configuration format [\#109](https://github.com/inaka/elvis/pull/109) ([jfacorro](https://github.com/jfacorro))

- \[\#21\] State records in OTP modules. [\#104](https://github.com/inaka/elvis/pull/104) ([jfacorro](https://github.com/jfacorro))

## [0.1.1](https://github.com/inaka/elvis/tree/0.1.1) (2014-09-09)

**Implemented enhancements:**

- make compatible with erlang.mk [\#91](https://github.com/inaka/elvis/issues/91)

- Handle <<"ping"\>\> GitHub event [\#53](https://github.com/inaka/elvis/issues/53)

- webhook: read and use the elvis.config from the repository   [\#47](https://github.com/inaka/elvis/issues/47)

- Improve feedback when using Elvis on the command line [\#86](https://github.com/inaka/elvis/issues/86)

- Improve running time by caching file information [\#64](https://github.com/inaka/elvis/issues/64)

-  GitHub API: Use OAuth instead of basic authentication [\#58](https://github.com/inaka/elvis/issues/58)

**Fixed bugs:**

- Elvis/Aleppo can't handle a comment on first line of a module [\#93](https://github.com/inaka/elvis/issues/93)

- used\_ignored\_variable reports unused ignored variables [\#92](https://github.com/inaka/elvis/issues/92)

- ?MODULE should be allowed in the macro\_module\_names rule [\#89](https://github.com/inaka/elvis/issues/89)

- Improve module name default Regex [\#88](https://github.com/inaka/elvis/issues/88)

- operator\_spaces rule complains about missing spaces in comments [\#79](https://github.com/inaka/elvis/issues/79)

- Elvis crashes in `erl\_parse:abstract/2` [\#76](https://github.com/inaka/elvis/issues/76)

- Aleppo library is missing when creating a release [\#70](https://github.com/inaka/elvis/issues/70)

- Access file contents using GitHub API [\#59](https://github.com/inaka/elvis/issues/59)

- operator\_spaces rule complains about missing spaces inside strings [\#42](https://github.com/inaka/elvis/issues/42)

- macro\_names rule complains about "STAGED\_CONTENT\(Path\)" [\#41](https://github.com/inaka/elvis/issues/41)

- Missing link in README [\#39](https://github.com/inaka/elvis/issues/39)

- README: Outdated configuration argument value  [\#34](https://github.com/inaka/elvis/issues/34)

- Error in webhook when elvis.config in repo missing  [\#68](https://github.com/inaka/elvis/issues/68)

**Closed issues:**

- Elvis crashes when running on processone/ejabberd [\#84](https://github.com/inaka/elvis/issues/84)

- Rule idea: pinpoint functions with too many indentation levels [\#82](https://github.com/inaka/elvis/issues/82)

- Elvis can't find header files [\#75](https://github.com/inaka/elvis/issues/75)

- http://elvis.inakalabs.com doesn't advertise character encoding [\#74](https://github.com/inaka/elvis/issues/74)

- Comment position has to be relative to the diff [\#56](https://github.com/inaka/elvis/issues/56)

- Rules wiki page [\#8](https://github.com/inaka/elvis/issues/8)

- Build a simple website [\#6](https://github.com/inaka/elvis/issues/6)

- Github Integration [\#5](https://github.com/inaka/elvis/issues/5)

- Commit Integration [\#4](https://github.com/inaka/elvis/issues/4)

- CLI tool [\#3](https://github.com/inaka/elvis/issues/3)

- Erlang console tool [\#2](https://github.com/inaka/elvis/issues/2)

- Initial App Structure [\#1](https://github.com/inaka/elvis/issues/1)

**Merged pull requests:**

- \[Closes \#18\] No deps in revision 'master'. [\#102](https://github.com/inaka/elvis/pull/102) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#86\] Improve command line feedback. [\#99](https://github.com/inaka/elvis/pull/99) ([jfacorro](https://github.com/jfacorro))

- \[Fix \#92\] Fixed bug. [\#98](https://github.com/inaka/elvis/pull/98) ([jfacorro](https://github.com/jfacorro))

- \[\#93\] Added handling for unhandled and unexpected abstract forms. [\#97](https://github.com/inaka/elvis/pull/97) ([jfacorro](https://github.com/jfacorro))

- \[\#91\] Updated erlang.mk version to 1.1 [\#94](https://github.com/inaka/elvis/pull/94) ([jfacorro](https://github.com/jfacorro))

- \[\#89\]\[\#88\] MODULE as a valid module call part. '\_SUITE' as a module name suffix. [\#90](https://github.com/inaka/elvis/pull/90) ([jfacorro](https://github.com/jfacorro))

- \[\#84\] Fixed bugs. Implemented missing nodes. [\#85](https://github.com/inaka/elvis/pull/85) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#79\] Ignore op\_space if node is not found on parse tree. [\#80](https://github.com/inaka/elvis/pull/80) ([jfacorro](https://github.com/jfacorro))

- \[\#76\] Added record definition clauses for to\_map function. [\#78](https://github.com/inaka/elvis/pull/78) ([jfacorro](https://github.com/jfacorro))

- \[Fixes \#75\]\[Fixes \#76\] Use config src\_dirs to look for header files. [\#77](https://github.com/inaka/elvis/pull/77) ([jfacorro](https://github.com/jfacorro))

- \[inaka/elvis-server\#19\] Add user to Services team. [\#73](https://github.com/inaka/elvis/pull/73) ([jfacorro](https://github.com/jfacorro))

- \[inaka/elvis-server\#17\] List all the repositories for which the user has admin permission. [\#72](https://github.com/inaka/elvis/pull/72) ([jfacorro](https://github.com/jfacorro))

- \[\#70\] Added aleppo as applications to the .app file. [\#71](https://github.com/inaka/elvis/pull/71) ([jfacorro](https://github.com/jfacorro))

- \[\#68\] Fixed bug when elvis.config is missing from the repo. [\#69](https://github.com/inaka/elvis/pull/69) ([jfacorro](https://github.com/jfacorro))

- \[inaka/elvis-server\#8\] Added GitHub API calls for Elvis's website  [\#67](https://github.com/inaka/elvis/pull/67) ([jfacorro](https://github.com/jfacorro))

- \[\#58\] Added support for OAuth. [\#66](https://github.com/inaka/elvis/pull/66) ([jfacorro](https://github.com/jfacorro))

- \[\#64\] Improved performance by processing parse tree only once. [\#65](https://github.com/inaka/elvis/pull/65) ([jfacorro](https://github.com/jfacorro))

- \[\#47\] Use the repository's elvis.config file [\#63](https://github.com/inaka/elvis/pull/63) ([jfacorro](https://github.com/jfacorro))

- \[Fixes \#42\] Strings, atoms and binaries are new ignored. [\#62](https://github.com/inaka/elvis/pull/62) ([jfacorro](https://github.com/jfacorro))

- \[\#41\] Fixed bug in macro\_names rule [\#61](https://github.com/inaka/elvis/pull/61) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#59\] Using API to get files' content [\#60](https://github.com/inaka/elvis/pull/60) ([jfacorro](https://github.com/jfacorro))

- \[\#56\] Relative position for PR comments [\#57](https://github.com/inaka/elvis/pull/57) ([jfacorro](https://github.com/jfacorro))

- \[\#53\] Added handling for GitHub's ping event [\#55](https://github.com/inaka/elvis/pull/55) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#19\] Implemented 'module naming convention' rule. [\#52](https://github.com/inaka/elvis/pull/52) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#20\] Implemented 'no behavio\(u\)r\_info' rule. [\#51](https://github.com/inaka/elvis/pull/51) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#17\] Implemented 'used ignored variable' rule. [\#50](https://github.com/inaka/elvis/pull/50) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#17\] Implemented invalid dynamic calls rule. [\#49](https://github.com/inaka/elvis/pull/49) ([jfacorro](https://github.com/jfacorro))

- \[\#26\] Implemented 'no if expression' rule. [\#48](https://github.com/inaka/elvis/pull/48) ([jfacorro](https://github.com/jfacorro))

- \[\#16\] Implemented god modules rule. [\#46](https://github.com/inaka/elvis/pull/46) ([jfacorro](https://github.com/jfacorro))

- \[\#14\] Modified AST node generation for 'case' and list comprehension [\#45](https://github.com/inaka/elvis/pull/45) ([jfacorro](https://github.com/jfacorro))

- \[\#14\] Implement nesting level rule [\#43](https://github.com/inaka/elvis/pull/43) ([jfacorro](https://github.com/jfacorro))

- \[\#5\] GitHub Integration: errors and bugs fixes [\#40](https://github.com/inaka/elvis/pull/40) ([jfacorro](https://github.com/jfacorro))

- \[\#5\] Implemented GitHub Integration [\#37](https://github.com/inaka/elvis/pull/37) ([jfacorro](https://github.com/jfacorro))

- \[\#4\] Added git-hook command [\#33](https://github.com/inaka/elvis/pull/33) ([jfacorro](https://github.com/jfacorro))

- \[\#3\] Implemented a command line interface for Elvis. [\#31](https://github.com/inaka/elvis/pull/31) ([jfacorro](https://github.com/jfacorro))

- \[\#2\] Implemented elvis for console usage [\#9](https://github.com/inaka/elvis/pull/9) ([jfacorro](https://github.com/jfacorro))

- \[\#1\] Rebar and erlang.mk configuration files and other application structure files. [\#7](https://github.com/inaka/elvis/pull/7) ([jfacorro](https://github.com/jfacorro))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*