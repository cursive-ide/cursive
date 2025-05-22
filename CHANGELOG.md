# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)

## 2025.2-eap1 - 2025-05-22

### Added

- Add support for 2025.2 EAP [\#3031](https://github.com/cursive-ide/cursive/issues/3031)

### Fixed

- Can't open DevTools when showing HTML using :display :editor [\#3033](https://github.com/cursive-ide/cursive/issues/3033)
- Tagged literals printed incorrectly, space removed [\#3032](https://github.com/cursive-ide/cursive/issues/3032)

## 2025.1.1 - 2025-05-16

### Fixed

- "Dependency Cycle" bug when loading taoensso.nippy [\#3026](https://github.com/cursive-ide/cursive/issues/3026)

## 2025.1 - 2025-04-16

### Added

- Add support for 2025.1 EAP [\#3009](https://github.com/cursive-ide/cursive/issues/3009)
- Mark known clojure directories as excluded by default [\#2969](https://github.com/cursive-ide/cursive/issues/2969)
- Reformatting doesn't reflow doc strings [\#653](https://github.com/cursive-ide/cursive/issues/653)

### Changed

- Repl scope configuration is very confusing. [\#3008](https://github.com/cursive-ide/cursive/issues/3008)
- Add an option "Use open REPL pane" to restore previous behaviour [\#2988](https://github.com/cursive-ide/cursive/issues/2988)
- REPL commands intended for CLJ REPLs don't work in CLJS or EDN files [\#2985](https://github.com/cursive-ide/cursive/issues/2985)

### Fixed

- Cannot load namespace into a build.clj REPL [\#3023](https://github.com/cursive-ide/cursive/issues/3023)
- Problems resolving source path from library overridden in user deps.edn [\#3022](https://github.com/cursive-ide/cursive/issues/3022)
- Error printing Java object [\#3021](https://github.com/cursive-ide/cursive/issues/3021)
- Problems printing unreadable exceptions [\#3020](https://github.com/cursive-ide/cursive/issues/3020)
- Adding new modules to a project with name conflicts fails [\#3012](https://github.com/cursive-ide/cursive/issues/3012)
- Cursive doesn't correctly resolve data readers from libraries [\#3011](https://github.com/cursive-ide/cursive/issues/3011)
- "Show virtual space at the bottom of the file" setting causes inline diffs to expand infinitely [\#3010](https://github.com/cursive-ide/cursive/issues/3010)
- Re-run last test action does not in HTML files [\#3007](https://github.com/cursive-ide/cursive/issues/3007)
- *print-dup* breaks REPL test integration [\#3006](https://github.com/cursive-ide/cursive/issues/3006)
- New Method Reference syntax for instance methods is flakey [\#2997](https://github.com/cursive-ide/cursive/issues/2997)
- "Internal error: cannot patch the selected configuration" when running debugger [\#2995](https://github.com/cursive-ide/cursive/issues/2995)
- test exceptions not shown sometimes, "Error handling response" in repl [\#2994](https://github.com/cursive-ide/cursive/issues/2994)
- `cursive.repl.runtime.errors/ex->data` throws [\#2993](https://github.com/cursive-ide/cursive/issues/2993)
- Thread/interrupted receives incorrect warning [\#2989](https://github.com/cursive-ide/cursive/issues/2989)
- Config items in new REPL settings pane are not searchable [\#2987](https://github.com/cursive-ide/cursive/issues/2987)
- Cannot "Clear Output for Current REPL" anymore if its not running [\#2984](https://github.com/cursive-ide/cursive/issues/2984)
- Test runner reports failing tests as passed if actual or expected contains ansi color codes [\#2973](https://github.com/cursive-ide/cursive/issues/2973)
- `IllegalArgumentException` with `:shrunk` field in custom `IPersistentMap` implementation [\#2966](https://github.com/cursive-ide/cursive/issues/2966)

## 1.14.0 - 2024-11-13

### Added

- Automatically create run configurations on project open/creation [\#2951](https://github.com/cursive-ide/cursive/issues/2951)
- Support for inline form evaluation + watching [\#391](https://github.com/cursive-ide/cursive/issues/391)

### Changed

- Update rainbow parens colours to use colour palette from new UI guidelines [\#2948](https://github.com/cursive-ide/cursive/issues/2948)
- Show directory in editor tabs for non unique file names [\#2946](https://github.com/cursive-ide/cursive/issues/2946)

### Fixed

- Synchronizing Leiningen projects give errors about writing in EDT [\#2952](https://github.com/cursive-ide/cursive/issues/2952)
- Test exceptions/errors not printed in the REPL [\#2950](https://github.com/cursive-ide/cursive/issues/2950)

## 1.13.5 - 2024-08-10

### Fixed

- Fix regression of #2923 [\#2944](https://github.com/cursive-ide/cursive/issues/2944)

## 1.13.4 - 2024-08-06

### Added

- Add support for IntelliJ 2024.2 EAP [\#2904](https://github.com/cursive-ide/cursive/issues/2904)

### Changed

- Update icons for new UI [\#2935](https://github.com/cursive-ide/cursive/issues/2935)
- Allow switching between inlay contents when tests have multiple results [\#2926](https://github.com/cursive-ide/cursive/issues/2926)
- Allow switching between test result diffs in diff pane [\#2924](https://github.com/cursive-ide/cursive/issues/2924)
- Update support for new interop syntax [\#2910](https://github.com/cursive-ide/cursive/issues/2910)
- Report raw test results [\#2687](https://github.com/cursive-ide/cursive/issues/2687)
- [Deps] resources dir incorrectly classified in IntelliJ's project structure [\#2400](https://github.com/cursive-ide/cursive/issues/2400)

### Fixed

- Tests marked as green despite failure [\#2940](https://github.com/cursive-ide/cursive/issues/2940)
- REPL process output not passed through *out*/*err* doesn't receive ANSI highlighting [\#2932](https://github.com/cursive-ide/cursive/issues/2932)
- Spurious error running Clojure Application run configs with deps [\#2931](https://github.com/cursive-ide/cursive/issues/2931)
- Failure details not reported for assertions inside fixtures [\#2929](https://github.com/cursive-ide/cursive/issues/2929)
- "Load File in REPL" stopped working [\#2927](https://github.com/cursive-ide/cursive/issues/2927)
- Cursive causing UI freezes [\#2920](https://github.com/cursive-ide/cursive/issues/2920)
- Inner classes don't present popup to import [\#2917](https://github.com/cursive-ide/cursive/issues/2917)
- NumberFormatException trying to connect to babashka-REPL [\#2909](https://github.com/cursive-ide/cursive/issues/2909)
- "Load File in REPL" gives IndexOutOfBounds [\#2896](https://github.com/cursive-ide/cursive/issues/2896)
- Test failures from matcher-combinators have stopped displaying [\#2787](https://github.com/cursive-ide/cursive/issues/2787)
- Expected and actual values are swapped compared to typical Clojure test runners in test diffs [\#2775](https://github.com/cursive-ide/cursive/issues/2775)
- Test marked successful in cursive yet fails (correctly) with cognitect test runner [\#2744](https://github.com/cursive-ide/cursive/issues/2744)
- Organize imports removes imported Java classes if method calls use reflection [\#2734](https://github.com/cursive-ide/cursive/issues/2734)
- Load File in REPL throws exception [\#2664](https://github.com/cursive-ide/cursive/issues/2664)

## 1.13.3 - 2024-04-04

### Fixed

- Error generating stubs with 1.13.2 [\#2891](https://github.com/cursive-ide/cursive/issues/2891)

## 1.13.2 - 2024-04-04

### Added

- Add support for new language syntax in Clojure 1.12 [\#2878](https://github.com/cursive-ide/cursive/issues/2878)
- Add support for IntelliJ 2024.1 EAP [\#2871](https://github.com/cursive-ide/cursive/issues/2871)
- Code vision for references [\#2741](https://github.com/cursive-ide/cursive/issues/2741)
- Add Programmatic Setting of Remote REPL Host [\#2559](https://github.com/cursive-ide/cursive/issues/2559)

### Changed

- Simplify folding [\#2890](https://github.com/cursive-ide/cursive/issues/2890)
- Update Maven completion code in 2024.1 [\#2889](https://github.com/cursive-ide/cursive/issues/2889)
- Improvements to usages inlay hints [\#2883](https://github.com/cursive-ide/cursive/issues/2883)
- Don't select namespace text when creating a new namespace [\#2881](https://github.com/cursive-ide/cursive/issues/2881)
- Use built-in action for showing type information [\#2877](https://github.com/cursive-ide/cursive/issues/2877)

### Fixed

- Error resolving dependencies with Leiningen 2.11 [\#2879](https://github.com/cursive-ide/cursive/issues/2879)
- When importing deps projects, Maven repos are no longer detected [\#2873](https://github.com/cursive-ide/cursive/issues/2873)
- `.deps.clj/1.11.1.1429/ClojureTools/TRANSACTION_START (No such file or directory)` error on start [\#2867](https://github.com/cursive-ide/cursive/issues/2867)
- Cursive ide makes intellij freeze and ruins project when running test [\#2752](https://github.com/cursive-ide/cursive/issues/2752)
- Type inference does not work correctly for Class objects [\#2422](https://github.com/cursive-ide/cursive/issues/2422)
- Incorrect type inference for anonymous functions [\#1278](https://github.com/cursive-ide/cursive/issues/1278)

## 1.13.1 - 2023-12-07

### Added

- Support 2023.3 EAP [\#2840](https://github.com/cursive-ide/cursive/issues/2840)
- Implement Context Info [\#2838](https://github.com/cursive-ide/cursive/issues/2838)
- File Structure support for EDN files [\#2706](https://github.com/cursive-ide/cursive/issues/2706)
- Unable to select aliases when importing deps project [\#2285](https://github.com/cursive-ide/cursive/issues/2285)
- Add breadcrumbs [\#1793](https://github.com/cursive-ide/cursive/issues/1793)

### Changed

- When sending forms to REPL, they should include any metadata [\#2859](https://github.com/cursive-ide/cursive/issues/2859)
- Please enable stub generation for Rama [\#2855](https://github.com/cursive-ide/cursive/issues/2855)
- Clarify warning message when syncing using tools aliases [\#2826](https://github.com/cursive-ide/cursive/issues/2826)
- Add stub generation support for Specter [\#2767](https://github.com/cursive-ide/cursive/issues/2767)
- Cursive & Specter not playing nicely [\#1973](https://github.com/cursive-ide/cursive/issues/1973)

### Fixed

- Exceptions thrown when file's file type is overridden [\#2858](https://github.com/cursive-ide/cursive/issues/2858)
- Exception when keyword is used in clojure.test/testing [\#2857](https://github.com/cursive-ide/cursive/issues/2857)
- :local/root deps from within git deps are incorrectly added as modules [\#2845](https://github.com/cursive-ide/cursive/issues/2845)
- The project has an outdated format on startup [\#2835](https://github.com/cursive-ide/cursive/issues/2835)
- deps.clj is not correctly downloaded if user doesn't have it installed at startup [\#2832](https://github.com/cursive-ide/cursive/issues/2832)
- :local/root dependencies do not work correctly on Windows [\#2831](https://github.com/cursive-ide/cursive/issues/2831)
- local/root deps are not handled correctly when using paths outside referring project [\#2829](https://github.com/cursive-ide/cursive/issues/2829)
- Deps modules which are converted to libraries are incorrectly shown in project view before sync [\#2823](https://github.com/cursive-ide/cursive/issues/2823)
- New deps integration doesn't handle case when project requires aliases to sync [\#2822](https://github.com/cursive-ide/cursive/issues/2822)
- New deps integration doesn't correctly handle :mvn/local-repo [\#2821](https://github.com/cursive-ide/cursive/issues/2821)
- New IDE zoom doesn't affect the REPL-window [\#2793](https://github.com/cursive-ide/cursive/issues/2793)
- Leiningen task command line parameters with spaces [\#2769](https://github.com/cursive-ide/cursive/issues/2769)
- Ctrl+Mousewheel REPL zoom [\#2766](https://github.com/cursive-ide/cursive/issues/2766)
- Test markers not visible in the gutter [\#2762](https://github.com/cursive-ide/cursive/issues/2762)
- IntelliJ IDEA 2022.1.2 REPL Pinch to zoom [\#2726](https://github.com/cursive-ide/cursive/issues/2726)
- Variable binding is wrong on if-let [\#500](https://github.com/cursive-ide/cursive/issues/500)

## 1.13.0 - 2023-07-11

### Added

- Allow defaulting of modules for run configurations when created from context [\#2818](https://github.com/cursive-ide/cursive/issues/2818)
- Make URLs in strings clickable [\#2804](https://github.com/cursive-ide/cursive/issues/2804)
- Allow running tools.build REPLs [\#2653](https://github.com/cursive-ide/cursive/issues/2653)
- Support adding brick as :extra-deps for a Polylith workspace in development [\#2554](https://github.com/cursive-ide/cursive/issues/2554)
- deps.edn: add support for alias types other than -A [\#2409](https://github.com/cursive-ide/cursive/issues/2409)

### Fixed

- Stubs generation doesn't correctly stop when encountering errors [\#2814](https://github.com/cursive-ide/cursive/issues/2814)
- Problems when generating stubs due to interactions with user.clj [\#2808](https://github.com/cursive-ide/cursive/issues/2808)
- Cursive doesn't resolve deftype fields containing dashes when accessed using field syntax [\#2797](https://github.com/cursive-ide/cursive/issues/2797)
- Introduce Variable with Parinfer breaks code [\#2786](https://github.com/cursive-ide/cursive/issues/2786)
- replace-deps/paths in aliases stopped working around 1.12.3 [\#2689](https://github.com/cursive-ide/cursive/issues/2689)
- Rename variable with Parinfer breaks code [\#2106](https://github.com/cursive-ide/cursive/issues/2106)

## 1.12.8 - 2023-03-28

### Added

- Add support for IntelliJ 2023.1 EAP [\#2764](https://github.com/cursive-ide/cursive/issues/2764)
- Support Evaluating Bookmarked Forms [\#2623](https://github.com/cursive-ide/cursive/issues/2623)
- "Reload all from disk" after REPL command  [\#2597](https://github.com/cursive-ide/cursive/issues/2597)
- Execute REPL command in current file namespace [\#1756](https://github.com/cursive-ide/cursive/issues/1756)
- Support inline output replace on REPL commands [\#1755](https://github.com/cursive-ide/cursive/issues/1755)
- "Clear REPL" before executing a REPL command  [\#1459](https://github.com/cursive-ide/cursive/issues/1459)
- Add ability to delete items from REPL history [\#1383](https://github.com/cursive-ide/cursive/issues/1383)

### Changed

- Improve ordering of entries in Edit REPL Commands window [\#2622](https://github.com/cursive-ide/cursive/issues/2622)
- REPL commands get added to REPL history [\#1990](https://github.com/cursive-ide/cursive/issues/1990)
- Edit REPL Commands window should have + button to create a REPL command [\#1415](https://github.com/cursive-ide/cursive/issues/1415)
- Missing command? [\#843](https://github.com/cursive-ide/cursive/issues/843)

### Fixed

- :as-alias doesn't correctly prevent cyclic dependency warnings in CLJS [\#2782](https://github.com/cursive-ide/cursive/issues/2782)
- Incorrect indentation when adding new require clauses to ns form [\#2763](https://github.com/cursive-ide/cursive/issues/2763)
- REPL does not automatically select .shadow-cljs/nrepl.port for nREPL connection type [\#2759](https://github.com/cursive-ide/cursive/issues/2759)
- Sometimes unable to view diff on test failure [\#2723](https://github.com/cursive-ide/cursive/issues/2723)
- REPL History window opens on secondary monitor [\#2294](https://github.com/cursive-ide/cursive/issues/2294)
- REPL history hangs Intellij [\#1325](https://github.com/cursive-ide/cursive/issues/1325)
- REPL Search History Renders Incorrectly [\#971](https://github.com/cursive-ide/cursive/issues/971)

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

## 1.4.3 - 2017-03-09

- Cursive 1.4.0 stop working with idea 2016.3 [\#1602](https://github.com/cursive-ide/cursive/issues/1602)

## 1.4.0 - 2017-11-16

- Option to deactivate editor frame on REPL command [\#1562](https://github.com/cursive-ide/cursive/issues/1562)
- Unable to run Leiningen tasks with 1.4.0-eap3 [\#1561](https://github.com/cursive-ide/cursive/issues/1561)
- Occasional NPEs with 1.4.0-eap3 [\#1560](https://github.com/cursive-ide/cursive/issues/1560)
- Cursive 1.4.0-eap3 can’t open REPLs in JDK 7 projects (probably because of code compiled for JDK 8) [\#1555](https://github.com/cursive-ide/cursive/issues/1555)
- when reading project.clj, set OS cwd to enclosing project.clj folder (IDEA 2016.3 EAP regression) [\#1551](https://github.com/cursive-ide/cursive/issues/1551)
- Assoc incorrectly indented 1.4.0-eap3-2016.2 [\#1550](https://github.com/cursive-ide/cursive/issues/1550)
- 1.4.0-eap3 fails when importing multi module projects with :version [\#1548](https://github.com/cursive-ide/cursive/issues/1548)
- Error running Leiningen tasks using trampoline in 1.4.0 EAPs [\#1547](https://github.com/cursive-ide/cursive/issues/1547)
- Error when using new managed deps functionality in lein 2.7.0 [\#1543](https://github.com/cursive-ide/cursive/issues/1543)
- unable to launch a repl for projects that don't explicitly declare clojure version [\#1542](https://github.com/cursive-ide/cursive/issues/1542)
- Support 2016.3 EAP [\#1527](https://github.com/cursive-ide/cursive/issues/1527)
- Error generating stubs for module ...: Exception in thread "main" [\#1524](https://github.com/cursive-ide/cursive/issues/1524)
- Stub generation process should filter out var overwrite warnings [\#1515](https://github.com/cursive-ide/cursive/issues/1515)
- Stub generation process should not use debug JVM flags from project.clj [\#1514](https://github.com/cursive-ide/cursive/issues/1514)
- Renaming alias does not change namespaced keywords [\#1511](https://github.com/cursive-ide/cursive/issues/1511)
- Cursive deadlock on IDEA startup when upgrading to the latest version [\#1508](https://github.com/cursive-ide/cursive/issues/1508)
- Support Leiningen 2.7.0 [\#1506](https://github.com/cursive-ide/cursive/issues/1506)
- Ability to ignore certain "Require namespace" hints [\#1499](https://github.com/cursive-ide/cursive/issues/1499)
- Keys for :or should be locally bound, not keywords or qualified symbols [\#1495](https://github.com/cursive-ide/cursive/issues/1495)
- Support CLJS namespace aliasing [\#1481](https://github.com/cursive-ide/cursive/issues/1481)
- Pick up remote repl port from .nrepl-port in Maven/boot projects [\#1473](https://github.com/cursive-ide/cursive/issues/1473)
- Add support for new namespacing in Clojure 1.9-alpha8 [\#1450](https://github.com/cursive-ide/cursive/issues/1450)
- Suggestions list - missing live template description/abbreviation [\#1442](https://github.com/cursive-ide/cursive/issues/1442)
- No closing parenthesis when starting anonymous function shorthand [\#1265](https://github.com/cursive-ide/cursive/issues/1265)
- Nil Language Error on Clojure Code Blocks in Markdown [\#1256](https://github.com/cursive-ide/cursive/issues/1256)
- Possible incorrect indentation for forms used in anonymous functions [\#1227](https://github.com/cursive-ide/cursive/issues/1227)
- constant NullPointerExceptions [\#1216](https://github.com/cursive-ide/cursive/issues/1216)
- Cursive throws an exception when entering `{:12345 :abc}` [\#1010](https://github.com/cursive-ide/cursive/issues/1010)
- Detect/suggest correct Clojure filetype [\#904](https://github.com/cursive-ide/cursive/issues/904)
- Put Datomic Stubs on Clojars [\#896](https://github.com/cursive-ide/cursive/issues/896)
- Add support for converting .clj files to .cljc files [\#893](https://github.com/cursive-ide/cursive/issues/893)
- Find usages [\#847](https://github.com/cursive-ide/cursive/issues/847)
- DEBUG: unknown status need-input when trying to REPL ClojureScript [\#358](https://github.com/cursive-ide/cursive/issues/358)
- Additional source path outside of project dir not included (no additional content root generated) [\#324](https://github.com/cursive-ide/cursive/issues/324)
- Add support for console input [\#228](https://github.com/cursive-ide/cursive/issues/228)

## 1.2.7 - 2016-05-16

- Can't use space when on Parinfer mode [\#1398](https://github.com/cursive-ide/cursive/issues/1398)
- Run configuration icons for HiRes displays [\#1378](https://github.com/cursive-ide/cursive/issues/1378)
- "Evaluate Expression" and "Watches" do not work with Clojure 1.8 [\#1370](https://github.com/cursive-ide/cursive/issues/1370)
- Gutter icons are too small on retina screens (1.2.1) [\#1310](https://github.com/cursive-ide/cursive/issues/1310)
- [0.1.43] Spurious error "inserted id is not valid" [\#709](https://github.com/cursive-ide/cursive/issues/709)

## 1.2.6 - 2016-05-02

- Unable to find or copy inside repl result text box. [\#1381](https://github.com/cursive-ide/cursive/issues/1381)
- Copy from REPL window not working [\#1380](https://github.com/cursive-ide/cursive/issues/1380)
- Keybinding: Move focus to REPL input [\#1372](https://github.com/cursive-ide/cursive/issues/1372)
- 'Clear output for current REPL' button should be active when there is no REPL connected [\#1107](https://github.com/cursive-ide/cursive/issues/1107)

## 1.2.5 - 2016-04-28

- Keybinding: Send selected form to REPL [\#1371](https://github.com/cursive-ide/cursive/issues/1371)
- Option to permanently disable parinfer, or issue warning [\#1369](https://github.com/cursive-ide/cursive/issues/1369)
- Parinfer can break code on symbol rename refactoring by prematurely removing spaces [\#1359](https://github.com/cursive-ide/cursive/issues/1359)
- Parinfer should automatically wrap forms [\#1357](https://github.com/cursive-ide/cursive/issues/1357)
- Load file in REPL doesn't work for local REPL [\#1349](https://github.com/cursive-ide/cursive/issues/1349)
- Invalid numeric-prefixed symbol literals are not highlighted as compile errors [\#1328](https://github.com/cursive-ide/cursive/issues/1328)
- Reformat splits symbols starting with % [\#1317](https://github.com/cursive-ide/cursive/issues/1317)
- Intellij crashes when adding a leiningen project [\#1230](https://github.com/cursive-ide/cursive/issues/1230)
- Send Top Form to REPL should send previous form when invoked between two forms [\#1225](https://github.com/cursive-ide/cursive/issues/1225)
- "Move caret to matching brace" doesn't work in the REPL [\#1103](https://github.com/cursive-ide/cursive/issues/1103)
- Keyword incorrectly marked as 'Invalid token: ":/"' [\#772](https://github.com/cursive-ide/cursive/issues/772)
- clojure.core// not recognized as symbol; "Expected symbol: /" [\#245](https://github.com/cursive-ide/cursive/issues/245)

## 1.2.4 - 2016-04-14

- Paredit – closing brackets not inserted before tokens, spaces not inserted anywhere [\#1347](https://github.com/cursive-ide/cursive/issues/1347)

## 1.2.3 - 2016-04-05

- Tab stop [\#1346](https://github.com/cursive-ide/cursive/issues/1346)
- Parinfer doesn't insert space for new forms [\#1344](https://github.com/cursive-ide/cursive/issues/1344)
- Inserting parenthesis on newline fails with parinfer [\#1343](https://github.com/cursive-ide/cursive/issues/1343)
- Parinfer breaks when using \[ and \] [\#1342](https://github.com/cursive-ide/cursive/issues/1342)
- Emacs tab indent doesn't work on last line in Parinfer on 1.2.2 [\#1341](https://github.com/cursive-ide/cursive/issues/1341)
- Parinfer triggers on-the-fly code analysis every time the cursor is moved leading to lagginess [\#1333](https://github.com/cursive-ide/cursive/issues/1333)
- Parinfer does not respect "Maintain selection when surrounding with braces" [\#1319](https://github.com/cursive-ide/cursive/issues/1319)
- Undo after parinfer jumps cursor back to wrong position [\#1299](https://github.com/cursive-ide/cursive/issues/1299)

## 1.2.2 - 2016-04-01

- Cursive not generating java classes from ns with gen-class [\#1326](https://github.com/cursive-ide/cursive/issues/1326)
- Parinfer REPL editor spams command history [\#1324](https://github.com/cursive-ide/cursive/issues/1324)
- Editing map literal with parinfer [\#1323](https://github.com/cursive-ide/cursive/issues/1323)
- Parinfer does not work correctly in REPL editor [\#1316](https://github.com/cursive-ide/cursive/issues/1316)
- Running Lein run configurations produces "KotlinReflectionNotSupportedError" [\#1308](https://github.com/cursive-ide/cursive/issues/1308)
- Parinfer paren inference not working [\#1307](https://github.com/cursive-ide/cursive/issues/1307)
- parinfer doesn't allow :let binding [\#1306](https://github.com/cursive-ide/cursive/issues/1306)
- After upgrade to 1.2.1, Tab key no longer works for executing (expanding) Live Templates [\#1305](https://github.com/cursive-ide/cursive/issues/1305)
- Tab key doesn't add spaces anymore if Structure Edit is OFF [\#1304](https://github.com/cursive-ide/cursive/issues/1304)
- After installing 1.2.1, no autocomplete [\#1302](https://github.com/cursive-ide/cursive/issues/1302)
- parinfer behaves oddly in split window [\#1301](https://github.com/cursive-ide/cursive/issues/1301)
- keyword syntax broken in 1.2.1-2016.1 [\#1300](https://github.com/cursive-ide/cursive/issues/1300)
- Requiring manifold.deferred yields cyclic dependency error on "Load files in REPL" [\#1298](https://github.com/cursive-ide/cursive/issues/1298)
- Unable to download sources [1.1.0, IntelliJ 14.1.5] [\#1206](https://github.com/cursive-ide/cursive/issues/1206)

## 1.2.0 - 2016-03-20

- Settings Repository with Cursive Licence [\#1291](https://github.com/cursive-ide/cursive/issues/1291)
- Leiningen warning banner for unregistered project.clj is broken [\#1289](https://github.com/cursive-ide/cursive/issues/1289)
- Leiningen 2.6.1? [\#1262](https://github.com/cursive-ide/cursive/issues/1262)
- Sync files in REPL syncs files not under source roots [\#1255](https://github.com/cursive-ide/cursive/issues/1255)
- Test actions don't obey the transitive loading flag [\#1254](https://github.com/cursive-ide/cursive/issues/1254)
- Make Cursive compatible with IntelliJ 16 EAP [\#1228](https://github.com/cursive-ide/cursive/issues/1228)
- Integrate parinfer functionality [\#1155](https://github.com/cursive-ide/cursive/issues/1155)

