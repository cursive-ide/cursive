# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)

## 1.11.0-eap3 - 2021-08-19

### Fixed

- 1.11.0-eap2 produces IllegalArgumentException [\#2582](https://github.com/cursive-ide/cursive/issues/2582)

## 1.11.0-eap2 - 2021-08-18

### Added

- Add support for Grazie grammar checker [\#2579](https://github.com/cursive-ide/cursive/issues/2579)

### Fixed

- New versions of Tools Deps breaks git SHA support [\#2581](https://github.com/cursive-ide/cursive/issues/2581)
- test markers not staying visible in gutter [\#2574](https://github.com/cursive-ide/cursive/issues/2574)

## 1.11.0-eap1 - 2021-08-03

### Added

- Babashka problem inventory [\#2516](https://github.com/cursive-ide/cursive/issues/2516)
- Support babashka as valid REPL target [\#2452](https://github.com/cursive-ide/cursive/issues/2452)

### Fixed

- [Deps] Sub-modules with same name do not resolve correctly in IntelliJ [\#2391](https://github.com/cursive-ide/cursive/issues/2391)

## 1.11 - 2021-09-17

## 1.10.3 - 2021-07-28

### Added

- cursive plugin stop working with IntelliJ IDEA 2021.2 EAP [\#2558](https://github.com/cursive-ide/cursive/issues/2558)

### Changed

- Set JAVA_HOME when invoking deps -Sdescribe [\#2561](https://github.com/cursive-ide/cursive/issues/2561)

### Fixed

- Some deps projects refuse to sync in 2021.1 [\#2563](https://github.com/cursive-ide/cursive/issues/2563)
- Failure when using :override-deps in deps.edn [\#2557](https://github.com/cursive-ide/cursive/issues/2557)
- REPL occasionally shows blank tab title [\#2541](https://github.com/cursive-ide/cursive/issues/2541)
- Bug: doesn't work with relative path in :mvn/local-repo [\#2535](https://github.com/cursive-ide/cursive/issues/2535)
- [deps.edn] Cursive picks up the wrong version of clojure-tools JAR when there are multiple versions of it under "/usr/local/lib/clojure/libexec" [\#2105](https://github.com/cursive-ide/cursive/issues/2105)

## 1.10.2 - 2021-04-16

### Changed

- Update deps support to pass path to git command-line [\#2525](https://github.com/cursive-ide/cursive/issues/2525)
- Make structural movement commands work better on strings [\#2523](https://github.com/cursive-ide/cursive/issues/2523)

### Fixed

- Deps import fails when using :default-deps [\#2517](https://github.com/cursive-ide/cursive/issues/2517)
- New Clojurescript test-namespace doesn't compile because of `:refer :all` [\#2508](https://github.com/cursive-ide/cursive/issues/2508)
- Cursive crashes trying to open a project with a :keyword as the project.clj version [\#1999](https://github.com/cursive-ide/cursive/issues/1999)
- (ns ... (:require [... :rename {a b}]) not handled [\#394](https://github.com/cursive-ide/cursive/issues/394)

## 1.10.1 - 2021-03-01

### Added

- Cursive will stop working with Intellij 2021.1 EAP [\#2491](https://github.com/cursive-ide/cursive/issues/2491)
- Passing the line number in REPL commands [\#2488](https://github.com/cursive-ide/cursive/issues/2488)

### Changed

- Cursive doesn't provide version completion for :replace-deps [\#2490](https://github.com/cursive-ide/cursive/issues/2490)
- Structural navigation doesn't work as expected within strings and comments [\#2097](https://github.com/cursive-ide/cursive/issues/2097)

### Fixed

- Using latest tools.deps.alpha CLI breaks Cursive [\#2511](https://github.com/cursive-ide/cursive/issues/2511)
- Can't start REPL with 2019.3 [\#2504](https://github.com/cursive-ide/cursive/issues/2504)
- Cursive fails at startup and locks IDE under 2021.1 EAP 2 [\#2502](https://github.com/cursive-ide/cursive/issues/2502)
- Cursive Run/Debug Configuration forgets the "Specify custom port file" setting [\#2498](https://github.com/cursive-ide/cursive/issues/2498)
- Importing Metabase project results in bogus "profiles" [\#2487](https://github.com/cursive-ide/cursive/issues/2487)
- Refactor > rename broken in 1.10.0-2020.3 [\#2473](https://github.com/cursive-ide/cursive/issues/2473)
- Unable to add Leiningen Configuration  [\#2471](https://github.com/cursive-ide/cursive/issues/2471)

## 1.10.0 - 2020-12-10

### Added

- Action to allow library dependencies to be copied to scratch files [\#2463](https://github.com/cursive-ide/cursive/issues/2463)
- Repl profile name on tab [\#2282](https://github.com/cursive-ide/cursive/issues/2282)
- Feature Request: Named REPLs [\#1974](https://github.com/cursive-ide/cursive/issues/1974)
- Test runner [\#247](https://github.com/cursive-ide/cursive/issues/247)

### Fixed

- Namespace navigation not available with IntelliJIdea 2020.3/Cursive 1.9.4-2020.3 [\#2467](https://github.com/cursive-ide/cursive/issues/2467)
- Cursive doesn't support unqualified data reader tags [\#2464](https://github.com/cursive-ide/cursive/issues/2464)
- No structural editing in clojure scratch buffer [\#2461](https://github.com/cursive-ide/cursive/issues/2461)
- "Show usages" dialog not appearing again for namespaced keywords [\#2457](https://github.com/cursive-ide/cursive/issues/2457)
- ClojureDocs aren't shown for CLJS files [\#2392](https://github.com/cursive-ide/cursive/issues/2392)
- Clojure scratch files cannot be loaded into REPL due to file extension [\#1528](https://github.com/cursive-ide/cursive/issues/1528)

## 1.9.4 - 2020-10-20

### Added

- Add new option to format all forms as Indent Only [\#2443](https://github.com/cursive-ide/cursive/issues/2443)
- Cursive will stop working with Intellij 2020.3 EAP [\#2438](https://github.com/cursive-ide/cursive/issues/2438)
- Add support for with-test [\#2423](https://github.com/cursive-ide/cursive/issues/2423)
- Add Resolve as: none option to form resolution customisation [\#2417](https://github.com/cursive-ide/cursive/issues/2417)
- Stubs for Datomic dev-local [\#2397](https://github.com/cursive-ide/cursive/issues/2397)
- Support for Lokeh/helix using stub generation [\#2330](https://github.com/cursive-ide/cursive/issues/2330)

### Changed

- Allow configuring parinfer bracket open behaviour [\#2432](https://github.com/cursive-ide/cursive/issues/2432)
- Config option to disable hiccup prompts [\#2416](https://github.com/cursive-ide/cursive/issues/2416)
- Deps artifact completion should not shorten artifacts where group is equal to artifact [\#2408](https://github.com/cursive-ide/cursive/issues/2408)
- deps.edn alias support in :paths  [\#2404](https://github.com/cursive-ide/cursive/issues/2404)
- Structural selection in let [\#2258](https://github.com/cursive-ide/cursive/issues/2258)
- Hiccup conversion uses the class shortcut  [\#2184](https://github.com/cursive-ide/cursive/issues/2184)

### Fixed

- Fix Assert failed: port errors when starting nREPL [\#2440](https://github.com/cursive-ide/cursive/issues/2440)
- core.async/<!! & core.async/>!! not resolveable in 1.9.4-eap5-2020.2 w/ tools-deps [\#2439](https://github.com/cursive-ide/cursive/issues/2439)
- HTML->Hiccup conversion producing invalid code [\#2420](https://github.com/cursive-ide/cursive/issues/2420)
- Socket REPL doesn't flush consistently [\#2415](https://github.com/cursive-ide/cursive/issues/2415)
- Deps project resolution broken in 1.10.1.624 [\#2410](https://github.com/cursive-ide/cursive/issues/2410)
- Dependency completion in deps files broken in 1.9.2 [\#2393](https://github.com/cursive-ide/cursive/issues/2393)

### Removed

- Remove Deps migrations from older project format. [\#2446](https://github.com/cursive-ide/cursive/issues/2446)

## 1.9.3 - 2020-07-30

### Added

- Show ClojureDocs examples for CLJS too [\#2292](https://github.com/cursive-ide/cursive/issues/2292)

### Changed

- Parinfer sometimes unbalances delimiters when editing in middle of line [\#2237](https://github.com/cursive-ide/cursive/issues/2237)

### Fixed

- Fix deps API breakage [\#2403](https://github.com/cursive-ide/cursive/issues/2403)

## 1.9.2 - 2020-07-24

### Added

- Support for Leiningen 2.9.3? [\#2343](https://github.com/cursive-ide/cursive/issues/2343)
- Configuriable "Use Leiningen REPL port" Option for remote nREPL [\#2216](https://github.com/cursive-ide/cursive/issues/2216)
- Add action to interrupt REPL printing [\#2100](https://github.com/cursive-ide/cursive/issues/2100)
- Add def behaviour to `goog-define` [\#1067](https://github.com/cursive-ide/cursive/issues/1067)

### Changed

- Show public/private status of functions and vars in autocomplete [\#1991](https://github.com/cursive-ide/cursive/issues/1991)

### Fixed

- Go to definition not working on 'Symbol Resolution' symbols in 1.9.2-eap-6-2020.2 [\#2389](https://github.com/cursive-ide/cursive/issues/2389)
- Cursive throws error when handling nREPL :error status [\#2374](https://github.com/cursive-ide/cursive/issues/2374)
- Deps files with local/root dependency cycles cause OOM errors [\#2371](https://github.com/cursive-ide/cursive/issues/2371)
- Add as Leiningen/Deps Project actions broken [\#2366](https://github.com/cursive-ide/cursive/issues/2366)
- Wrong project name when import from deps [\#2363](https://github.com/cursive-ide/cursive/issues/2363)
- Cursive is unable to understand project when deps.edn is a symlink [\#2360](https://github.com/cursive-ide/cursive/issues/2360)
- IDE becomes unusable after Deps project import [\#2355](https://github.com/cursive-ide/cursive/issues/2355)
- Under 2020.1, the structural editing widget has disappeared [\#2349](https://github.com/cursive-ide/cursive/issues/2349)
- Debugger no longer shows values of lazy sequences [\#2348](https://github.com/cursive-ide/cursive/issues/2348)
- leiningen 2.7.1 could not create shim [\#2347](https://github.com/cursive-ide/cursive/issues/2347)
- Code Evaluation Tool not working on version 1.9.1-2019.3 [\#2345](https://github.com/cursive-ide/cursive/issues/2345)
- "Show usages" dialog not appearing for namespaced keywords [\#2233](https://github.com/cursive-ide/cursive/issues/2233)
- Jump to declaration doesnt work with defonce [\#1069](https://github.com/cursive-ide/cursive/issues/1069)

## 1.9.1 - 2020-03-20

### Added

- Support 2020.1 EAP [\#2304](https://github.com/cursive-ide/cursive/issues/2304)
- Mark deprecated vars/methods [\#2029](https://github.com/cursive-ide/cursive/issues/2029)

### Fixed

- Remote REPL config shows no error when nREPL port cannot be obtained from file [\#2334](https://github.com/cursive-ide/cursive/issues/2334)
- Classpath isn't updated after REPL restart (need to reopen the project) [\#2331](https://github.com/cursive-ide/cursive/issues/2331)
- Custom REPL Commands stopped working [\#2319](https://github.com/cursive-ide/cursive/issues/2319)
- Error when using Rainbow parens on 1.9.1-eap6 [\#2318](https://github.com/cursive-ide/cursive/issues/2318)
- Cannot create listener cursive.notifications.LeiningenProjectNotificationProvider [\#2315](https://github.com/cursive-ide/cursive/issues/2315)
- When a remote nREPL REPL cannot connect, an NPE is shown [\#2313](https://github.com/cursive-ide/cursive/issues/2313)
- Remote REPL config doesn't persist nREPL port module [\#2311](https://github.com/cursive-ide/cursive/issues/2311)
- Issue importing Java classes in 1.9.1-eap4 [\#2310](https://github.com/cursive-ide/cursive/issues/2310)
- Problem running REPL configurations on 2020.1 [\#2308](https://github.com/cursive-ide/cursive/issues/2308)
- unable to change leiningen version [\#2307](https://github.com/cursive-ide/cursive/issues/2307)
- Docstrings have their initial indent removed [\#2300](https://github.com/cursive-ide/cursive/issues/2300)
- ClojureDocs examples are not correctly escaped [\#2299](https://github.com/cursive-ide/cursive/issues/2299)
- Remote socket REPL doesn't handle errors correctly [\#2298](https://github.com/cursive-ide/cursive/issues/2298)
- CLJC doc lookup fix doesn't work when caret is at end of element [\#2288](https://github.com/cursive-ide/cursive/issues/2288)
- When converting file type using File | Convert To..., symbols are unresolved [\#2287](https://github.com/cursive-ide/cursive/issues/2287)
- Incorrect REPL NS handling when using "Send form to REPL" variants [\#2286](https://github.com/cursive-ide/cursive/issues/2286)
- Non-static inner classes fail to recognize constructor [\#2277](https://github.com/cursive-ide/cursive/issues/2277)
- java.util.IllegalFormatConversionException: d != java.lang.String on IntelliJ 2019.2.4/2019.3 + cursive 1.9.0-2019.2/2019.3 [\#2276](https://github.com/cursive-ide/cursive/issues/2276)
- Quick doc/definition popup empty in .cljc files when ClojureScript dependency present [\#1645](https://github.com/cursive-ide/cursive/issues/1645)

## 1.9.0 - 2019-11-25

### Added

- Support for 2019.3 [\#2240](https://github.com/cursive-ide/cursive/issues/2240)
- Support nREPL middleware for Deps projects [\#2215](https://github.com/cursive-ide/cursive/issues/2215)
- Allow switching REPL editor to plain text [\#2206](https://github.com/cursive-ide/cursive/issues/2206)
- Add option to REPL commands to not save files [\#2201](https://github.com/cursive-ide/cursive/issues/2201)
- Add a plugin icon [\#2192](https://github.com/cursive-ide/cursive/issues/2192)

### Changed

- Allow configurable test path handling with Deps [\#2253](https://github.com/cursive-ide/cursive/issues/2253)
- Fulcro 3 Code Motion [\#2241](https://github.com/cursive-ide/cursive/issues/2241)
- Update Cursive to use system deps.edn from t.d.a when available [\#2200](https://github.com/cursive-ide/cursive/issues/2200)
- The restart button in the REPL seems to reversed [\#977](https://github.com/cursive-ide/cursive/issues/977)

### Fixed

- Deps/Leiningen Refresh Projects action is only available from project file [\#2274](https://github.com/cursive-ide/cursive/issues/2274)
- Use correct pluralisation for "ClojureDocs archive is 0 day old" [\#2273](https://github.com/cursive-ide/cursive/issues/2273)
- Import/require popup no longer shows in REPL editor [\#2270](https://github.com/cursive-ide/cursive/issues/2270)
- Dependency completion no longer works [\#2255](https://github.com/cursive-ide/cursive/issues/2255)
- For Deps, handle -Sdescribe returning project deps.edn [\#2251](https://github.com/cursive-ide/cursive/issues/2251)
- No default Clojure platform for creating test namespace via New -> Clojure Namespace [\#2249](https://github.com/cursive-ide/cursive/issues/2249)
- deps alias ordering [\#2246](https://github.com/cursive-ide/cursive/issues/2246)
- eap3 causes IDEA to report error in java module [\#2245](https://github.com/cursive-ide/cursive/issues/2245)
- Stub generation fails Cursive 1.9.0-eap2-2019.3 (also 2019.2) [\#2242](https://github.com/cursive-ide/cursive/issues/2242)
- `Syntax error compiling at (cheshire/generate.clj:1:1)` when refreshing Leiningen projects [\#2208](https://github.com/cursive-ide/cursive/issues/2208)
- Exception lines are not correctly linked [\#2199](https://github.com/cursive-ide/cursive/issues/2199)
- Error in deps file causes useless exception on import [\#2198](https://github.com/cursive-ide/cursive/issues/2198)
- Exceptions from Clojure 1.10.1 on Windows cause Cursive exception [\#2197](https://github.com/cursive-ide/cursive/issues/2197)
- Cursive obscures the repl expression with REBL [\#2113](https://github.com/cursive-ide/cursive/issues/2113)
- REPL history only available after second expression. [\#2003](https://github.com/cursive-ide/cursive/issues/2003)

## 1.8.2 - 2019-12-10

### Added

- Add support for EnvFile plugin for env var management [\#2160](https://github.com/cursive-ide/cursive/issues/2160)
- Support for Leiningen 2.9.1? [\#2158](https://github.com/cursive-ide/cursive/issues/2158)
- Add stubs support for datomic ions [\#2156](https://github.com/cursive-ide/cursive/issues/2156)
- Allow pasting HTML code into hiccup [\#2154](https://github.com/cursive-ide/cursive/issues/2154)
- Make new error messages in Clojure 1.10 clickable [\#2142](https://github.com/cursive-ide/cursive/issues/2142)
- Add option to set environment variables in leiningen run config [\#1953](https://github.com/cursive-ide/cursive/issues/1953)
- When hover on showing code examples for built-in functions on clojuredocs.org [\#1783](https://github.com/cursive-ide/cursive/issues/1783)

### Changed

- When using t.d.a directly for Deps support, the configured IntelliJ proxy should be obeyed [\#2150](https://github.com/cursive-ide/cursive/issues/2150)
- Allow user to specify Maven repo to use when using t.d.a directly for Deps support [\#2149](https://github.com/cursive-ide/cursive/issues/2149)

### Fixed

- Pasting and converting HTML to Hiccup loses contents of <style> and <script> tags [\#2171](https://github.com/cursive-ide/cursive/issues/2171)
- Resolve :extra-deps under aliases to be part of a project [\#2164](https://github.com/cursive-ide/cursive/issues/2164)
- "Allow running in parallel" option in run configs defaults to false and doesn't persist [\#2162](https://github.com/cursive-ide/cursive/issues/2162)
- deps.edn alias overrides from `~/.clojure/deps.edn` fail if they contain '/' [\#2161](https://github.com/cursive-ide/cursive/issues/2161)
- deps.edn with metadata does not import [\#2155](https://github.com/cursive-ide/cursive/issues/2155)
- Deps defaults to Clojure 1.9.0 when using t.d.a directly [\#2148](https://github.com/cursive-ide/cursive/issues/2148)
- Test result / diff not showing  [\#2123](https://github.com/cursive-ide/cursive/issues/2123)
- Code reformat with Parinfer breaks code: def with metadata [\#2044](https://github.com/cursive-ide/cursive/issues/2044)
- Parinfer is confused when functions are indirectly referenced [\#2027](https://github.com/cursive-ide/cursive/issues/2027)
- Namespaced keyword "Navigate to Declaration" and "Find Usages" do not work outside of CLJC files [\#1913](https://github.com/cursive-ide/cursive/issues/1913)
- Not all usages of namespaced keywords are found [\#1908](https://github.com/cursive-ide/cursive/issues/1908)
- metadata map followed by newline indents incorrectly [\#796](https://github.com/cursive-ide/cursive/issues/796)

## 1.8.1 - 2019-12-10

### Added

- Show Quick Documentation on namespace [\#2119](https://github.com/cursive-ide/cursive/issues/2119)
- Deps integration should warn if a selected alias isn't present in the project [\#2112](https://github.com/cursive-ide/cursive/issues/2112)
- Cursive is incompatible with IntelliJ IDEA 2019.1 (JetBrains Runtime 11) EAP  [\#2110](https://github.com/cursive-ide/cursive/issues/2110)
- Support IntelliJ IDEA 2019.1 EAP [\#2104](https://github.com/cursive-ide/cursive/issues/2104)
- Showing full namespace in autocomplete of prefixed namespaced keywords [\#2093](https://github.com/cursive-ide/cursive/issues/2093)

### Changed

- Support leiningen versions > 2.8.1 [\#2120](https://github.com/cursive-ide/cursive/issues/2120)
- Upgrade nREPL [\#2102](https://github.com/cursive-ide/cursive/issues/2102)
- Variable names are altered in the debugger [\#311](https://github.com/cursive-ide/cursive/issues/311)

### Fixed

- Clojure CLI tools 1.10.0.442 breaks gitlibs and local roots in Cursive [\#2138](https://github.com/cursive-ide/cursive/issues/2138)
- Incorrect CachedValue use exceptions [\#2118](https://github.com/cursive-ide/cursive/issues/2118)
- Deps support cannot be configured to use tools.deps directly from the project import wizard [\#2117](https://github.com/cursive-ide/cursive/issues/2117)
- Failure when :local/root in deps.edn is relative path [\#2109](https://github.com/cursive-ide/cursive/issues/2109)
- Cursive doesn't set the `clojure.libfile` system property [\#2108](https://github.com/cursive-ide/cursive/issues/2108)
- "Evaluate Expression" hangs on Clojure 1.10 [\#2099](https://github.com/cursive-ide/cursive/issues/2099)
- Dependency cycle for clj-pdf - Curive 1.8.0 IntelliJ 2018.2 and 2018.3 [\#2094](https://github.com/cursive-ide/cursive/issues/2094)
- Having tests colocated with source code marks the directory as a test directory [\#2088](https://github.com/cursive-ide/cursive/issues/2088)
- Exceptions when parsing javascript files [\#2083](https://github.com/cursive-ide/cursive/issues/2083)
- "Stubs" are generated into `out` directory in project [\#2069](https://github.com/cursive-ide/cursive/issues/2069)
- Dependency cycle for sente.cljc [\#1868](https://github.com/cursive-ide/cursive/issues/1868)
- Inline code in deftype-like things cannot be debugged [\#911](https://github.com/cursive-ide/cursive/issues/911)

## 1.8.0 - 2019-12-10

### Added

- Add support for :extend-via-metadata in protocol definitions [\#2085](https://github.com/cursive-ide/cursive/issues/2085)
- Do not require resolution customisation targets to be present in project [\#2081](https://github.com/cursive-ide/cursive/issues/2081)
- cljs-out directory should be excluded [\#2080](https://github.com/cursive-ide/cursive/issues/2080)
- Add support for IntelliJ 2018.3 EAP [\#2046](https://github.com/cursive-ide/cursive/issues/2046)
- Add autocomplete to deps.edn files [\#2036](https://github.com/cursive-ide/cursive/issues/2036)
- Allow deps to be added with "Generate..." action [\#2034](https://github.com/cursive-ide/cursive/issues/2034)
- Request: config to use two semicolons ;; for line comments [\#1983](https://github.com/cursive-ide/cursive/issues/1983)
- Support for deps.edn [\#1910](https://github.com/cursive-ide/cursive/issues/1910)
- Add support for macrovich? [\#1847](https://github.com/cursive-ide/cursive/issues/1847)
- Fuzzy search for keywords [\#1439](https://github.com/cursive-ide/cursive/issues/1439)
- Feature Request: Folding code and data [\#1269](https://github.com/cursive-ide/cursive/issues/1269)
- Allow "lein run" option to run a REPL [\#1036](https://github.com/cursive-ide/cursive/issues/1036)
- Schema defmethod [\#993](https://github.com/cursive-ide/cursive/issues/993)

### Changed

- ns formatting with reader conditionals [\#1014](https://github.com/cursive-ide/cursive/issues/1014)

### Fixed

- Macrovich fix doesn't work for mount because of vendoring [\#2086](https://github.com/cursive-ide/cursive/issues/2086)
- Resolution cannot be customised from library code [\#2084](https://github.com/cursive-ide/cursive/issues/2084)
- Cursive doesn't handle namespaced maps in deps.edn files [\#2060](https://github.com/cursive-ide/cursive/issues/2060)
- Add -r at end of parameters rather than beginning [\#2059](https://github.com/cursive-ide/cursive/issues/2059)
- macros not always resolved [\#2053](https://github.com/cursive-ide/cursive/issues/2053)
- Refactoring keywords creates incorrect values [\#2051](https://github.com/cursive-ide/cursive/issues/2051)
- environment variables defined using environ.core are not propagated to program when using trampoline [\#2050](https://github.com/cursive-ide/cursive/issues/2050)
- Run configs fail due to proxy exceptions problem [\#2049](https://github.com/cursive-ide/cursive/issues/2049)
- When starting local REPL types, empty console window is always shown. [\#2031](https://github.com/cursive-ide/cursive/issues/2031)
- Windows: exception generating stubs when classpath is too long, CreateProcess error=206 [\#2021](https://github.com/cursive-ide/cursive/issues/2021)
- [tools.deps] timeout for clojure executable when classpath is stale [\#2012](https://github.com/cursive-ide/cursive/issues/2012)
- deps.edn: Can't read resource from paths entry [\#2010](https://github.com/cursive-ide/cursive/issues/2010)
- IndexNotReady exception on project open [\#1996](https://github.com/cursive-ide/cursive/issues/1996)
- "Cannot switch to ClojureScript namespace in Clojure REPL" for cljs > 1.10.63 [\#1993](https://github.com/cursive-ide/cursive/issues/1993)
- com.intellij.openapi.project.IndexNotReadyException: Please change caller accord [\#1985](https://github.com/cursive-ide/cursive/issues/1985)
- Symbol resolution doesn't work from definition, only from usage [\#1977](https://github.com/cursive-ide/cursive/issues/1977)
- [BUG] Reformatting breaks reader conditionals in require form when using parinfer [\#1972](https://github.com/cursive-ide/cursive/issues/1972)
- Locals clearing setup on REPL start doesn't work with cljs.main [\#1955](https://github.com/cursive-ide/cursive/issues/1955)
- Keywords suggestion are twisted if two or more project/editors are open simultaneously [\#1581](https://github.com/cursive-ide/cursive/issues/1581)
- Having trouble with finding relative certificates from project.clj [\#1156](https://github.com/cursive-ide/cursive/issues/1156)
- Hangs on REPL Start: Error when starting java process due to length of classpath [\#1150](https://github.com/cursive-ide/cursive/issues/1150)
- StackOverflowError in CLJS code [\#929](https://github.com/cursive-ide/cursive/issues/929)
- ToolWindow icons should be 13x13 [\#456](https://github.com/cursive-ide/cursive/issues/456)

## 1.11 - 2021-09-17

