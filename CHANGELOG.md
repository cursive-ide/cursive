# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)

## 1.12.3-eap2 - 2022-04-22

### Changed

- Make Cursive more forgiving in cases of unresolved symbols [\#2682](https://github.com/cursive-ide/cursive/issues/2682)

### Fixed

- Symbol resolution customisation bug [\#2683](https://github.com/cursive-ide/cursive/issues/2683)

## 1.12.3-eap1 - 2022-04-15

### Changed

- Create src dir when creating new deps project [\#2675](https://github.com/cursive-ide/cursive/issues/2675)

### Fixed

- Cursive 1.12.2 doesn't handle multiple requires of same ns correctly [\#2678](https://github.com/cursive-ide/cursive/issues/2678)
- Nested requires not resolved in 1.12.2-2022.1 / IntelliJ IDEA 2022.1 [\#2676](https://github.com/cursive-ide/cursive/issues/2676)
- spec alias shows as not being used when you import it via clojure ns in clojurescript [\#2673](https://github.com/cursive-ide/cursive/issues/2673)
- Babashka REPL environment vars not getting set [\#2670](https://github.com/cursive-ide/cursive/issues/2670)
- Run configuration with deps.edn alias fails [\#2617](https://github.com/cursive-ide/cursive/issues/2617)
- Alias :main-opts not respected for nREPL configuration [\#2322](https://github.com/cursive-ide/cursive/issues/2322)

## 1.12.2 - 2022-04-13

### Added

- Cursive plugin doesn't work with Intellij IDEA 2022.1 EAP [\#2642](https://github.com/cursive-ide/cursive/issues/2642)
- Multiline TODO matchers would be nice [\#2524](https://github.com/cursive-ide/cursive/issues/2524)
- Highlight a ":require" entry with ":refer" as unused [\#2427](https://github.com/cursive-ide/cursive/issues/2427)
- Trigger Visual Diff from REPL [\#2128](https://github.com/cursive-ide/cursive/issues/2128)
- Implement "Optimize Imports" feature [\#1197](https://github.com/cursive-ide/cursive/issues/1197)
- [0.1.42] Unused Requirements - Unused Alias [\#629](https://github.com/cursive-ide/cursive/issues/629)
- Suggestion - Organize (ns) - 0.1.04 [\#77](https://github.com/cursive-ide/cursive/issues/77)
- Identify unused namespaces (via import or require) - 0.1.04 [\#75](https://github.com/cursive-ide/cursive/issues/75)

### Fixed

- Cursive occasionally excludes entire project [\#2648](https://github.com/cursive-ide/cursive/issues/2648)
- Could not create shim [\#2647](https://github.com/cursive-ide/cursive/issues/2647)
- Running tests with Leiningen results in exception [\#2621](https://github.com/cursive-ide/cursive/issues/2621)
- REPL history move commands are broken in Cursive 1.12.0 & 1.12.1 [\#2620](https://github.com/cursive-ide/cursive/issues/2620)
- Code completion doesn't work with renamed, referred vars [\#1544](https://github.com/cursive-ide/cursive/issues/1544)
- Autocomplete of field removes dot [\#1096](https://github.com/cursive-ide/cursive/issues/1096)
- alias marked as unused but it is used [\#638](https://github.com/cursive-ide/cursive/issues/638)

## 1.12.1 - 2021-11-30

### Fixed

- Cursive is binary incompatible with 2021.3 final release [\#2618](https://github.com/cursive-ide/cursive/issues/2618)

## 1.12.0 - 2021-11-29

### Added

- Add support for Package Search [\#2601](https://github.com/cursive-ide/cursive/issues/2601)
- Suport the new require `:as-alias` option [\#2592](https://github.com/cursive-ide/cursive/issues/2592)
- Allow attaching sources to dependencies [\#2591](https://github.com/cursive-ide/cursive/issues/2591)
- Cursive should respect :classpath-overrides [\#2590](https://github.com/cursive-ide/cursive/issues/2590)
- Cursive plugin doesn't work with Intellij IDEA 2021.3 EAP [\#2589](https://github.com/cursive-ide/cursive/issues/2589)
- Add support for tools build [\#2580](https://github.com/cursive-ide/cursive/issues/2580)
- Support selecting the clojure CLI config directory [\#2212](https://github.com/cursive-ide/cursive/issues/2212)

### Changed

- Format forms for comparison when using test runner [\#2609](https://github.com/cursive-ide/cursive/issues/2609)
- Make structural movement commands work better on comments [\#2593](https://github.com/cursive-ide/cursive/issues/2593)
- Map indentation option when key and value are on separate lines [\#2547](https://github.com/cursive-ide/cursive/issues/2547)
- Be (optionally) able to skip map alignment by inserting blank lines [\#2026](https://github.com/cursive-ide/cursive/issues/2026)

### Fixed

- Structural actions don't work in test result diffs [\#2611](https://github.com/cursive-ide/cursive/issues/2611)
- Cursive causes IDE Hang [\#2587](https://github.com/cursive-ide/cursive/issues/2587)
- JetBrain's "Code with Me" plugin doesn't share the REPL [\#2486](https://github.com/cursive-ide/cursive/issues/2486)
- Stop stealing focus when starting REPL [\#1579](https://github.com/cursive-ide/cursive/issues/1579)

## 1.11.0 - 2021-09-17

### Added

- Add support for Grazie grammar checker [\#2579](https://github.com/cursive-ide/cursive/issues/2579)
- Babashka problem inventory [\#2516](https://github.com/cursive-ide/cursive/issues/2516)
- Support babashka as valid REPL target [\#2452](https://github.com/cursive-ide/cursive/issues/2452)

### Fixed

- New versions of Tools Deps breaks git SHA support [\#2581](https://github.com/cursive-ide/cursive/issues/2581)
- test markers not staying visible in gutter [\#2574](https://github.com/cursive-ide/cursive/issues/2574)
- [Deps] Sub-modules with same name do not resolve correctly in IntelliJ [\#2391](https://github.com/cursive-ide/cursive/issues/2391)

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

