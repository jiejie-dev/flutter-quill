## 12.0.1

 - **REFACTOR**: remove internal annotation from image_save_utils.dart.

## 12.0.0

> Note: This release has breaking changes.

 - **REVERT**: Rename quill_localizations.dart to quill_localizations.g.dart.
 - **REVERT**(example): using web embed builders for all platforms.
 - **REVERT**: changes of https://github.com/singerdmx/flutter-quill/commit/836451367ea5712bb93ea0891cc933806188bdb6.
 - **REVERT**: remove changes of https://github.com/singerdmx/flutter-quill/commit/0d695e9381fd9d889a36837a46b481821b85b95e#diff-06572a96a58dc510037d5efa622f9bec8519bc1beab13c9f251e97e657a9d4edR103 since they were not published to pub.dev.
 - **REVERT**: "Resolved issue with broken IME composing rect in Windows desktop" (#2266).
 - **REVERT**: disable rich text paste feature on web as a workaround (#2221).
 - **REVERT**(translations): restore deleted cut and paste keys for english only.
 - **REVERT**: Remove unpublished 9.3.16-experimental version by CI.
 - **REVERT**: updating the CHANGELOG.md files wihtout release the changes.
 - **REVERT**: package version from 9.3.14 to 9.3.13.
 - **REVERT**: fix the version of the packages by restoring it to the previous state.
 - **REVERT**: fix selection.affinity always downstream after updateEditingValue.
 - **REVERT**: move sub packages to `./packages`" (#1717).
 - **REVERT**: Remove unneeded widget.
 - **REVERT**: Bug fix temporary.
 - **REVERT**: Update bug template.
 - **REVERT**: add new line.
 - **REFACTOR**: remove media_pick_setting.dart.
 - **REFACTOR**: moved shortcuts and onKeyEvents to its own file (#2223).
 - **REFACTOR**: use immutable annotation from flutter foundation instead of meta package in flutter_quill.
 - **REFACTOR**: restructure project into modular architecture for flutter_quill (#2032).
 - **REFACTOR**: Moved core link button functions to link.dart (#2008).
 - **REFACTOR**: context menu function, add test code (#1979).
 - **REFACTOR**(publishing-workflow): move fethcing GitHub release notes steps into a dart script.
 - **REFACTOR**: Rename pubspec_overrides.yaml.g to pubspec_overrides.yaml.disabled.
 - **PERF**: Performance optimization (#1964).
 - **FIX**(toolbar): regard showDividers in simple toolbar (#2172).
 - **FIX**: Clicking on the Link icon without any text on a new line will crash.
 - **FIX**: link menu action Cupertino modal popup now does NOT use root nav (#2332).
 - **FIX**(macos): Implement actions for ExpandSelectionToDocumentBoundaryIntent and ExpandSelectionToLineBreakIntent to use keyboard shortcuts, unrelated cleanup to the bug fix. (#2279).
 - **FIX**: allow all correct URLs to be formatted (#2328).
 - **FIX**: avoid using getClipboardFiles() if unsupported on the current platform.
 - **FIX**(example): build failure on Android with latest version of Android Studio Ladybug (#2312).
 - **FIX**(ci): use fixed version of simple_spell_checker to fix CI warnings.
 - **FIX**: replace flutter_keyboard_visibility with flutter_keyboard_visibility_temp_fork to support Flutter/Wasm target (#2293).
 - **FIX**: fixed casting null to Tuple2 when link dialog is dismissed without any input (e.g. barrier dismissed) (#681).
 - **FIX**: update version range of quill_native_bridge to avoid using latest version of the package (#2283).
 - **FIX**: Resolved issue with broken IME composing rect in Windows desktop app (#2282).
 - **FIX**(ci): add flutter pub get step for quill_native_bridge to fix failure in #2264 (#2265).
 - **FIX**: the composing text did not show an underline during IME conversion (#2242).
 - **FIX**: Resolved issue with broken IME composing rect in Windows desktop app (#2239).
 - **FIX**: QuillToolbarToggleStyleButton Switching failure (#2234).
 - **FIX**(readme): use bold text for Markdown and HTML in HTML conversation section.
 - **FIX**: properties other than 'style' for custom inline code styles (such as 'backgroundColor') were not being applied correctly (#2226).
 - **FIX**: QuillEditor doesn't respect the system keyboard brightness by default on iOS (#2522).
 - **FIX**: Block Attributes are not displayed if the editor is empty (#2210).
 - **FIX**: export camera_types.dart to be able to configure QuillToolbarCameraButtonOptions.
 - **FIX**: use absolute URL to issue #2194 in CHANGE of 10.5.15-dev.0 to fix link on pub.dev.
 - **FIX**(readme): use absolute URLs for screenshots section instead of relative path to show on pub.dev.
 - **FIX**: Allow backspace at start of document to remove block elements and headers" (#2201).
 - **FIX**: Backspace remove block attributes at start (#2200).
 - **FIX**: Allow backspace at start of document to remove block elements and headers (#2198).
 - **FIX**: Assertion Failure in line.dart When Editing Text with Block-Level Attributes (#2174).
 - **FIX**: viewId when no View in context (#2662).
 - **FIX**: direction has no opposite effect is the language is rtl (#2154).
 - **FIX**: Unable to scroll 2nd editor window (#2152).
 - **FIX**: fix blank lines do not display when --web-renderer=html (#705).
 - **FIX**: Double click to select text sometimes doesn't work. (#2086)".
 - **FIX**: Loss of style when backspace (#2125).
 - **FIX**: unsafe operation while getting overlayEntry in text_selection (#2117).
 - **FIX**: context menu is visible even when selection is collapsed (#2116).
 - **FIX**: Link selection and editing (#2114).
 - **FIX**(example): image_cropper outdated version (#2100).
 - **FIX**: Double click to select text sometimes doesn't work. (#2086).
 - **FIX**: collectStyles for lists and alignments (#2082).
 - **FIX**: hide toolbar if editor loses focus (#2066).
 - **FIX**: manual checking of directionality (#2063).
 - **FIX**: invalid selection when tapping placeholder text (#2062).
 - **FIX**: RTL issues (#2060).
 - **FIX**: textInputAction is not set when creating QuillRawEditorConfigurations (#2057).
 - **FIX**: require 10.0.0 as minimum version for quill packages (#2035).
 - **FIX**: unpredictable endless loop of '_handleFocusChanged' in the phase of page route changing when editor is set to readonly. (#2488).
 - **FIX**(rule): PreserveInlineStyleRule assume the type of the operation data and throw stacktrace (#2028).
 - **FIX**: Key actions not being handled (#2025).
 - **FIX**: removed unicode from `QuillText` element that causes weird caret behavior (#2453).
 - **FIX**: delta_x tests fail (#2010).
 - **FIX**: typos in README.md of flutter_quill_extensions.
 - **FIX**: Fixed passing textStyle to formula embed (#1989).
 - **FIX**: LineHeight button to use MenuAnchor (#1986).
 - **FIX**(typo): fix typo ClipboardServiceProvider.instacne (#1983).
 - **FIX**: PreserveInlineStylesRule (#1980).
 - **FIX**: common link is detected as a video link (#1978).
 - **FIX**: make mouse right click to open context menu (#1976).
 - **FIX**(docs): update outdated code in markdown files.
 - **FIX**(editor): implement editor shortcut action for home and end keys to fix exception about unimplemented ScrollToDocumentBoundaryIntent (#1937).
 - **FIX**: search dialog throw an exception due to missing FlutterQuillLocalizations.delegate in the editor (#1938).
 - **FIX**: color picker hex unfocus on web (#1934).
 - **FIX**: Enabled link regex to be overridden (#1931).
 - **FIX**(publishing): create build directory if doesn't exist.
 - **FIX**: nextLine getter null where no assertion (#1061).
 - **FIX**(analysis): remove old import related to the recent changes of providing legacy search button.
 - **FIX**: Can not insert newline when Bold is toggled ON (#75).
 - **FIX**: assertion failure for swipe typing and undo on Android (#1898).
 - **FIX**: toolbar style change will be invalid when inputting more than 2 characters at a time (#1890).
 - **FIX**: Drop the support for formula in the editor.
 - **FIX**: fix runtime errors.
 - **FIX**: fix typos in PR template.
 - **FIX**: Color picker hex field (#2415).
 - **FIX**: Fixed handling of mac intents (#1089).
 - **FIX**: Use const constructor for EmbedBuilder (#1160).
 - **FIX**: pass iconButtonFactor to childBuilder.
 - **FIX**: analysis warrnings.
 - **FIX**: typos in using_custom_app_widget.md.
 - **FIX**: typos localizations_setup.md.
 - **FIX**: typos custom_embed_blocks.md.
 - **FIX**: typos custom_toolbar.md.
 - **FIX**: typos development_notes.md.
 - **FIX**: typos translation.md.
 - **FIX**: link in README.md of flutter_quill_extensions.
 - **FIX**: A bug in quill extensions.
 - **FIX**(CHANGELOG): use more descriptive bullet points (#1400).
 - **FIX**: outcommented clipboard status.
 - **FIX**: typo.
 - **FIX**: multiline styling stuck/not working properly (#1782).
 - **FIX**: removed misleading parameters (#1825).
 - **FIX**: added missed translations for ru, es, de (#1826).
 - **FIX**: MD Parsing for multi space (#1828).
 - **FIX**: FontFamily and FontSize toolbars track the text selected in the editor. (#1829).
 - **FIX**: typos in README.md.
 - **FIX**(publishing): update the workflow to not use deprecated command, and fix running the script command.
 - **FIX**: Indented position not holding while editing.
 - **FIX**: Undo/redo cursor position fixed (#1885).
 - **FIX**: Issue 1887 (#1892).
 - **FEAT**: Add configuration option to always indent on TAB key press (#2187).
 - **FEAT**: Removing check not allowing spell check on web (#2252).
 - **FEAT**: allow customising iconButtonFactor.
 - **FEAT**: Line height support (#1972).
 - **FEAT**: fix #2350.
 - **FEAT**(extensions): Youtube Video Player Support Mode (#1916).
 - **FEAT**: add zh_TW localization support (#2598).
 - **FEAT**: support multiple links insertion on the go (#579).
 - **FEAT**: add Amharic (ETHIOPIA) localization support (#2582).
 - **FEAT**: include spell checker for example app (#2127).
 - **FEAT**: Use quill_native_bridge as default impl in DefaultClipboardService, fix related bugs in the extensions package (#2230).
 - **FEAT**: Spellchecker for Flutter Quill (#2118).
 - **FEAT**: customizable character and space shortcut events (#2228).
 - **FEAT**: support for customize copy and cut Embeddables to Clipboard (#2067).
 - **FEAT**: Ability to add custom shortcuts (#1097).
 - **FEAT**: Enable BoxDecoration for DefaultTextBlockStyle of header Attribute (#2438).
 - **FEAT**: move cursor after inserting video/image (#1739).
 - **FEAT**: add callback to handle performAction (#2061).
 - **FEAT**: add paste gif from clipboard (#1788).
 - **FEAT**(l10n): localize all untranslated.json (#2217).
 - **FEAT**: Html converter package (#1523).
 - **FEAT**: cache for toPlainText in Document to avoid unnecessary text computing (#2482).
 - **FEAT**: allow to use custom callback QuillToolbarColorButton.
 - **FEAT**: Added builder for custom button in _LinkDialog (#1342).
 - **FEAT**: Add `readOnlyMouseCursor` to config mouse cursor type (#1873).
 - **FEAT**(clipboard): allow pasting markdown and html files from the system to the editor (#1915).
 - **FEAT**(flutter_quill_extensions): improve image save (#2403).
 - **FEAT**: allow to override link validation check, and accept mailto and other links by default (#2525).
 - **FEAT**: search bar improved (#1904).
 - **FEAT**: New way to get Delta from HTML inputs (#1984).
 - **FEAT**: added option to disable automatic list conversion (#2011).
 - **FEAT**: added Note to linkActionPickerDelegate (#741).
 - **FEAT**: custom leading builder (#2146).
 - **FEAT**(keyboard): support for customize onKey events, original PR #2345 (#2368).
 - **FEAT**(web): rich text paste from Clipboard using HTML (#2009).
 - **FEAT**: disableClipboard.
 - **DOCS**(changelog): super nit.
 - **DOCS**: update the translation markdown file to reflect the changes.
 - **DOCS**(changelog): add  in the CHANGELOG.
 - **DOCS**(changelog): document #2413 changes in unreleased section.
 - **DOCS**: remove What's changed in the CHANGELOG.md files for version 9.3.15.
 - **DOCS**: update outdated README.md in the root project folder.
 - **DOCS**: Add a note to not manually edit the CHANGELOG.md or the version for any of the packages.
 - **DOCS**: Update outdated README.md.
 - **DOCS**: Update the Contributing and add a few guidelines.
 - **DOCS**: update changelog for https://github.com/singerdmx/flutter-quill/pull/2579.
 - **DOCS**: address https://github.com/singerdmx/flutter-quill/pull/2427#discussion_r1920577655, document enableClipboardPaste to indicates that this is only applicable for the paste button.
 - **DOCS**: remove pub.dev package link in the README.md.
 - **DOCS**(readme): remove 'breaking changes' section.
 - **DOCS**(translations): update outdated translation page.
 - **DOCS**(translations): improve translation page.
 - **DOCS**: improve README.md.
 - **DOCS**(markdown-files): improve markdown docs files.
 - **DOCS**(markdown-files): improve readability.
 - **DOCS**: add spacing for Embed Blocks section in flutter_quill_extensions.
 - **DOCS**: add CODE_OF_CONDUCT.md.
 - **DOCS**(readme): include a note about converting HTML and Markdown to Delta in Conversion to HTML section.
 - **DOCS**(readme): add spacing between the We word and the blockquotes.
 - **DOCS**(readme): use inline code for plugin links.
 - **DOCS**(readme): update a note about using super_clipboard with flutter_quill.
 - **DOCS**: update custom_buttons to revert a minor change from previous commit.
 - **DOCS**: Update CHANGELOG.md and regenerate_versions.dart comments.
 - **DOCS**: Update CHANGELOG.md and translation.md.
 - **DOCS**(readme): update flutter_quill_extensions README to reflect the latest changes of table support, add ref when using the packages from git repository.
 - **DOCS**: Update todo and fix typo.
 - **DOCS**: Fix typos in the README.md.
 - **DOCS**: Update the custom toolbar example.
 - **DOCS**: Outdated custom embed blocks page.
 - **DOCS**: update flutter_quill_extensions CHANGELOG.
 - **DOCS**: fix typos README.md.
 - **DOCS**(readme): update super_clipboard plugin support message to be more specific.
 - **DOCS**: update outdated README.md in flutter_quill_extensions.
 - **DOCS**(readme): update 'Conversion to HTML' section to include more details (#1996).
 - **DOCS**(readme): fix bold text syntax issue in README.md.
 - **DOCS**(readme): update the 'Conversion to HTML' section to fix minor issue.
 - **DOCS**(readme): fix a few typos and invalid links in extensions package.
 - **DOCS**: fix a few typos and add list of local codes.
 - **DOCS**(readme): update the extensions package to document the Rich Text Paste feature on web, fix typos and split the section with more details (#2001).
 - **DOCS**: add const keyword for QuillSimpleToolbarConfigurations in README.
 - **DOCS**: add comment for toolbarSectionSpacing for QuillSimpleToolbar.
 - **DOCS**(changelog): include PR links to changes of https://github.com/singerdmx/flutter-quill/pull/2416.
 - **DOCS**: cleanup the docs, remove outdated resources, general changes (#2227).
 - **DOCS**(readme): fix Installation section reference link.
 - **DOCS**: Update CHANGELOG.md.
 - **DOCS**: add important note for contributors before introducing new features (#2269).
 - **DOCS**: remove table support note in README of flutter_quill_extensions due to #2254.
 - **DOCS**: Move CONTRIBUTING.md to the root folder.
 - **DOCS**: Update pull request template.
 - **DOCS**: Update README.md.
 - **DOCS**: a minor change in v11 migration for readability.
 - **DOCS**: add 'and' before videos in extensions package.
 - **DOCS**(readme): improve Input / Output section to clarify save/load document.
 - **DOCS**(readme): add 'Breaking Changes' section (#2275).
 - **DOCS**(readme): update flutter_keyboard_visibility to flutter_keyboard_visibility_temp_fork in plugins section.
 - **DOCS**(readme): improve the note message of quill_super_clipboard and quill_native_bridge.
 - **DOCS**: update links to master branch instead of release/v11.
 - **DOCS**(changelog): add unreleased change related to CI.
 - **DOCS**: update migration guide to relfect https://github.com/singerdmx/flutter-quill/pull/2529.
 - **DOCS**(readme): minor changes in README.md, indicating shortcut events in unsupported on mobile devices, fix outdated font family link.
 - **DOCS**(readme): improve README.md.
 - **DOCS**(changelog): add new change in Unreleased section.
 - **DOCS**(readme): use Github admonitions in Markdown blockquotes.
 - **BREAKING** **REVERT**: magnifier (#2413).
 - **BREAKING** **REFACTOR**: restructure project into modular architecture for flutter_quill_extensions (#2106).
 - **BREAKING** **REFACTOR**(plugins): move super clipboard to extensions package (#1914).
 - **BREAKING** **FIX**(extensions): drop support for YouTube iframeView for non-web platforms, remove youtube_player_flutter dependency, throw warnings for anything related to YoutubeVideoApp in development mode (#2286).
 - **BREAKING** **FEAT**: release version 11.0.0 with breaking changes (#2338).
 - **BREAKING** **FEAT**: add config class for clipboard action buttons (#2433).
 - **BREAKING** **CHORE**: move spell checker to example (#2145).
 - **BREAKING** **CHORE**: disable clipboard buttons in QuillSimpleToolbar by default.

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

> [!NOTE]
> The [previous `CHANGELOG.md`](https://github.com/singerdmx/flutter-quill/blob/master/doc/OLD_CHANGELOG.md) has been archived.

## [Unreleased]

### Added

- Added localization support for `mn` (Mongolian, Mongolia)

## [11.5.0] - 2025-10-18

### Fixed

- Fixed `View.of(context)` calls throwing when used with the `screenshot` package [#2662](https://github.com/singerdmx/flutter-quill/pull/2662).

### Added

- Add missing Brazilian Portuguese translations

## [11.4.2] - 2025-07-22

### Fixed

- **App crash on desktop platforms** when using Flutter `3.32.0-0.5.pre` and newer.  
  Fixed by passing the required `viewId` for experimental multi-window support [#2579](https://github.com/singerdmx/flutter-quill/pull/2579).

## [11.4.1] - 2025-05-15

### Added

- `copyWith` methods to `HorizontalSpacing`, `VerticalSpacing`, `DefaultTextBlockStyle`, and `DefaultListBlockStyle` for immutable updates of properties [#2550](https://github.com/singerdmx/flutter-quill/pull/2550).
- Finnish (fi) language translation [#2564](https://github.com/singerdmx/flutter-quill/pull/2564).

## [11.4.0] - 2025-04-23

### Added

- Accept `mailto`, `tel`, `sms`, and other link prefixes by default in the insert link toolbar button [#2525](https://github.com/singerdmx/flutter-quill/pull/2525).
- `validateLink` in `QuillToolbarLinkStyleButtonOptions` to allow overriding the link validation [#2525](https://github.com/singerdmx/flutter-quill/pull/2525).

### Fixed

- Improve doc comment of `customLinkPrefixes` in `QuillEditor` [#2525](https://github.com/singerdmx/flutter-quill/pull/2525).

### Changed

- Deprecate `linkRegExp` in favor of the new callback `validateLink` [#2525](https://github.com/singerdmx/flutter-quill/pull/2525).

## [11.3.0] - 2025-04-23

### Fixed

- Can't select text when `readOnly` is true [#2529](https://github.com/singerdmx/flutter-quill/pull/2529).

### Added

- Display magnifier using `RawMagnifier` widget when dragging on iOS/Android [#2529](https://github.com/singerdmx/flutter-quill/pull/2529).

## [11.2.0] - 2025-03-26

### Added

- Cache for `toPlainText` in `Document` class to avoid unnecessary text computing [#2482](https://github.com/singerdmx/flutter-quill/pull/2482).

## [11.1.2] - 2025-03-24

### Fixed

- **[iOS]** `QuillEditor` doesn't respect the system keyboard brightness by default [#2522](https://github.com/singerdmx/flutter-quill/pull/2522).
- Add a default empty list for `characterShortcutEvents` and `spaceShortcutEvents` in `QuillRawEditorConfig` [#2522](https://github.com/singerdmx/flutter-quill/pull/2522).
- Deprecate `QuillEditorState.configurations` in favor of `QuillEditorState.config` [#2522](https://github.com/singerdmx/flutter-quill/pull/2522).

## [11.1.1] - 2025-03-19

### Fixed

 - Explicitly schedule frame on secondary click to ensure context menu is shown on Windows [#2507](https://github.com/singerdmx/flutter-quill/pull/2507).

## [11.1.0] - 2025-03-11

### Fixed

- Remove unnecessary content change listeners in read-only mode to avoid triggering infinite loops of **FocusNode** callbacks [#2488](https://github.com/singerdmx/flutter-quill/pull/2488).
- Remove unicode from `QuillText` element that causes weird caret behavior on empty lines [#2453](https://github.com/singerdmx/flutter-quill/pull/2453).
- Focus and open context menu on right click if unfocused [#2477](https://github.com/singerdmx/flutter-quill/pull/2477).
- Update QuillController `length` extension method deprecation message [#2483](https://github.com/singerdmx/flutter-quill/pull/2483).

### Added

- `Rule` is now part of the public API, so that `Document.setCustomRules` can be used.
- `decoration` property in `DefaultTextBlockStyle` for the `header` attribute to customize headers with borders, background colors, and other styles using `BoxDecoration` [#2429](https://github.com/singerdmx/flutter-quill/pull/2429).

## [11.0.0] - 2025-02-16

> [!IMPORTANT]
> See the [migration guide from 10.0.0 to 11.0.0](https://github.com/singerdmx/flutter-quill/blob/master/doc/migration/10_to_11.md) for the full breaking changes and migration. Ensure to read the [breaking behavior](https://github.com/singerdmx/flutter-quill/blob/master/doc/migration/10_to_11.md#-breaking-behavior) section to avoid unexpected changes.

### Fixed

- **[iOS]** Localize the Cupertino link menu actions.
- Export `QuillToolbarSelectLineHeightStyleDropdownButtonOptions`, fixing [#2333](https://github.com/singerdmx/flutter-quill/issues/2333).
- Clipboard images pasting as plain text on **Android** [#2384](https://github.com/singerdmx/flutter-quill/pull/2384).
- Avoid using [`url_launcher_string.dart`](https://pub.dev/documentation/url_launcher/latest/url_launcher_string/url_launcher_string-library.html) which is [**strongly discouraged**](https://pub.dev/packages/url_launcher#urls-not-handled-by-uri) [#2403](https://github.com/singerdmx/flutter-quill/pull/2403).
- The color picker dialog's hex field does not use the correct value of the selected text in the editor [#2415](https://github.com/singerdmx/flutter-quill/pull/2415).

### Added

- New localization strings for the image save functionality [#2403](https://github.com/singerdmx/flutter-quill/pull/2403).
- `Insert video` string in `quill_en.arb` to support localization for `flutter_quill_extensions`. Currently available **only in English**.
- `QuillClipboardConfig` class with customizable clipboard paste handling callbacks, partial fix to [#2350](https://github.com/singerdmx/flutter-quill/issues/2350).
- The option to enable/disable rich text paste (from other apps) in `QuillClipboardConfig`.
- `Insert video` string in `quill_en.arb` to support localization for `flutter_quill_extensions`. Currently available **only in English**.
- `onKeyPressed` in `QuillEditorConfig` to customize key press handling in the editor [#2368](https://github.com/singerdmx/flutter-quill/pull/2368).
- Croatian (hr) language translation [#2431](https://github.com/singerdmx/flutter-quill/pull/2431).
- `enableClipboardPaste` flag in `QuillToolbarClipboardButton` to determine if the button defaults to `null,` which will use `ClipboardMonitor`, which checks every second if the clipboard has content to paste [#2427](https://github.com/singerdmx/flutter-quill/pull/2427).

### Changed

- Rewrite the image save functionality for [`flutter_quill_extensions`](https://pub.dev/packages/flutter_quill_extensions) [#2403](https://github.com/singerdmx/flutter-quill/pull/2403).
- Migrate [quill_native_bridge](https://pub.dev/packages/quill_native_bridge) to `11.0.0` [#2403](https://github.com/singerdmx/flutter-quill/pull/2403).
- Avoid using deprecated APIs in Flutter 3.27.0 [#2416](https://github.com/singerdmx/flutter-quill/pull/2416):
    - Migrate from `withOpacity` to `withValues` according to [Color wide gamut - Opacity migration](https://docs.flutter.dev/release/breaking-changes/wide-gamut-framework#opacity).
    - Avoid using the deprecated `Color.value` getter.
- Ignore `unreachable_switch_default` warning (introduced in Dart 3.6) [#2416](https://github.com/singerdmx/flutter-quill/pull/2416).
- Update `intl` dependency to support versions `0.19.0` and `0.20.0` [#2416](https://github.com/singerdmx/flutter-quill/pull/2416).
- Restore [base button options](https://github.com/singerdmx/flutter-quill/pull/2338/commits/1f51935f1eaa229f01c4d14398708ab2d3bd05b0), now works without the inherited widgets, and support buttons of `flutter_quill_extensions`.
- The option to enable/disable rich text paste (from other apps) in `QuillClipboardConfig`.
- Improve `README.md`.
- Simplify the `example` app.
- Update the minimum supported SDK version to **Flutter 3.0/Dart 3.0** for compatibility, fixing [#2347](https://github.com/singerdmx/flutter-quill/issues/2347).
- Improve dependencies constraints for compatibility.
- Improve `README.md`.
- [Always call `setState()` in `_markNeedsBuild()` in `QuillRawEditorState`](https://github.com/singerdmx/flutter-quill/pull/2338/commits/a127628214c23bb4a7a3b0cdc644fefb21eee738) (**revert to the old behavior**).
- **BREAKING**: Update configuration class names to use the suffix `Config` instead of `Configurations`.
- **BREAKING**: Refactor **embed block interface** for both the `EmbedBuilder.build()` and `EmbedButtonBuilder`.
- [Minor cleanup](https://github.com/singerdmx/flutter-quill/pull/2338/commits/b739b700cbae9c3d4427e4966963d97cebf0a852) to magnifier feature.
- The `QuillSimpleToolbar` base button options now support buttons of `flutter_quill_extensions`.
- Mark `shouldNotifyListeners` as experimental in `QuillController.replaceText()`.
- Mark the method `QuillController.clipboardSelection()` as experimental.
- Improve pub topics in package metadata.
- Update the minimum required version of the dependency [quill_native_bridge](https://pub.dev/packages/quill_native_bridge) from `10.7.9` to `10.7.11`.
- Address warnings of `unreachable_switch_default` (introduced in Dart 3.6).
- **BREAKING**: Clipboard action buttons in `QuillSimpleToolbar` are now disabled by default. To enable them, set `showClipboardCut`, `showClipboardCopy`, and `showClipboardPaste` to `true` in `QuillSimpleToolbarConfig`.
- **BREAKING**: Change the `options` parameter class type from `QuillToolbarToggleStyleButtonOptions` to `QuillToolbarClipboardButtonOptions` in `QuillToolbarClipboardButton`. To migrate, use `QuillToolbarClipboardButtonOptions` instead of `QuillToolbarToggleStyleButtonOptions` [#2433](https://github.com/singerdmx/flutter-quill/pull/2433). This change was made for the PR [#2427](https://github.com/singerdmx/flutter-quill/pull/2427).
- **BREAKING**: Change the `onTapDown` to accept `TapDownDetails` instead of `TapDragDownDetails` (revert [#2128](https://github.com/singerdmx/flutter-quill/pull/2128/files#diff-49ca9b0fdd0d380a06b34d5aed7674bbfb27fede500831b3e1279615a9edd06dL259-L261) due to regressions).
- **BREAKING**: Change the `onTapUp` to accept `TapUpDetails` instead of `TapDragUpDetails` (revert [#2128](https://github.com/singerdmx/flutter-quill/pull/2128/files#diff-49ca9b0fdd0d380a06b34d5aed7674bbfb27fede500831b3e1279615a9edd06dL263-L265) due to regressions).
- **BREAKING**: Revert [`Copy TapAndPanGestureRecognizer from TextField` PR #2128](https://github.com/singerdmx/flutter-quill/pull/2128), restoring editor behavior to match versions before [`10.4.0`](https://pub.dev/packages/flutter_quill/changelog#1040) due to the regressions [#2413](https://github.com/singerdmx/flutter-quill/pull/2413).
- **BREAKING**: Replace `QuillClipboardConfig.onDeltaPaste` with `QuillClipboardConfig.onRichTextPaste` which is more specific and provides an additional parameter `isExternal` to determine whether the `Delta` content is from an external app.
- Bosnian (bs), Macedonian (mk) and Gujarati (gu) language translations [#2455](https://github.com/singerdmx/flutter-quill/pull/2455).
- `textSpanBuilder` to `QuillEditorConfig` to allow overriding how text content is rendered.

### Removed

- **BREAKING**: The quill shared configuration class.
- The dependency [equatable](https://pub.dev/packages/equatable).
- The experimental support for spell checking. See [#2246](https://github.com/singerdmx/flutter-quill/issues/2246).
- **BREAKING**: The magnifier feature due to buggy behavior [#2413](https://github.com/singerdmx/flutter-quill/pull/2413). See [#2406](https://github.com/singerdmx/flutter-quill/issues/2406) for a list of reasons.

## [10.8.5] - 2024-10-24

### Fixed

- Allow all correct URLs to be formatted [#2328](https://github.com/singerdmx/flutter-quill/pull/2328).
- **[macOS]** Implement actions for `ExpandSelectionToDocumentBoundaryIntent` and `ExpandSelectionToLineBreakIntent` to use keyboard shortcuts, along with unrelated cleanup [#2279](https://github.com/singerdmx/flutter-quill/pull/2279).

## [9.4.0] - 2024-06-13

### Added

- Korean translations [#1911](https://github.com/singerdmx/flutter-quill/pull/1911).

### Changed

- Rework search bar/dialog for **Material 3** UI with on-the-fly search [#1904](https://github.com/singerdmx/flutter-quill/pull/1904).
- Support for subscript and superscript across all languages.
- Improve pasting of Markdown and HTML file content from the system clipboard [#1915](https://github.com/singerdmx/flutter-quill/pull/1915).

### Removed

- Apple-specific font dependency for subscript and superscript functionality from the example.
- **BREAKING**: The [`super_clipboard`](https://pub.dev/packages/super_clipboard) plugin, To restore legacy behavior for `super_clipboard`, use [`flutter_quill_extensions`](https://pub.dev/packages/flutter_quill_extensions) package and `FlutterQuillExtensions.useSuperClipboardPlugin()`.

[unreleased]: https://github.com/singerdmx/flutter-quill/compare/v11.5.0...HEAD
[11.5.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.5.0
[11.4.2]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.4.2
[11.4.1]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.4.1
[11.4.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.4.0
[11.3.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.3.0
[11.2.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.2.0
[11.1.2]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.1.2
[11.1.1]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.1.1
[11.1.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.1.0
[11.0.0]: https://github.com/singerdmx/flutter-quill/compare/v10.0.0...v11.0.0
[10.8.5]: https://github.com/singerdmx/flutter-quill/compare/v9.4.0...v10.8.5
[9.4.0]: https://github.com/singerdmx/flutter-quill/releases/tag/v9.4.0
