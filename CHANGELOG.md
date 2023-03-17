# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)

## 1.12.8-eap5 - 2023-03-17

### Fixed

- :as-alias doesn't correctly prevent cyclic dependency warnings in CLJS [\#2782](https://github.com/cursive-ide/cursive/issues/2782)

## 1.12.8-eap4 - 2023-03-13

### Fixed

- REPL does not automatically select .shadow-cljs/nrepl.port for nREPL connection type [\#2759](https://github.com/cursive-ide/cursive/issues/2759)

## 1.12.8-eap3 - 2023-03-01

### Added

- Support Evaluating Bookmarked Forms [\#2623](https://github.com/cursive-ide/cursive/issues/2623)
- Add ability to delete items from REPL history [\#1383](https://github.com/cursive-ide/cursive/issues/1383)

### Fixed

- Sometimes unable to view diff on test failure [\#2723](https://github.com/cursive-ide/cursive/issues/2723)
- REPL History window opens on secondary monitor [\#2294](https://github.com/cursive-ide/cursive/issues/2294)
- REPL history hangs Intellij [\#1325](https://github.com/cursive-ide/cursive/issues/1325)
- REPL Search History Renders Incorrectly [\#971](https://github.com/cursive-ide/cursive/issues/971)

## 1.12.8-eap2 - 2023-02-08

### Added

- "Reload all from disk" after REPL command  [\#2597](https://github.com/cursive-ide/cursive/issues/2597)
- Support inline output replace on REPL commands [\#1755](https://github.com/cursive-ide/cursive/issues/1755)

### Changed

- REPL commands get added to REPL history [\#1990](https://github.com/cursive-ide/cursive/issues/1990)

## 1.12.8-eap1 - 2023-02-03

### Added

- Add support for IntelliJ 2023.1 EAP [\#2764](https://github.com/cursive-ide/cursive/issues/2764)
- Execute REPL command in current file namespace [\#1756](https://github.com/cursive-ide/cursive/issues/1756)
- "Clear REPL" before executing a REPL command  [\#1459](https://github.com/cursive-ide/cursive/issues/1459)

### Changed

- Improve ordering of entries in Edit REPL Commands window [\#2622](https://github.com/cursive-ide/cursive/issues/2622)
- Edit REPL Commands window should have + button to create a REPL command [\#1415](https://github.com/cursive-ide/cursive/issues/1415)
- Missing command? [\#843](https://github.com/cursive-ide/cursive/issues/843)

### Fixed

- Incorrect indentation when adding new require clauses to ns form [\#2763](https://github.com/cursive-ide/cursive/issues/2763)

## 1.12.7 - 2023-01-06

### Fixed

- Allow selecting up to date Leiningen versions [\#2732](https://github.com/cursive-ide/cursive/issues/2732)

## 1.12.6 - 2022-12-14

### Fixed

- "Could not create shim" error when using deps 1.11.1.1208 [\#2754](https://github.com/cursive-ide/cursive/issues/2754)
- 422 Unprocessable Entity error when submitting errors to tracker [\#2747](https://github.com/cursive-ide/cursive/issues/2747)

## 1.12.5 - 2022-11-30

### Added

- Add support for IntelliJ 2022.3 EAP [\#2733](https://github.com/cursive-ide/cursive/issues/2733)
- Add code author inlay hints [\#2698](https://github.com/cursive-ide/cursive/issues/2698)
- Add option "Always generate stubs (for this project|for all projects)" [\#2556](https://github.com/cursive-ide/cursive/issues/2556)
- Keep :require sorted [\#2002](https://github.com/cursive-ide/cursive/issues/2002)

### Changed

- Clean up temporary system deps files [\#2719](https://github.com/cursive-ide/cursive/issues/2719)
- Add ability for socket REPL to pick up the port from a file [\#2695](https://github.com/cursive-ide/cursive/issues/2695)
- Output to stderr when generating stubs is treated as an error [\#2654](https://github.com/cursive-ide/cursive/issues/2654)

### Fixed

- Error handling response - class java.lang.IllegalArgumentException: Argument for @NotNull parameter 'name' of com/intellij/psi/search/FilenameIndex.getVirtualFilesByName must not be null [\#2712](https://github.com/cursive-ide/cursive/issues/2712)
- Deftype method implementations show false errors in CLJC files when method arity over 1 [\#2346](https://github.com/cursive-ide/cursive/issues/2346)
- Invalid arity detection for protocol implementation [\#1431](https://github.com/cursive-ide/cursive/issues/1431)

## 1.12.4 - 2022-06-03

### Added

- Add support for 2022.2 [\#2697](https://github.com/cursive-ide/cursive/issues/2697)
- Identify context from `deftest` and `clojure.test/testing` in assertion failure  [\#2387](https://github.com/cursive-ide/cursive/issues/2387)
- "Show diff for error" intention [\#2229](https://github.com/cursive-ide/cursive/issues/2229)
- Better test.check support [\#2170](https://github.com/cursive-ide/cursive/issues/2170)
- Sidebar color display, like IntelliJ does for other languages [\#1844](https://github.com/cursive-ide/cursive/issues/1844)
- Add feature to run test.check defspec under caret [\#632](https://github.com/cursive-ide/cursive/issues/632)

### Changed

- Allow configuring AOT compilation to skip tests [\#2685](https://github.com/cursive-ide/cursive/issues/2685)

### Fixed

- When printing large ANSI-formatted output, items are sometimes duplicated [\#2702](https://github.com/cursive-ide/cursive/issues/2702)
- Multiple options not supported when creating lein projects from templates [\#2692](https://github.com/cursive-ide/cursive/issues/2692)
- Cannot load file in REPL with an :as-alias require that would be a cyclic dependency if it were loaded [\#2690](https://github.com/cursive-ide/cursive/issues/2690)
- Compiler error messages not correctly reported [\#2684](https://github.com/cursive-ide/cursive/issues/2684)
- Find usages of in other modules in project [\#2660](https://github.com/cursive-ide/cursive/issues/2660)
- deps alias with segments in namespace provokes failure [\#2536](https://github.com/cursive-ide/cursive/issues/2536)
- Displaying a very large diff for failed test completely hangs IDEA [\#2396](https://github.com/cursive-ide/cursive/issues/2396)
- ANSI color escapes can escape interpretation [\#2357](https://github.com/cursive-ide/cursive/issues/2357)
- Large test result previews don't display [\#2032](https://github.com/cursive-ide/cursive/issues/2032)
- Limiting output in test tooltip/test results [\#1680](https://github.com/cursive-ide/cursive/issues/1680)
- REPL logs error when running defspec [\#1525](https://github.com/cursive-ide/cursive/issues/1525)

## 1.12.3 - 2022-04-28

### Changed

- Make Cursive more forgiving in cases of unresolved symbols [\#2682](https://github.com/cursive-ide/cursive/issues/2682)
- Create src dir when creating new deps project [\#2675](https://github.com/cursive-ide/cursive/issues/2675)

### Fixed

- Symbol resolution customisation bug [\#2683](https://github.com/cursive-ide/cursive/issues/2683)
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

