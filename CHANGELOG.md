# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](https://semver.org/).
This change log adheres to standards from [Keep a CHANGELOG](https://keepachangelog.com).

## Unreleased

### Added
* [`jsx-props-no-multi-spaces`]: improve autofix for multi-line ([#3930][] @justisb)

### Fixed
* [`no-unknown-property`]: allow `onLoad` on `body` ([#3923][] @DerekStapleton)

[#3930]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3930
[#3923]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3923

## [7.37.5] - 2025.04.03

### Fixed
* [`no-unknown-property`]: allow shadow root attrs on `<template>` ([#3912][] @ljharb)
* [`prop-types`]: support `ComponentPropsWithRef` from a namespace import ([#3651][] @corydeppen)
* [`jsx-no-constructed-context-values`]: detect constructed context values in React 19 `<Context>` usage ([#3910][] @TildaDares)
* [`no-unknown-property`]: allow `transform-origin` on `rect` ([#3914][] @ljharb)

### Changed
* [Docs] [`button-has-type`]: clean up phrasing ([#3909][] @hamirmahal)

[7.37.5]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.37.4...v7.37.5
[#3914]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3914
[#3912]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3912
[#3910]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3910
[#3909]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3909
[#3651]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3651

## [7.37.4] - 2025.01.12

### Fixed
* [`no-unknown-property`]: support `onBeforeToggle`, `popoverTarget`, `popoverTargetAction` attributes ([#3865][] @acusti)
* [types] fix types of flat configs ([#3874][] @ljharb)

[7.37.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.37.3...v7.37.4
[#3874]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3874
[#3865]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3865

## [7.37.3] - 2024.12.23

### Fixed
* [`no-danger`]: avoid a crash on a nested component name ([#3833][] @ljharb)
* [Fix] types: correct generated type declaration ([#3840][] @ocavue)
* [`no-unknown-property`]: support `precedence` prop in react 19 ([#3829][] @acusti)
* [`prop-types`]: props missing in validation when using generic types from a namespace import ([#3859][] @rbondoc96)

### Changed
* [Tests] [`jsx-no-script-url`]: Improve tests ([#3849][] @radu2147)
* [Docs] fix broken links: [`default-props-match-prop-types`], [`jsx-boolean-value`], [`jsx-curly-brace-presence`], [`jsx-no-bind`], [`no-array-index-key`], [`no-is-mounted`], [`no-render-return-value`], [`require-default-props`] ([#3841][] @bastiendmt)

[7.37.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.37.2...v7.37.3
[#3859]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3859
[#3849]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3849
[#3841]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3841
[#3840]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3840
[#3833]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3833
[#3829]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3829

## [7.37.2] - 2024.10.22

### Fixed
* [`destructuring-assignment`]: fix false negative when using `typeof props.a` ([#3835][] @golopot)

### Changed
* [Refactor] [`destructuring-assignment`]: use `getParentStatelessComponent` ([#3835][] @golopot)

[7.37.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.37.1...v7.37.2
[#3835]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3835

## [7.37.1] - 2024.10.01

### Fixed
* [meta] do not npmignore `d.ts` files ([#3836][] @ljharb)

### Changed
* [readme] Fix shared settings link ([#3834][] @MgenGlder)

[7.37.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.37.0...v7.37.1
[#3836]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3836
[#3834]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3834

## [7.37.0] - 2024.09.26

### Added
* add type generation ([#3830][] @voxpelli)
* [`no-unescaped-entities`]: add suggestions ([#3831][] @StyleShit)
* [`forbid-component-props`]: add `allowedForPatterns`/`disallowedForPatterns` options ([#3805][] @Efimenko)
* [`no-unstable-nested-components`]: add `propNamePattern` to support custom render prop naming conventions ([#3826][] @danreeves)

### Changed
* [readme] flat config example for react 17+ ([#3824][] @GabenGar)

[7.37.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.36.1...v7.37.0
[#3831]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3831
[#3830]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3830
[#3826]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3826
[#3824]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3824
[#3805]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3805

## [7.36.1] - 2024.09.12

### Fixed
* [`no-is-mounted`]: fix logic in method name check ([#3821][] @Mathias-S)
* [`jsx-no-literals`]: Avoid crashing on valueless boolean props ([#3823][] @reosarevok)

[7.36.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.36.0...v7.36.1
[#3823]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3823
[#3821]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3821

## [7.36.0] - 2024.09.12

### Added
* [`no-string-refs`]: allow this.refs in > 18.3.0 ([#3807][] @henryqdineen)
* [`jsx-no-literals`] Add `elementOverrides` option and the ability to ignore this rule on specific elements ([#3812][] @Pearce-Ropion)
* [`forward-ref-uses-ref`]: add rule for checking ref parameter is added ([#3667][] @NotWoods)

### Fixed
* [`function-component-definition`], [`boolean-prop-naming`], [`jsx-first-prop-new-line`], [`jsx-props-no-multi-spaces`], `propTypes`: use type args ([#3629][] @HenryBrown0)
* JSX pragma: fail gracefully ([#3632][] @ljharb)
* [`jsx-props-no-spreading`]: add `explicitSpread` option to schema ([#3799][] @ljharb)

### Changed
* [Tests] add @typescript-eslint/parser v6 ([#3629][] @HenryBrown0)
* [Tests] add @typescript-eslint/parser v7 and v8 ([#3629][] @hampustagerud)
* [Docs] [`no-danger`]: update broken link ([#3817][] @lucasrmendonca)
* [types] add jsdoc type annotations ([#3731][] @y-hsgw)
* [Tests] `button-has-type`: add test case with spread ([#3731][] @y-hsgw)

[7.36.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.35.2...v7.36.0
[#3799]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3799
[#3632]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3632
[#3812]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3812
[#3731]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3731
[#3694]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3667
[#3629]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3629
[#3817]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3817
[#3807]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3807

## [7.35.2] - 2024.09.03

### Fixed
* [`jsx-curly-brace-presence`]: avoid autofixing attributes with double quotes to a double quoted attribute ([#3814][] @ljharb)

[7.35.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.35.1...v7.35.2
[#3814]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3814

## [7.35.1] - 2024.09.02

### Fixed
* [`jsx-curly-brace-presence`]: do not trigger on strings containing a quote character ([#3798][] @akulsr0)

[7.35.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.35.0...v7.35.1
[#3798]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3798

## [7.35.0] - 2024.07.19

### Added
* support eslint v9 ([#3759][] @mdjermanovic)
* export flat configs from plugin root and fix flat config crash ([#3694][] @bradzacher @mdjermanovic)
* add [`jsx-props-no-spread-multi`] ([#3724][] @SimonSchick)
* [`forbid-component-props`]: add `propNamePattern` to allow / disallow prop name patterns ([#3774][] @akulsr0)
* [`jsx-handler-names`]: support ignoring component names ([#3772][] @akulsr0)
* version settings: Allow react defaultVersion to be configurable ([#3771][] @onlywei)
* [`jsx-closing-tag-location`]: add `line-aligned` option ([#3777] @kimtaejin3)
* [`no-danger`]: add `customComponentNames` option ([#3748][] @akulsr0)

### Fixed
* [`no-invalid-html-attribute`]: substitute placeholders in suggestion messages ([#3759][] @mdjermanovic)
* [`sort-prop-types`]: single line type ending without semicolon ([#3784][] @akulsr0)
* [`require-default-props`]: report when required props have default value ([#3785][] @akulsr0)

### Changed
* [Refactor] `variableUtil`: Avoid creating a single flat variable scope for each lookup ([#3782][] @DanielRosenwasser)

[7.35.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.34.4...v7.35.0
[#3785]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3785
[#3784]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3784
[#3782]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3782
[#3777]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3777
[#3774]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3774
[#3772]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3772
[#3771]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3771
[#3759]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3759
[#3748]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3748
[#3724]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3724
[#3694]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3694

## [7.34.4] - 2024.07.13

### Fixed

* [`prop-types`]: fix `className` missing in prop validation false negative ([#3749][] @akulsr0)
* [`sort-prop-types`]: Check for undefined before accessing `node.typeAnnotation.typeAnnotation` ([#3779][] @tylerlaprade)

[7.34.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.34.3...v7.34.4
[#3779]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3779
[#3749]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3749

## [7.34.3] - 2024.06.18

### Fixed
* [`prop-types`]: null-check rootNode before calling getScope ([#3762][] @crnhrv)
* [`boolean-prop-naming`]: avoid a crash with a spread prop ([#3733][] @ljharb)
* [`jsx-boolean-value`]: `assumeUndefinedIsFalse` with `never` must not allow explicit `true` value ([#3757][] @6uliver)
* [`no-object-type-as-default-prop`]: enable rule for components with many parameters ([#3768][] @JulienR1)
* [`jsx-key`]: incorrect behavior for checkKeyMustBeforeSpread with map callbacks ([#3769][] @akulsr0)

[7.34.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.34.2...v7.34.3
[#3769]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3769
[#3768]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3768
[#3762]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3762
[#3757]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3757
[#3733]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3733

## [7.34.2] - 2024.05.24

### Fixed
* [`boolean-prop-naming`]: avoid a crash with a non-TSTypeReference type ([#3718][] @developer-bandi)
* [`jsx-no-leaked-render`]: invalid report if left eside is boolean ([#3746][] @akulsr0)
* [`jsx-closing-bracket-location`]: message shows `{{details}}` when there are no details ([#3759][] @mdjermanovic)
* [`no-invalid-html-attribute`]: ensure error messages are correct ([#3759][] @mdjermanovic, @ljharb)

### Changed
 * [Refactor] create various eslint utils to fix eslint deprecations ([#3759][] @mdjermanovic, @ljharb)

[7.34.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.34.1...v7.34.2
[#3759]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3759
[#3746]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3746
[#3718]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3718

## [7.34.1] - 2024.03.15

### Fixed
* [`jsx-no-leaked-render`]: prevent wrongly adding parens ([#3700][] @developer-bandi)
* [`boolean-prop-naming`]: detect TS interfaces ([#3701][] @developer-bandi)
* [`boolean-prop-naming`]: literalType error fix ([#3704][] @developer-bandi)
* [`boolean-prop-naming`]: allow TSIntersectionType ([#3705][] @developer-bandi)
* [`no-unknown-property`]: support `popover`, `popovertarget`, `popovertargetaction` attributes ([#3707][] @ljharb)
* [`no-unknown-property`]: only match `data-*` attributes containing `-` ([#3713][] @silverwind)
* [`checked-requires-onchange-or-readonly`]: correct options that were behaving opposite ([#3715][] @jaesoekjjang)

### Changed
* [`boolean-prop-naming`]: improve error message (@ljharb)

[7.34.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.34.0...v7.34.1
[#3715]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3715
[#3713]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3713
[#3707]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3707
[#3705]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3705
[#3704]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3704
[#3701]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3701
[#3700]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3700

## [7.34.0] - 2024.03.03

### Added
* [`sort-prop-types`]: give errors on TS types ([#3615][] @akulsr0)
* [`no-invalid-html-attribute`]: add support for `apple-touch-startup-image` `rel` attributes in `link` tags ([#3638][] @thomashockaday)
* [`no-unknown-property`]: add requireDataLowercase option ([#3645][] @HermanBilous)
* [`no-unknown-property`]: add `displaystyle` on `<math>` ([#3652][] @lounsbrough)
* [`prefer-read-only-props`], [`prop-types`], component detection: allow components to be async functions ([#3654][] @pnodet)
* [`no-unknown-property`]: support `onResize` on audio/video tags ([#3662][] @caesar1030)
* [`jsx-wrap-multilines`]: add `never` option to prohibit wrapping parens on multiline JSX ([#3668][] @reedws)
* [`jsx-filename-extension`]: add `ignoreFilesWithoutCode` option to allow empty files ([#3674][] @burtek)
* [`jsx-boolean-value`]: add `assumeUndefinedIsFalse` option ([#3675][] @developer-bandi)
* `linkAttribute` setting, [`jsx-no-target-blank`]: support multiple properties ([#3673][] @burtek)
* [`jsx-no-script-url`]: add `includeFromSettings` option to support `linkAttributes` setting ([#3673][] @burtek)
* [`jsx-one-expression-per-line`]: add `non-jsx` option to allow non-JSX children in one line ([#3677][] @burtek)
* add [`checked-requires-onchange-or-readonly`] rule ([#3680][] @jaesoekjjang)

### Fixed
* [`jsx-no-leaked-render`]: preserve RHS parens for multiline jsx elements while fixing ([#3623][] @akulsr0)
* [`jsx-key`]: detect conditional returns ([#3630][] @yialo)
* [`jsx-newline`]: prevent a crash when `allowMultilines` ([#3633][] @ljharb)
* [`no-unknown-property`]: use a better regex to avoid a crash ([#3666][] @ljharb @SCH227)
* [`prop-types`]: handle nested forwardRef + memo ([#3679][] @developer-bandi)
* [`no-unknown-property`]: add `fetchPriority` ([#3697][] @SevereCloud)
* [`forbid-elements`]: prevent a crash on `createElement()` ([#3632][] @ljharb)

### Changed
* [`jsx-boolean-value`]: make error messages clearer ([#3691][] @developer-bandi)
* [Refactor] `propTypes`: extract type params to var ([#3634][] @HenryBrown0)
* [Refactor] [`boolean-prop-naming`]: invert if statement ([#3634][] @HenryBrown0)
* [Refactor] [`function-component-definition`]: exit early if no type params ([#3634][] @HenryBrown0)
* [Refactor] [`jsx-props-no-multi-spaces`]: extract type parameters to var ([#3634][] @HenryBrown0)
* [Docs] [`jsx-key`]: fix correct example ([#3656][] @developer-bandi)
* [Tests] `jsx-wrap-multilines`: passing tests ([#3545][] @burtek)
* [Docs] [`iframe-missing-sandbox`]: fix link to iframe attribute on mdn ([#3690][] @nnmrts)
* [Docs] [`hook-use-state`]: fix an undefined variable ([#3626][] @chentsulin)

[7.34.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.33.2...v7.34.0
[#3697]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3697
[#3691]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3691
[#3690]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3690
[#3680]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3680
[#3679]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3679
[#3677]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3677
[#3675]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3675
[#3674]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3674
[#3673]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3673
[#3668]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3668
[#3666]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3666
[#3662]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3662
[#3656]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3656
[#3654]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3654
[#3652]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3652
[#3645]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3645
[#3638]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3638
[#3634]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3634
[#3633]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3633
[#3632]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3632
[#3630]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3630
[#3626]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3626
[#3623]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3623
[#3615]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3615
[#3545]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3545

## [7.33.2] - 2023.08.15

### Fixed
* [`no-deprecated`]: prevent false positive on commonjs import ([#3614][] @akulsr0)
* [`no-unsafe`]: report on the method instead of the entire component (@ljharb)
* [`no-deprecated`]: report on the destructured property instead of the entire variable declarator (@ljharb)
* [`no-deprecated`]: report on the imported specifier instead of the entire import statement (@ljharb)
* [`no-invalid-html-attribute`]: report more granularly (@ljharb)

[7.33.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.33.1...v7.33.2
[#3614]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3614

## [7.33.1] - 2023.07.29

### Fixed
* [`require-default-props`]: fix config schema ([#3605][] @controversial)
* [`jsx-curly-brace-presence`]: Revert [#3538][] due to issues with intended string type casting usage ([#3611][] @taozhou-glean)
* [`sort-prop-types`]: ensure sort-prop-types respects noSortAlphabetically ([#3610][] @caesar1030)

[7.33.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.33.0...v7.33.1
[#3611]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3611
[#3610]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3610
[#3605]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3605

## [7.33.0] - 2023.07.19

### Added
* [`display-name`]: add `checkContextObjects` option ([#3529][] @JulesBlm)
* [`jsx-first-prop-new-line`]: add `multiprop` option ([#3533][] @haydncomley)
* [`no-deprecated`]: add React 18 deprecations ([#3548][] @sergei-startsev)
* [`forbid-component-props`]: add `disallowedFor` option ([#3417][] @jacketwpbb)

### Fixed
* [`no-array-index-key`]: consider flatMap ([#3530][] @k-yle)
* [`jsx-curly-brace-presence`]: handle single and only expression template literals ([#3538][] @taozhou-glean)
* [`no-unknown-property`]: allow `onLoad` on `source` (@ljharb)
* [`jsx-first-prop-new-line`]: ensure autofix preserves generics in component name ([#3546][] @ljharb)
* [`no-unknown-property`]: allow `fill` prop on `<symbol>` ([#3555][] @stefanprobst)
* [`display-name`], [`prop-types`]: when checking for a capitalized name, ignore underscores entirely ([#3560][] @ljharb)
* [`no-unused-state`]: avoid crashing on a class field function with destructured state ([#3568][] @ljharb)
* [`no-unused-prop-types`]: allow using spread with object expression in jsx ([#3570][] @akulsr0)
* Revert "[`destructuring-assignment`]: Handle destructuring of useContext in SFC" ([#3583][] [#2797][] @102)
* [`prefer-read-only-props`]: add TS support ([#3593][] @HenryBrown0)

### Changed
* [Docs] [`jsx-newline`], [`no-unsafe`], [`static-property-placement`]: Fix code syntax highlighting ([#3563][] @nbsp1221)
* [readme] resore configuration URL ([#3582][] @gokaygurcan)
* [Docs] [`jsx-no-bind`]: reword performance rationale ([#3581][] @gpoole)
- [Docs] [`jsx-first-prop-new-line`]: add missing `multiprop` value ([#3598][] @dzek69)

[7.33.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.32.2...v7.33.0
[#3598]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3598
[#3593]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3593
[#3583]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3583
[#3582]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3582
[#3581]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3581
[#3570]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3570
[#3568]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3568
[#3563]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3563
[#3560]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3560
[#3555]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3555
[#3548]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3548
[#3546]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3546
[#3538]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3538
[#3533]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3533
[#3530]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3530
[#3529]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3529
[#3417]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3417

## [7.32.2] - 2023.01.28

### Fixed
* configs: restore `parserOptions` in legacy configs ([#3523][] @ljharb)
* [`jsx-no-constructed-context-values`], [`jsx-no-useless-fragment`]: add a rule schema (@ljharb)
( [`no-unknown-property`]: add `fill` for `<marker>` ([#3525][] @alexey-koran)

[7.32.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.32.1...v7.32.2
[#3525]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3525
[#3520]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3523

## [7.32.1] - 2023.01.16

### Fixed
* prevent circular dependency in index and "all" config ([#3519][] @ljharb)
* [`destructuring-assignment`]: do not force destructuring of optionally chained properties ([#3520][] @ljharb)

[7.32.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.32.0...v7.32.1
[#3520]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3520
[#3519]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3519

## [7.32.0] - 2023.01.10

### Added
* support new config system ([#3429][] @jjangga0214)
* [`hook-use-state`]: add `allowDestructuredState` option ([#3449][] @ljharb)
* add [`sort-default-props`] and deprecate [`jsx-sort-default-props`] ([#1861][] @alexzherdev)
* add [`no-object-type-as-default-prop`] rule ([#2848][] @cyan33 @fengkx)

### Fixed
* configs: avoid legacy config system error ([#3461][] @ljharb)
* [`sort-prop-types`]: restore autofixing ([#3452][], [#3471][] @ROSSROSALES)
* [`no-unknown-property`]: do not check `fbs` elements ([#3494][] @brianogilvie)
* [`jsx-newline`]: No newline between comments and jsx elements ([#3493][] @justmejulian)
* [`jsx-no-leaked-render`]: Don't report errors on empty strings if React >= v18 ([#3488][] @himanshu007-creator)
* [`no-invalid-html-attribute`]: convert autofix to suggestion ([#3474][] @himanshu007-creator @ljharb)
* [`jsx-no-leaked-render`]: fix removing parentheses for conditionals ([#3502][] @akulsr0)
* [`jsx-no-leaked-render`]: invalid fixes in coerce mode ([#3511][] @akulsr0)
* [`destructuring-assignment`]: Handle destructuring of useContext in SFC ([#2797][] @Zinyon @ljharb)

### Changed
* [Docs] [`jsx-no-leaked-render`]: Remove mentions of empty strings for React 18 ([#3468][] @karlhorky)
* [Docs] update `eslint-doc-generator` to v1.0.0 ([#3499][] @bmish)
* [meta] add issue template ([#3483][] @ROSSROSALES)
* [Docs] Use emoji for jsx-runtime config and config file for eslint-doc-generator ([#3504][] @bmish)
* [Docs] [`prefer-exact-props`]: fix example flow syntax ([#3510][] @smackfu)
* [Perf] use `anyOf` instead of `oneOf` (@ljharb @remcohaszing)

[7.32.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.11...v7.32.0
[#3511]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3511
[#3510]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3510
[#3504]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3504
[#3502]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3502
[#3499]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3499
[#3494]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3494
[#3493]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3493
[#3488]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3488
[#3483]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3483
[#3474]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3474
[#3471]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3471
[#3468]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3468
[#3461]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3461
[#3452]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3452
[#3449]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3449
[#3429]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3429
[#2848]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2848
[#2797]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2797
[#1861]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1861

## [7.31.11] - 2022.11.17

### Fixed
* [`jsx-no-target-blank`]: allow ternaries with literals ([#3464][] @akulsr0)
* [`no-unknown-property`]: add `inert` attribute ([#3484][] @ljharb)
* [`jsx-key`]: detect keys in logical expression and conditional expression ([#3490][] @metreniuk)

### Changed
* [Perf] component detection: improve performance by avoiding traversing parents unnecessarily ([#3459][] @golopot)
* [Docs] `forbid-component-props`: inclusive language w/ allowlist ([#3473][] @AndersDJohnson)
* [Docs] automate doc generation with `eslint-doc-generator` ([#3469][] @bmish)

[7.31.11]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.10...v7.31.11
[#3490]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3490
[#3484]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3484
[#3473]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3473
[#3469]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3469
[#3464]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3464
[#3459]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3459

## [7.31.10] - 2022.10.10

### Fixed
* [`no-unknown-property`]: allow `allowFullScreen` on `iframe` ([#3455][] @almeidx)

[7.31.10]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.9...v7.31.10
[#3455]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3455

## [7.31.9] - 2022.10.09

### Fixed
* [`no-unknown-property`]: add `dialog` attributes ([#3436][] @ljharb)
* [`no-arrow-function-lifecycle`]: when converting from an arrow, remove the semi and wrapping parens ([#3337][] @ljharb)
* [`jsx-key`]: Ignore elements inside `React.Children.toArray()` ([#1591][] @silvenon)
* [`jsx-no-constructed-context-values`]: fix false positive for usage in non-components ([#3448][] @golopot)
* [`static-property-placement`]: warn on nonstatic expected-statics ([#2581][] @ljharb)
* [`no-unknown-property`]: properly tag-restrict case-insensitive attributes (@ljharb)
* [`no-unknown-property`]: allow `webkitDirectory` on `input`, case-insensitive ([#3454][] @ljharb)

### Changed
* [Docs] [`no-unknown-property`]: fix typo in link ([#3445][] @denkristoffer)
* [Perf] component detection: improve performance by optimizing getId ([#3451][] @golopot)
* [Docs] [`no-unstable-nested-components`]: Warn about memoized, nested components ([#3444][] @eps1lon)

[7.31.9]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.8...v7.31.9
[#3454]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3454
[#3451]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3451
[#3448]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3448
[#3445]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3445
[#3444]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3444
[#3436]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3436
[#3337]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3337
[#2581]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2581
[#1591]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1591

## [7.31.8] - 2022.09.08

### Fixed
* [`no-unknown-property`]: add `viewBox` on `marker` ([#3416][] @ljharb)
* [`no-unknown-property`]: add `noModule` on `script` ([#3414][] @ljharb)
* [`no-unknown-property`]: allow `onLoad` on `<object>` ([#3415][] @OleksiiKachan)
* [`no-multi-comp`]: do not detect a function property returning only null as a component ([#3412][] @ljharb)
* [`no-unknown-property`]: allow `abbr` on `<th>` and `<td>` ([#3419][] @OleksiiKachan)
* [`no-unknown-property`]: add `viewBox` for `pattern`, `symbol`, `view` ([#3424][] @MNBuyskih)
* [`no-unknown-property`]: add `align` on all the tags that support it ([#3425][] @ljharb)

### Changed

* [meta] npmignore markdownlint config ([#3413][] @jorrit)

[7.31.8]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.7...v7.31.8
[#3425]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3425
[#3424]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3424
[#3419]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3419
[#3416]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3416
[#3415]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3415
[#3414]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3414
[#3413]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3413
[#3412]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3412

## [7.31.7] - 2022.09.05

### Fixed
* [`no-unknown-property`]: avoid warning on `fbt` nodes entirely ([#3391][] @ljharb)
* [`no-unknown-property`]: add `download` property support for `a` and `area` ([#3394][] @HJain13)
* [`no-unknown-property`]: allow `webkitAllowFullScreen` and `mozAllowFullScreen` ([#3396][] @ljharb)
* [`no-unknown-property`]: `controlsList`, not `controlList` ([#3397][] @ljharb)
* [`no-unknown-property`]: add more capture event properties ([#3402][] @sjarva)
* [`no-unknown-property`]: Add more one word properties found in DefinitelyTyped's react/index.d.ts ([#3402][] @sjarva)
* [`no-unknown-property`]: Mark onLoad/onError as supported on iframes ([#3398][] @maiis, [#3406][] @akx)
* [`no-unknown-property`]: allow `imageSrcSet` and `imageSizes` attributes on `<link>` ([#3407][] @terrymun)
* [`no-unknown-property`]: add `border`; `focusable` on `<svg>` ([#3404][] [#3404][] @ljharb)
* [`no-unknown-property`]: React lowercases `data-` attrs ([#3395][] @ljharb)
* [`no-unknown-property`]: add `valign` on table components ([#3389][] @ljharb)

[7.31.7]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.6...v7.31.7
[#3407]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3407
[#3406]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3406
[#3405]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3405
[#3404]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3404
[#3402]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3402
[#3398]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3398
[#3397]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3397
[#3396]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3396
[#3395]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3395
[#3394]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3394
[#3391]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3391
[#3389]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3389

## [7.31.6] - 2022.09.04

### Fixed
* [`no-unknown-property`]: `onError` and `onLoad` both work on `img` and `script` ([#3388][] @ljharb)
* [`no-unknown-property`]: data-* attributes can have numbers ([#3390][] @sjarva)
* [`no-unknown-property`]: add more audio/video attributes ([#3390][] @sjarva)
* [`no-unknown-property`]: move allowfullscreen to case ignored attributes ([#3390][] @sjarva)
* [`no-unknown-property`]: fill works on line, mask, and use elements ([#3390][] @sjarva)
* [`no-unknown-property`]: add onMouseMoveCapture as valid react-specific attribute ([#3390][] @sjarva)
* [`no-unknown-property`]: make onLoad and onError be accepted on more elements ([#3390][] @sjarva)

### Changed

* [Docs] [`no-unknown-property`]: add a mention about using ignores properties with libraries that add props ([#3390][] @sjarva)

[7.31.6]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.5...v7.31.6
[#3390]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3390
[#3388]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3388

## [7.31.5] - 2022.09.03

### Fixed
* [`no-unknown-property`]: add properties `onToggle`, `fill`, `as`, and pointer events ([#3385][] @sjarva)
* [`no-unknown-property`]: add `defaultChecked` property ([#3385][] @sjarva)
* [`no-unknown-property`]: add touch and media event related properties ([#3385][] @sjarva)
* [`no-unknown-property`]: `children` is always an acceptable prop; iframes have `scrolling`; video has `playsInline` ([#3385][] @ljharb)

[7.31.5]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.4...v7.31.5
[#3385]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3385

## [7.31.4] - 2022.09.03

### Fixed
* [`no-unknown-property`]: support `checked` on inputs ([#3383][] @ljharb)

[#3383]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3383

[7.31.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.3...v7.31.4

## [7.31.3] - 2022.09.02

### Fixed
* [`no-unknown-property`]: add SVG and meta properties ([#3381][] @AhmadMayo)

[7.31.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.2...v7.31.3
[#3381]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3381

## [7.31.2] - 2022.09.02

### Fixed
* [`jsx-key`]: avoid a crash with optional chaining ([#3371][] @ljharb)
* [`jsx-sort-props`]: avoid a crash with spread props ([#3376][] @ljharb)
* [`no-unknown-property`]: properly recognize valid data- and aria- attributes ([#3377][] @sjarva)
* [`no-unknown-property`]: properly recognize unknown HTML/DOM attributes ([#3377][] @sjarva)

### Changed
* [Docs] [`jsx-sort-props`]: replace ref string with ref variable ([#3375][] @Luccasoli)
* [Refactor] [`no-unknown-property`]: improve jsdoc; extract logic to separate functions ([#3377][] @sjarva)
* [Refactor] [`no-unknown-property`]: update DOM properties to include also one word properties ([#3377][] @sjarva)

[7.31.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.1...v7.31.2
[#3377]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3377
[#3376]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3376
[#3375]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3375
[#3371]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3371

## [7.31.1] - 2022.08.26

### Fixed
* [`jsx-key`]: fix detecting missing key in `Array.from`'s mapping function ([#3369][] @sjarva)
* [`jsx-no-leaked-render`]: coerce strategy now allows a ternary ([#3370][] @sjarva)

[7.31.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.31.0...v7.31.1
[#3370]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3370
[#3369]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3369

## [7.31.0] - 2022.08.24

### Added
* [`jsx-newline`]: add `allowMultiline` option when prevent option is true ([#3311][] @TildaDares)
* [`forbid-dom-props`]: add `disallowedFor` option ([#3338][] @TildaDares)

### Fixed
* [`jsx-no-literals`]: properly error on children with noAttributeStrings: true ([#3317][] @TildaDares)
* [`jsx-key`]: catch key errors inside conditional statements ([#3320][] @TildaDares)
* [`display-name`]: Accept forwardRef and Memo nesting in newer React versions ([#3321][] @TildaDares)
* [`jsx-key`]: avoid a crash from optional chaining from [#3320][] ([#3327][] @ljharb)
* [`jsx-key`]: avoid a crash on a non-array node.body from [#3320][] ([#3328][] @ljharb)
* [`display-name`]: fix false positive for assignment of function returning null ([#3331][] @apbarrero)
* [`display-name`]: fix identifying `_` as a capital letter ([#3335][] @apbarrero)
* [`require-default-props`]: avoid a crash when function has no props param ([#3350][] @noahnu)
* [`display-name`], component detection: fix HOF returning null as Components ([#3347][] @jxm-math)
* [`forbid-prop-types`]: Ignore objects that are not of type React.PropTypes ([#3326][] @TildaDares)
* [`display-name`], component detection: fix false positive for HOF returning only nulls and literals ([#3305][] @golopot)
* [`jsx-no-target-blank`]: False negative when rel attribute is assigned using ConditionalExpression ([#3332][] @V2dha)
* [`jsx-no-leaked-render`]: autofix nested "&&" logical expressions ([#3353][] @hduprat)
* [`jsx-sort-props`]: sorted attributes now respect comments ([#3358][] @ROSSROSALES)

### Changed
* [Refactor] [`jsx-indent-props`]: improved readability of the checkNodesIndent function ([#3315][] @caroline223)
* [Tests] [`jsx-indent`], [`jsx-one-expression-per-line`]: add passing test cases ([#3314][] @ROSSROSALES)
* [Refactor] `boolean-prop-naming`, `jsx-indent`: avoid assigning to arguments ([#3316][] @caroline223)
* [Docs] [`sort-comp`]: add class component examples ([#3339][] @maurer2)
* [Docs] [`jsx-no-useless-fragment`]: add more examples of correct code ([#3349][] @karlhorky)
* [Docs] [`jsx-boolean-value`]: add jsdoc types for helper functions ([#3344][] @caroline223)
* [readme] remove dead codeclimate badge, add actions badge (@ljharb)
* [readme] Remove dead david-dm badge ([#3262][] @ddzz)
* [Refactor] [`jsx-closing-bracket-location`], [`jsx-no-bind`]: fix eslint issues ([#3351][] @caroline223)
* [Tests] [`function-component-definition`]: add passing test cases ([#3355][] @TildaDares)
* [Docs] [`jsx-no-target-blank`]: Fix link to link-type-noreferrer ([#3319][] @Luccasoli)
* [Docs] document which rules provide suggestions ([#3359][], [#3365][] @bmish)
* [Docs] Consistent rule descriptions and doc sections ([#3361][] @bmish)
* [Docs] Standardize deprecated rule notice ([#3364][] @bmish)
* [Docs] Fix typos ([#3366][] @bmish)
* [Docs] Add markdownlint for documentation formatting consistency ([#3367][] @bmish)
* [Docs] Add config notice to rule docs ([#3362][] @bmish)

[7.31.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.30.1...v7.31.0
[#3367]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3367
[#3366]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3366
[#3365]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3365
[#3364]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3364
[#3362]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3362
[#3361]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3361
[#3359]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3359
[#3358]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3358
[#3355]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3355
[#3353]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3353
[#3351]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3351
[#3350]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3350
[#3349]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3349
[#3347]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3347
[#3344]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3344
[#3339]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3339
[#3338]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3338
[#3335]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3335
[#3332]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3332
[#3331]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3331
[#3328]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3328
[#3327]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3327
[#3326]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3326
[#3321]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3321
[#3320]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3320
[#3319]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3319
[#3317]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3317
[#3316]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3316
[#3315]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3315
[#3314]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3314
[#3311]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3311
[#3305]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3305
[#3262]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3262

## [7.30.1] - 2022.06.23

### Fixed
* [`display-name`]: fix false positive for HOF returning only nulls ([#3291][] @golopot)
* [`jsx-no-leaked-render`]: avoid unnecessary negation operators and ternary branches deletion ([#3299][] @Belco90)
* [`display-name`]: fix false positive when using memo ([#3304][] @golopot)

### Changed
* [Docs] [`jsx-tag-spacing`]: rename option from [#3264][] ([#3294[] @ljharb)
* [Docs] [`jsx-key`]: split the examples ([#3293][] @ioggstream)

[7.30.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.30.0...v7.30.1
[#3304]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3304
[#3299]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3299
[#3294]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3294
[#3293]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3293
[#3291]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3291

## [7.30.0] - 2022.05.18

### Added
* [`destructuring-assignment`]: add option `destructureInSignature` ([#3235][] @golopot)
* [`no-unknown-property`]: Allow crossOrigin on image tag (SVG) ([#3251][] @zpao)
* [`jsx-tag-spacing`]: Add `multiline-always` option ([#3260][], [#3264][] @Nokel81)
* [`function-component-definition`]: replace `var` by `const` in certain situations ([#3248][] @JohnBerd @SimeonC)
* add [`jsx-no-leaked-render`] ([#3203][] @Belco90)
* [`require-default-props`]: add option `functions` ([#3249][] @nix6839)
* [`jsx-newline`]: Add `allowMultilines` option ([#3311][] @TildaDares)

### Fixed
* [`hook-use-state`]: Allow UPPERCASE setState setter prefixes ([#3244][] @duncanbeevers)
* `propTypes`: add `VFC` to react generic type param map ([#3230][] @dlech)
* [`no-unused-state`]: avoid a crash ([#3258][] @WillyLiaoWH @ljharb)
* [`jsx-no-useless-fragment`]: use proper apostrophe in error message ([#3266][] @develohpanda)
* `propTypes`: handle imported types/interface in forwardRef generic ([#3280][] @vedadeepta)
* [`button-has-type`]: fix exception for `<button type>` ([#3255][] @meowtec)
* [`no-unstable-nested-components`]: Improve error message and catch React.memo() ([#3247][] @zacharyliu)

### Changed
* [readme] remove global usage and eslint version from readme ([#3254][] @aladdin-add)
* [Refactor] fix linter errors ([#3261][] @golopot)
* [Docs] [`no-unused-prop-types`]: fix syntax errors ([#3259][] @mrdulin)
* [Refactor] improve performance for detecting function components ([#3265][] @golopot)
* [Refactor] improve performance for detecting class components ([#3267][] @golopot)
* [Refactor] [`no-deprecated`]: improve performance ([#3271][] @golopot)
* [Refactor] [`no-did-mount-set-state`], [`no-did-update-set-state`], [`no-will-update-set-state`]: improve performance ([#3272][] @golopot)
* [Refactor] improve performance by avoiding unnecessary `Components.detect` ([#3273][] @golopot)
* [Refactor] add `isParenthesized` AST util ([#3203][] @Belco90)
* [Docs] `default-props-match-prop-types`, `require-default-props`, `sort-prop-types`: fix typos ([#3279][] @nix6839)
* [Refactor] improve performance of rule merging ([#3281][] @golopot)
* [Refactor] improve performance of component detection ([#3276][] @golopot)

[7.30.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.29.4...v7.30.0
[#3281]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3281
[#3280]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3280
[#3279]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3279
[#3276]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3276
[#3273]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3273
[#3272]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3272
[#3271]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3271
[#3267]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3267
[#3266]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3266
[#3265]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3265
[#3264]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3264
[#3261]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3261
[#3260]: https://github.jsx-eslintckcr/eslint-plugin-react/pull/3260
[#3259]: https://githubjsx-eslintickcr/eslint-plugin-react/pull/3259
[#3258]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3258
[#3255]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3255
[#3254]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3254
[#3251]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3251
[#3249]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3249
[#3248]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3248
[#3247]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3247
[#3244]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3244
[#3235]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3235
[#3230]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3230
[#3203]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3203

## [7.29.4] - 2022.03.13

### Fixed
* [`no-unused-state`]: avoid a crash on a class field gDSFP ([#3236][] @ljharb)
* [`boolean-prop-naming`]: handle React.FC, intersection, union types ([#3241][] @ljharb)

[7.29.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.29.3...v7.29.4
[#3241]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3241
[#3236]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3236

## [7.29.3] - 2022.03.03

### Fixed
* [`no-unused-state`]: avoid a crash on type-only gDSFP declarations ([#3225][] @ljharb)
* [`jsx-curly-brace-presence`]: the string "never" defaults to `propElementValues` as `ignore` ([#3228][] @ljharb)
* `propTypes`: add `VFC` to react generic list ([#3230][] @ljharb)

[7.29.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.29.2...v7.29.3
[#3230]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3230
[#3228]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3228
[#3225]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3225

## [7.29.2] - 2022.02.25

### Fixed
* [`jsx-curly-brace-presence`]: avoid warning on curlies containing quote characters ([#3214][] @ljharb)
* [`jsx-indent`]: do not report on non-jsx-returning ternaries that contain null ([#3222][] @ljharb)
* [`jsx-indent`]: properly report on returned ternaries with jsx ([#3222][] @ljharb)
* [`no-array-index-key`]: detect named-imported `cloneElement`/`createElement` ([#3213][] @ljharb)

[7.29.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.29.1...v7.29.2
[#3222]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3222
[#3214]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3214
[#3213]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3213

## [7.29.1] - 2022.02.25

### Fixed
* [`jsx-key`]: prevent false "missing array key" warning ([#3215][] @ljharb)
* [`jsx-indent`]: avoid checking returns sans jsx ([#3218][] @ljharb)
* [`jsx-key`]: avoid a crash ([#3220][] @ljharb)
* version settings: avoid a crash with an invalid version ([#3219][] @ljharb)

[7.29.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.29.0...v7.29.1
[#3220]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3220
[#3219]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3219
[#3218]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3218
[#3215]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3215

## [7.29.0] - 2022.02.24

### Added
* add [`hook-use-state`] rule to enforce symmetric useState hook variable names ([#2921][] @duncanbeevers)
* [`jsx-no-target-blank`]: Improve fixer with option `allowReferrer` ([#3167][] @apepper)
* [`jsx-curly-brace-presence`]: add "propElementValues" config option ([#3191][] @ljharb)
* add [`iframe-missing-sandbox`] rule ([#2753][] @tosmolka @ljharb)
* [`no-did-mount-set-state`], [`no-did-update-set-state`]: no-op with react >= 16.3 ([#1754][] @ljharb)
* [`jsx-sort-props`]: support multiline prop groups ([#3198][] @duhamelgm)
* [`jsx-key`]: add `warnDuplicates` option to warn on duplicate jsx keys in an array ([#2614][] @ljharb)
* [`jsx-sort-props`]: add `locale` option ([#3002][] @ljharb)

### Fixed
* [`prop-types`], `propTypes`: add support for exported type inference ([#3163][] @vedadeepta)
* [`no-invalid-html-attribute`]: allow 'shortcut icon' on `link` ([#3174][] @Primajin)
* [`prefer-exact-props`] improve performance for `Identifier` visitor ([#3190][] @meowtec)
* `propTypes`: Handle TSTypeReference in no-unused-prop-type ([#3195][] @niik)
* [`sort-prop-types`]: avoid repeated warnings of the same node/reason ([#519][] @ljharb)
* [`jsx-indent`]: Fix indent handling for closing parentheses ([#620][] @stefanbuck])
* [`prop-types`]/`propTypes`: follow a returned identifier to see if it is JSX ([#1046][] @ljharb)
* [`no-unused-state`]: TS: support `getDerivedStateFromProps` as an arrow function ([#2061][] @ljharb)
* [`no-array-index-key`]: catch `.toString` and `String()` usage ([#2813][] @RedTn)
* [`function-component-definition`]: do not break on dollar signs ([#3207][] @ljharb)
* [`prefer-stateless-function`]: avoid a crash inside `doctrine` ([#2596][] @ljharb)
* [`prop-types`]: catch infinite loop ([#2861][] @ljharb)
* [`forbid-prop-types`]: properly report name in error message; check undestructured arguments ([#2945][] @ljharb)

### Changed
* [readme] change [`jsx-runtime`] link from branch to sha ([#3160][] @tatsushitoji)
* [Docs] HTTP => HTTPS ([#3133][] @Schweinepriester)
* [readme] Some grammar fixes ([#3186][] @JJ)
* [Docs] [`jsx-no-target-blank`]: Improve readme ([#3169][] @apepper)
* [Docs] [`display-name`]: improve examples ([#3189][] @golopot)
* [Refactor] [`no-invalid-html-attribute`]: sort HTML_ELEMENTS and messages ([#3182][] @Primajin)
* [Docs] [`forbid-foreign-prop-types`]: document `allowInPropTypes` option ([#1815][] @ljharb)
* [Refactor] [`jsx-sort-default-props`]: remove unnecessary code ([#1817][] @ljharb)
* [Docs] [`jsx-no-target-blank`]: fix syntax highlighting ([#3199][] @shamrin)
* [Docs] [`jsx-key`]: improve example ([#3202][] @chnakamura)
* [Refactor] [`jsx-key`]: use more AST selectors (@ljharb)

[7.29.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.28.0...v7.29.0
[#3207]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3207
[#3202]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3202
[#3199]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3199
[#3198]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3198
[#3195]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3195
[#3191]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3191
[#3190]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3190
[#3189]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3189
[#3186]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3186
[#3182]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3182
[#3174]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3174
[#3169]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3169
[#3167]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3167
[#3163]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3163
[#3160]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3160
[#3133]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3133
[#3002]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3002
[#2945]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2945
[#2921]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2921
[#2861]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2861
[#2813]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2813
[#2753]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2753
[#2614]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2614
[#2596]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2596
[#2061]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2061
[#1817]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1817
[#1815]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1815
[#1754]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1754
[#1046]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1046
[#620]: https://github.com/jsx-eslint/eslint-plugin-react/pull/620
[#519]: https://github.com/jsx-eslint/eslint-plugin-react/issues/519

## [7.28.0] - 2021.12.22

### Added
* [`function-component-definition`]: support namedComponents option being an array ([#3129][] @petersendidit)

### Fixed
* [`jsx-indent-props`]: Reset `line.isUsingOperator` correctly after ternary ([#3146][] @tobiaswaltl)

### Changed
* [Refactor] [`no-arrow-function-lifecycle`], [`no-unused-class-component-methods`]: use report/messages convention (@ljharb)
* [Tests] component detection: Add testing scaffolding ([#3149][] @duncanbeevers)
* [New] component detection: track React imports ([#3149][] @duncanbeevers)
* [New] component detection: add `util.isReactHookCall` ([#3156][] @duncanbeevers)

[7.28.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.27.1...v7.28.0
[#3156]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3156
[#3149]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3149
[#3146]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3146
[#3129]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3129

## [7.27.1] - 2021.11.18

### Fixed
* [`no-invalid-html-attribute`]: allow `link` `rel` to have `apple-touch-icon`, `mask-icon` ([#3132][] @ljharb)
* [`no-unused-class-component-methods`]: add `getChildContext` lifecycle method ([#3136][] @yoyo837)
* [`prop-types`]: fix false positives on renames in object destructuring ([#3142][] @golopot)
* [`no-arrow-function-lifecycle`]: fix invalid autofix from a concise arrow method to a regular one ([#3145][] @ljharb)
* [`display-name`]: avoid false positives on non-creatClass object expressions ([#3144] @ljharb)

### Changed
* [readme] fix syntax typo ([#3141][] @moselhy)

[7.27.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.27.0...v7.27.1
[#3145]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3145
[#3144]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3144
[#3142]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3142
[#3141]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3141
[#3136]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3136
[#3132]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3132

## [7.27.0] - 2021.11.09

### Added
* support eslint 8.x ([#3059][] @MichaelDeBoey @ljharb)
* [`no-unused-class-component-methods`]: Handle unused class component methods ([#2166][] @jakeleventhal @pawelnvk)
* add [`no-arrow-function-lifecycle`] ([#1980][] @ngtan)
* add support for `@typescript-eslint/parser` v5 (@ljharb)
* [`no-invalid-html-attribute`]: add rule ([#2863][] @Nokel81)

### Fixed
* `propTypes`: add `VoidFunctionComponent` to react generic list ([#3092][] @vedadeepta)
* [`jsx-fragments`], [`jsx-no-useless-fragment`]: avoid a crash on fragment syntax in `typescript-eslint` parser (@ljharb)
* [`jsx-props-no-multi-spaces`]: avoid a crash on long member chains in tag names in `typescript-eslint` parser (@ljharb)
* [`no-unused-prop-types`], `usedPropTypes`: avoid crash with typescript-eslint parser (@ljharb)
* [`display-name`]: unwrap TS `as` expressions ([#3110][] @ljharb)
* [`destructuring-assignment`]: detect refs nested in functions ([#3102] @ljharb)
* [`no-unstable-components`]: improve handling of objects containing render function properties ([#3111] @fizwidget)
* [`prop-types`], `propTypes`: add forwardRef<>, ForwardRefRenderFunction<> prop-types ([#3112] @vedadeepta)
* [`no-typos`]: prevent a crash when using private methods (@ljharb)
* [`destructuring-assignment`], component detection: improve component detection ([#3122] @vedadeepta)
* [`no-invalid-html-attribute`]: avoid crash on spread props ([#3126] @ljharb)

### Changed
* [Tests] test on the new babel eslint parser ([#3113] @ljharb)
* [Docs] [`jsx-no-target-blank`]: adjust options description ([#3124] @gebsh)

[7.27.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.26.1...v7.27.0
[#3126]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3126
[#3124]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3124
[#3122]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3122
[#3113]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3113
[#3112]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3112
[#3111]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3111
[#3110]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3110
[#3102]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3102
[#3092]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3092
[#3059]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3059
[#2863]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2863
[#2166]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2166
[#1980]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1980

## [7.26.1] - 2021.09.29

### Fixed
* [`no-namespace`]: fix crash on non-string React.createElement name ([#3082] @ljharb)
* [`no-namespace`]: avoid crash on non-string createElement values ([#3085] @ljharb)
* [`jsx-no-target-blank`]: improve error messages ([#3088] @cutiful)

### Changed
* [Docs] [`jsx-max-props-per-line`]: fix options example ([#3083] @MrRaiter)

[7.26.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.26.0...v7.26.1
[#3088]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3088
[#3085]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3085
[#3083]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3083
[#3082]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3082

## [7.26.0] - 2021.09.20

### Added
* add [`no-namespace`] rule ([#2640] @yacinehmito @ljharb)
* [`jsx-max-props-per-line`]: add `single` and `multi` options ([#3078] @SIL0RAK)

### Fixed
* [`display-name`]: Get rid of false position on component detection ([#2759] @iiison)

### Changed
* [`no-access-state-in-setstate`]: passing test for “don't error if it's not a React Component” ([#1873] @kentcdodds)

[7.26.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.25.3...v7.26.0
[#3078]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3078
[#2640]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2640
[#2759]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2759
[#1873]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1873

## [7.25.3] - 2021.09.19

### Fixed
* [`prop-types`], `propTypes`: bail out unknown generic types inside func params ([#3076] @vedadeepta)

### Changed
* [readme] Update broken link for configuration files ([#3071] @prateek3255)
* [Refactor] create/extract `isCreateElement` and `isDestructuredFromPragmaImport` utils (@ljharb)

[7.25.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.25.2...v7.25.3
[#3076]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3076
[#3071]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3071

## [7.25.2] - 2021.09.16

### Fixed
* [`jsx-no-useless-fragments`]: Handle insignificant whitespace correctly when `allowExpressions` is `true` ([#3061][] @benj-dobs)
* [`prop-types`], `propTypes`: handle implicit `children` prop in react's generic types ([#3064][] @vedadeepta)
* [`display-name`]: fix arrow function returning result of function call with JSX arguments being interpreted as component ([#3065][] @danielfinke)
* [`jsx-no-target-blank`]: avoid crash on attr-only href ([#3066][] @ljharb @gaz77a)
* [`jsx-uses-vars`]: ignore lowercase tag names ([#3070][] @alanorozco)

[7.25.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.25.1...v7.25.2
[#3070]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3070
[#3066]: https://github.com/jsx-eslint/eslint-plugin-react/issue/3066
[#3065]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3065
[#3064]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3064
[#3061]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3061

## [7.25.1] - 2021.08.29

### Fixed
* [`no-this-in-sfc`], component detection: Improve stateless component detection ([#3056][] @Wesitos)

[7.25.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.25.0...v7.25.1
[#3056]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3056

## [7.25.0] - 2021.08.27

### Added
* [`jsx-no-useless-fragments`]: add option to allow single expressions in fragments ([#3006][] @mattdarveniza)
* add [`prefer-exact-props`] rule ([#1547][] @jomasti)
* [`jsx-no-target-blank`]: add `forms` option ([#1617][] @jaaberg)
* [`jsx-pascal-case`]: add `allowLeadingUnderscore` option ([#3039][] @pangaeatech)
* [`no-children-prop`]: Add `allowFunctions` option ([#1903][] @alexzherdev)
* [`jsx-runtime`]: set `parserOptions.jsxPragma` for `@typescript-eslint/parser` ([bb64df65][] @ljharb)

### Fixed
* component detection: use `estraverse` to improve component detection ([#2992][] @Wesitos)
* [`destructuring-assignment`], [`no-multi-comp`], [`no-unstable-nested-components`], component detection: improve component detection ([#3001][] @vedadeepta)
* [`no-deprecated`]: fix crash on rest elements ([#3016][] @ljharb)
* [`destructuring-assignment`]: get the contextName correctly ([#3025][] @ohhoney1)
* [`no-typos`]: prevent crash on styled components and forwardRefs ([#3036][] @ljharb)
* [`destructuring-assignment`], component detection: handle default exports edge case ([#3038][] @vedadeepta)
* [`no-typos`]: fix crash on private methods ([#3043][] @ljharb)
* [`jsx-no-bind`]: handle local function declarations ([#3048][] @p7g)
* [`prop-types`], `propTypes`: handle React.* TypeScript types ([#3049][] @vedadeepta)
* [`prop-types`], `propTypes`: add handling for `FC<Props>`, improve tests ([#3051][] @vedadeepta)
* [`prop-types`], `propTypes`: prevent crash introduced in [#3051][] ([#3053][] @ljharb)

### Changed
* [Docs] [`jsx-no-bind`]: updates discussion of refs ([#2998][] @dimitropoulos)
* [Refactor] `utils/Components`: correct spelling and delete unused code ([#3026][] @ohhoney1)
* [Docs] [`jsx-uses-react`], [`react-in-jsx-scope`]: document [`react/jsx-runtime`] config ([#3018][] @pkuczynski @ljharb)
* [Docs] [`require-default-props`]: fix small typo ([#2994][] @evsasse)
* [Tests] add weekly scheduled smoke tests ([#2963][] @AriPerkkio)
* [Docs] improve instructions for `jsx-runtime` config ([#3052][] @ljharb)

[7.25.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.24.0...v7.25.0
[bb64df65]: https://github.com/jsx-eslint/eslint-plugin-react/commit/bb64df6505b3e9a01da5b61626ab9f544caea438
[#3053]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3053
[#3052]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3052
[#3051]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3051
[#3049]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3049
[#3048]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3048
[#3043]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3043
[#3039]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3039
[#3038]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3038
[#3036]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3036
[#3026]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3026
[#3025]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3025
[#3018]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3018
[#3016]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3016
[#3006]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3006
[#3001]: https://github.com/jsx-eslint/eslint-plugin-react/pull/3001
[#2998]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2998
[#2994]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2994
[#2992]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2992
[#2963]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2963
[#1903]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1903
[#1617]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1617
[#1547]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1547

## [7.24.0] - 2021.05.27

### Added
* component detection: add componentWrapperFunctions setting ([#2713][] @@jzabala @LandonSchropp)
* [`no-unused-prop-types`]: add ignore option ([#2972][] @grit96)
* version detection: support recursive processor virtual filename ([#2965][] @JounQin)

### Fixed
* [`jsx-handler-names`]: properly substitute value into message ([#2975][] @G-Rath)
* [`jsx-uses-vars`]: ignore namespaces ([#2985][] @remcohaszing)
* [`jsx-no-undef`]: ignore namespaces ([#2986][] @remcohaszing)
* [`jsx-child-element-spacing`]: Don't flag whitespace around `<br/>` tags ([#2989][] @pascalpp)

### Changed
* [Docs] [`jsx-newline`]: Fix minor spelling error on rule name ([#2974][] @DennisSkoko)
* [Refactor] [`void-dom-elements-no-children`]: improve performance
* [readme] fix missing trailing commas ([#2980][] @sugardon)
* [readme] fix broken anchor link ([#2982][] @vzvu3k6k)
* [Docs] [`jsx-child-element-spacing`]: fixes sentence which ends abruptly ([#2990][] @pascalpp)

[7.24.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.23.2...v7.24.0
[#2990]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2990
[#2989]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2989
[#2986]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2986
[#2985]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2985
[#2982]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2982
[#2980]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2980
[#2977]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2977
[#2975]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2975
[#2974]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2974
[#2972]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2972
[#2965]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2965
[#2713]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2713

## [7.23.2] - 2021.04.08

### Fixed
* [`jsx-max-depth`]: Prevent getting stuck in circular references ([#2957][] @AriPerkkio)
* [`jsx-no-target-blank`]: fix handling of `warnOnSpreadAttributes` being false ([#2953][] @Nokel81)
* [`forbid-dom-props`]: support `JSXNamespacedName` ([#2961][] @mrtnzlml)
* [`forbid-component-props`]: support `JSXNamespacedName` (@ljharb)

### Changed
* Fix CHANGELOG.md ([#2950][] @JounQin)

[7.23.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.23.1...v7.23.2
[#2961]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2961
[#2953]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2953
[#2957]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2957
[#2950]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2950

## [7.23.1] - 2021.03.23

### Fixed
* version detection: support processor virtual filename ([#2949][] @JounQin)

[7.23.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.23.0...v7.23.1
[#2949]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2949

## [7.23.0] - 2021.03.22

### Added
* [`jsx-no-target-blank`]: add fixer ([#2862][] @Nokel81)
* [`jsx-pascal-case`]: support minimatch `ignore` option ([#2906][] @bcherny)
* [`jsx-pascal-case`]: support `allowNamespace` option ([#2917][] @kev-y-huang)
* [`jsx-newline`]: Add prevent option ([#2935][] @jsphstls)
* [`no-unstable-nested-components`]: Prevent creating unstable components inside components ([#2750][] @AriPerkkio)
* added `jsx-runtime` config, for the modern JSX runtime transform (@ljharb)

### Fixed
* [`jsx-no-constructed-context-values`]: avoid a crash with `as X` TS code ([#2894][] @ljharb)
* [`jsx-no-constructed-context-values`]: avoid a crash with boolean shorthand ([#2895][] @ljharb)
* [`static-property-placement`]: do not report non-components ([#2893][] @golopot)
* [`no-array-index-key`]: support optional chaining ([#2897][] @SyMind)
* [`no-typos`]: avoid a crash on bindingless `prop-types` import; add warning ([#2899][] @ljharb)
* [`jsx-curly-brace-presence`]: ignore containers with comments ([#2900][] @golopot)
* [`destructuring-assignment`]: fix a false positive for local prop named `context` in SFC ([#2929][] @SyMind)
* [`jsx-no-target-blank`]: Allow rel="noreferrer" when `allowReferrer` is true ([#2925][] @edemaine)
* [`boolean-prop-naming`]: add check for typescript "boolean" type ([#2930][] @vedadeepta)
* version detection: Add tests that verify versioning works for sibling and child projects ([#2943][] @jcrosetto)
* [`jsx-curly-newline`]: Update error messages ([#2933][] @jbrower2)

### Changed
* [Docs] [`jsx-no-constructed-context-values`][]: fix invalid example syntax ([#2910][] @kud)
* [readme] Replace lists of rules with tables in readme ([#2908][] @motato1)
* [Docs] added missing curly braces ([#2923][] @Muditxofficial)

[7.23.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.22.0...v7.23.0
[#2943]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2943
[#2935]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2935
[#2933]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2933
[#2930]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2930
[#2929]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2929
[#2925]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2925
[#2923]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2923
[#2917]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2917
[#2910]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2910
[#2908]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2908
[#2906]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2906
[#2900]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2900
[#2899]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2899
[#2897]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2897
[#2895]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2895
[#2894]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2894
[#2893]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2893
[#2862]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2862
[#2750]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2750

## [7.22.0] - 2020.12.29

### Added
* [`jsx-key`]: added `checkKeyMustBeforeSpread` option for new jsx transform ([#2835][] @morlay)
* [`jsx-newline`]: add new rule ([#2693][] @jzabala)
* [`jsx-no-constructed-context-values`]: add new rule which checks when the value passed to a Context Provider will cause needless rerenders ([#2763][] @dylanOshima)
* [`jsx-indent-props`]: add `ignoreTernaryOperator` option ([#2846][] @SebastianZimmer)
* [`jsx-no-target-blank`]: Add `warnOnSpreadAttributes` option ([#2855][] @michael-yx-wu)

### Fixed
* [`display-name`]/component detection: avoid a crash on anonymous components ([#2840][] @ljharb)
* [`prop-types`]: function in class that returns a component causes false warning in typescript ([#2843][] @SyMind)
* [`jsx-no-target-blank`]: avoid a crash with a non-string literal ([#2851][] @ljharb)
* [`jsx-no-script-url`]: avoid crash with boolean `href` ([#2871][] @ljharb, @AriPerkkio)
* [`no-typos`]: avoid crash with computed method name ([#2870][] @ljharb, @AriPerkkio)
* [`jsx-max-depth`]: avoid crash with childless jsx child ([#2869][] @ljharb, @AriPerkkio)
* [`jsx-wrap-multilines`]: fix crash with `declaration`s that are on a new line after `=` ([#2875][] @ljharb)
* [`no-unknown-property`]: avoid crash with prop named with Object.prototype key ([#2879][] @ljharb, @AriPerkkio)
* [`prop-types`]: default argument does not count as props-types declaration ([#2877][] @golopot)
* [`jsx-props-no-multi-spaces`]: fix a false positive for beside comments ([#2878][] @golopot)
* [`jsx-no-undef`]: handle the TS parser combined with an invalid ecmaVersion ([#2882][] @ljharb)
* [`no-unused-prop-types`]: apply `skipShapeProps` to exact types ([#2883][] @golopot)
* [`no-danger-with-children`]/[`style-prop-object`]/[`no-adjacent-inline-elements`]: add category, URL ([#2891][] @thofmann)

### Docs
* [`no-unused-prop-types`]: Add new example to rule ([#2852][] @thehereward)
* [`prop-types`]: fix example ([#2881][] @technote-space)

[7.22.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.5...v7.22.0
[#2891]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2891
[#2883]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2883
[#2882]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2882
[#2881]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2881
[#2879]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2879
[#2878]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2878
[#2877]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2877
[#2875]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2875
[#2871]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2871
[#2870]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2870
[#2869]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2869
[#2855]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2855
[#2852]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2852
[#2851]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2851
[#2846]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2846
[#2843]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2843
[#2840]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2840
[#2835]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2835
[#2763]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2763
[#2693]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2693

## [7.21.5] - 2020.10.19

### Fixed
* [`jsx-indent-props`]: Apply indentation when using brackets ([#2826][] @Moong0122)
* [`jsx-handler-names`]: Skip inline handlers when checkInlineFunction=false ([#2833][] @onigoetz)

### Changed
* [Tests] `jsx-indent-props`: Add passing test ([#2823][] @Hypnosphi)

[7.21.5]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.4...v7.21.5
[#2833]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2833
[#2826]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2826
[#2823]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2823

## [7.21.4] - 2020.10.09

### Fixed
* [`no-unused-prop-types`]: Silence false positive on `never` type in TS ([#2815][] @pcorpet)
* [`jsx-indent-props`]: Apply indentation when operator is used in front of the upper line ([#2808][], [#2820][] @Moong0122)
* [Deps] update `jsx-ast-utils` ([#2822][] [jsx-eslint/jsx-ast-utils#102][] @ljharb)

[7.21.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.3...v7.21.4
[#2822]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2822
[#2820]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2820
[#2815]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2815
[#2808]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2808
[jsx-eslint/jsx-ast-utils#102]: https://github.com/jsx-eslint/jsx-ast-utils/pull/102

## [7.21.3] - 2020.10.02

### Fixed
* [`prop-types`]: fix Cannot read property 'type' of undefined error when destructured param ([#2807][] @minwe)
* [`no-typos`]: avoid crash on spread syntax in createReactClass object ([#2816][] @ljharb @Songyu-Wang)

[7.21.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.2...v7.21.3
[#2816]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2816
[#2807]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2807

## [7.21.2] - 2020.09.24

### Fixed
* [`prop-types`]: handle RestElement in destructured param ([#2805][] @hank121314)

[7.21.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.1...v7.21.2
[#2805]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2805

## [7.21.1] - 2020.09.23

### Fixed
* [`jsx-handler-names`]: avoid a crash when an inline prop is not a MemberExpression ([#2803][] @willheslam)

[7.21.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.21.0...v7.21.1
[#2803]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2803

## [7.21.0] - 2020.09.22

### Added
* [`button-has-type`]: support trivial ternary expressions ([#2748][] @Hypnosphi)
* [`jsx-handler-names`]: add `checkInlineFunction` option ([#2761][] @dididy)
* [`jsx-no-literals`]: add `noAttributeStrings` option ([#2782][] @TaLeaMonet)
* [`prop-types`]: add support for `PropTypes.exact` ([#2740][] @jzabala)
* [`jsx-filename-extension`]: Add allow option ([#2746][] @remcohaszing)

### Fixed
* [`function-component-definition`]: ignore object properties ([#2771][] @stefan-wullems)
* [`forbid-component-props`]: Implemented support for "namespaced" components ([#2767][] @mnn)
* [`prefer-read-only-props`]: support Flow `$ReadOnly` ([#2772][], [#2779][], [#2770][] @karolina-benitez)
* [`jsx-handler-names`]: handle whitespace ([#2789][] @AriPerkkio)
* [`prop-types`]: Detect TypeScript types for destructured default prop values ([#2780][] @sunghyunjo)
* [`jsx-pascal-case`]: Handle single character namespaced component ([#2791][] @daviferreira)
* [`jsx-closing-bracket-location`]: In `tag-aligned`, made a distinction between tabs and spaces ([#2796][] @Moong0122)
* [`jsx-handler-names`]: false positive when handler name begins with number ([#1689][] @jsphstls)
* [`prop-types`]: Detect JSX returned by sequential expression ([#2801][] @mikol)
* [`jsx-props-no-multi-spaces`]: "Expected no line gap between" false positive ([#2792][] @karolina-benitez)
* [`no-unknown-property`]: check attributes with any input case ([#2790][] @julienw)
* [`prop-types`]/[`no-unused-prop-types`]: handle CallExpression in ReturnType ([#2802][] @hank121314)
* [`jsx-uses-react`]: mark fragment variables as used ([#2775][] @remcohaszing)
* [`no-unused-prop-types`]: improve component declared props detection ([#2755][] @jzabala)
* [`jsx-props-no-multi-spaces`]: Show error in multi-line props ([#2756][] @iiison)

### Changed
* [Tests] [`jsx-one-expression-per-line`]: add passing tests ([#2799][] @TaLeaMonet)
* [Tests] [`prop-types`]: add test ([#2757][] @jzabala)

[7.21.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.6...v7.21.0
[#2802]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2802
[#2801]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2801
[#2799]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2799
[#2796]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2796
[#2792]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2792
[#2791]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2791
[#2790]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2790
[#2789]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2789
[#2782]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2782
[#2780]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2780
[#2779]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2779
[#2775]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2775
[#2772]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2772
[#2771]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2771
[#2770]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2770
[#2767]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2767
[#2761]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2761
[#2757]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2757
[#2756]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2756
[#2748]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2748
[#2746]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2746
[#2740]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2740
[#1689]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1689

## [7.20.6] - 2020.08.12

### Fixed
* [`jsx-curly-brace-presence`]: fix multiline comment case ([#2716][] @ljharb)
* [`jsx-no-useless-fragment`]: accept fragments with call expressions ([#2744][] @hasparus)
* [`jsx-no-literals`] with allowStrings doesn't work in props ([#2736][] @karolina-benitez)
* [`no-find-dom-node`]: Improve error message ([#2741][] @ecraig12345)
* [`no-typos`]/[`no-unused-prop-types`]/propType detection: Support typescript props interface extension and TSTypeAliasDeclaration ([#2721][] @hank121314)
* [`no-this-in-sfc`]/component detection: add arrow function to list of allowed position for component ([#2708][] @jzabala)
* [`no-access-state-in-setstate`]: add check for class component ([#2711][] @jzabala)
* [`prop-types`]/component detection: avoid a crash when a local `createElement` identifier exists ([#2733][] @ljharb)

### Changed
* [`no-unused-prop-types`]: add test assigning this.props to a variable

[7.20.6]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.5...v7.20.6
[#2744]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2744
[#2741]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2741
[#2737]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2737
[#2736]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2736
[#2733]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2733
[#2721]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2721
[#2716]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2716
[#2711]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2711
[#2708]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2708

## [7.20.5] - 2020.07.28

### Fixed
* [`jsx-curly-brace-presence`]: disable disallowed JSX text chars check in props ([#2710][] @jzabala)
* [`no-unused-state`]: check for class expression ([#2712][] @jzabala)
* [`prop-types`]: handle anonymous functions ([#2730][], [#2731][] @odinho @wKich @jzabala)

### Docs
* [Docs] [`no-access-state-in-setstate`]: fix example ([#2724][] @youngjuning)

[7.20.5]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.4...v7.20.5
[#2731]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2731
[#2730]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2730
[#2724]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2724
[#2712]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2712
[#2710]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2710

## [7.20.4] - 2020.07.26

### Fixed
* improve algorithm to check if a variable is coming from the pragma ([#2706][] @jzabala)
* [`prop-types`]: handle component returning null ([#2696][] @hank121314)
* [`prop-types`]/[`function-component-definition`]: Add check for first letter capitalization in functional component detection ([#2699][] @jzabala)
* [`prop-types`]: use variable value in prop type fields defined by variables ([#2704][] @jzabala)
* [`no-typos`]: warn on a bindingless `react` import

### Changed
* [Tests] `boolean-prop-naming`: Added test for function invocation of bool ([#2697][] @ajkovar)
* [Tests] `jsx-curly-brace-presence`, `jsx-no-comment-textnodes`: add passing tests
* [Refactor] `no-unused-state`: avoid a loop

[7.20.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.3...v7.20.4
[#2704]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2704
[#2699]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2699
[#2697]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2697
[#2696]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2696

## [7.20.3] - 2020-06-30

### Fixed
* [`no-unused-prop-types`]/[`prop-types`]: typescript interface support literal type and only FunctionComponent should have propTypes validation ([#2690][] @hank121314)
* [`no-unused-prop-types`]/TypeScript: avoid crash on indexable interface ([#2687][] @ljharb)

[7.20.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.2...v7.20.3
[#2690]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2690
[#2687]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2687

## [7.20.2] - 2020-06-29

### Fixed
* [`no-unused-prop-types`]: handle optional chaining ([#2679][] @hank121314)
* [`jsx-pascal-case`]: fix a false positive with "H1" ([#2683][] @ljharb)
* [`jsx-no-useless-fragment`]: avoid a crash when autofixing a self-closing React.Fragment ([#2680][] @ljharb)
* [`forbid-prop-types`]: avoid crash ([#2682][] @ljharb)

[7.20.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.1...v7.20.2
[#2683]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2683
[#2682]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2682
[#2680]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2680
[#2679]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2679

## [7.20.1] - 2020-06-28

### Fixed
* [`forbid-dom-props`], [`function-component-definition`]: fix schema typos ([#2667][] @mflorence99)
* [`no-unused-prop-types`]: fix with typescript eslint parser ([#2661][] @eltonio450)

### Changed
* [`forbid-prop-types`]: warn on destructured values as well ([#2676][] @ajkovar)
* relax JSX pragma regexp ([#2643][] @gfmio)
* Cache detected React version ([#2673][] @lencioni)
* [refactor] [`jsx-pascal-case`]: Remove xregexp ([#2636][] @yacinehmito))
* [Tests] a [`no-typos`] test fails in eslint v7.3 ([#2678][] @toshi-toma)
* [Deps] update `jsx-ast-utils`, `object.entries`, `resolve`
* [Dev Deps] update `@types/eslint`, `@types/estree`, `@types/node`, `@typescript-eslint/parser`, `eslint-config-airbnb-base`, `eslint-plugin-eslint-plugin`, `eslint-plugin-import`, `typescript`

[7.20.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.20.0...v7.20.1
[#2676]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2676
[#2673]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2673
[#2667]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2667
[#2661]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2661
[#2643]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2643
[#2636]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2636

## [7.20.0] - 2020-05-12

### Added
* support eslint v7 ([#2635][] @ljharb, @toshi-toma)
* [`forbid-component-props`][]/[`forbid-dom-props`][]: Allow a custom message with forbid props ([#2615][] @mtamhankar1)
* [`jsx-no-literals`][]: add `ignoreProps` option to ignore props validation ([#2146][] @iiison)

### Fixed
* [`jsx-sort-props`][]: only use localeCompare when case is ignored ([#2556][] @tanmoyopenroot)
* [`jsx-key`][]: add a failing test case for optional chaining ([#2610][] @JonathanLee-LX)
* [`no-unused-state`][]: handle optional chaining ([#2588][] @golopot)
* [`jsx-pascal-case`][]: Do not consider namespaces when checking for DOM ([#2638][] @yacinehmito)
* [`jsx-curly-spacing`][], [`jsx-no-bind`][], `usedPropTypes` util: avoid node.start and node.end ([25b1936][] @toshi-toma)
* [`jsx-no-target-blank`][]: allow `no-referrer` without `noopener` by default ([#2043][] @seancrater)
* [`button-has-type`][]: improve message when non-static value is used ([aecff62][] @golopot)
* [`no-adjacent-inline-elements`][]: prevent crash on nullish children ([#2621][] @Rogdham)
* [`prop-types`][]: avoid crash when spreading any type ([#2606][] @golopot))
* [`require-render-return`][]: add missing "a" ([#2604][] @leothorp)
* [`jsx-no-comment-textnodes`][]: fix for `@typescript-eslint/parser` ([#2601][] @Axnyff)
* [`displayName`][]: avoid a crash when using React.memo ([#2587][] @golopot)

### Docs
* Clean up examples in rule docs ([#2546][] @silvenon)
* [readme] Add Rules of Hooks to Other useful plugins section ([#2633][] @petetnt)
* [`no-this-in-sfc`][]: backtick `this` ([#2616][] @mrflip)
* [`function-component-definition`][]: Fix unnamedComponents option examples ([#2608][] @vkrol))

### Changed
* [Deps] Move "semver" to devDependencies ([#2595][] @rajivshah3)
* [eslint] remove `operator-linebreak` override ([#2578][] @golopot)
* [Tests] `button-has-type`: ensure no mistakenly allowed identifiers named `button`/`submit`/`reset` ([#2625][] @golopot)
* [Tests] `displayName`: add a test case ([#2593][] @golopot)
* [Dev Deps] update `@types/eslint`, `@types/estree`, `@types/node`, `@typescript-eslint/parser`, `coveralls`, `eslint-config-airbnb-base`, `eslint-plugin-import`, `typescript`

[7.20.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.19.0...v7.20.0
[#2638]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2638
[#2635]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2635
[#2633]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2633
[#2625]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2625
[#2621]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2621
[#2616]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2616
[#2615]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2615
[#2610]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2610
[#2608]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2608
[#2606]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2606
[#2604]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2604
[#2601]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2601
[#2595]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2595
[#2593]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2593
[#2588]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2588
[#2587]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2587
[#2578]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2578
[#2556]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2556
[#2546]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2546
[#2146]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2146
[#2043]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2043
[25b1936]: https://github.com/jsx-eslint/eslint-plugin-react/commit/25b19365e6cc3f188d6a5ed6cecc70fe6f1af7cd
[aecff62]: https://github.com/jsx-eslint/eslint-plugin-react/commit/aecff625bf0590ed4d80ed6b58b81af11901f5f6

## [7.19.0] - 2020-03-06

### Added
 * [`style-prop-object`][]: Add `allow` option ([#1819][] @hornta)
 * [`jsx-pascal-case`][]: Support unicode characters ([#2557][] @Svish)

### Fixed
 * [`prefer-stateless-function`][]: avoid crash on ts empty constructor ([#2582][] @golopot)
 * [`no-adjacent-inline-elements`][]: avoid a crash ([#2575] @ljharb)
 * [`no-unused-prop-types`][]: Change the reporting to point to a more accurate node ([#2292][] @jseminck)
 * [`self-closing-comp`][]: consider JSXMemberExpression as component too ([#2572][] @Belco90)
 * [`no-unused-prop-types`][]: make `markPropTypesAsUsed` work with `TSEmptyBodyFunctionExpression` AST node ([#2560][] @guillaumewuip)
 * [`displayName`][] (but really, `propTypes` detection): do not crash on empty flow type spreads ([#2570][] @ljharb)

### Changed
 * [readme] Small visual inconsistency ([#2568] @arvigeus)
 * [docs] add `react/` prefix to rule name, for consistency
 * [`no-unescaped-entities`][]: skip test cases that are now parsing errors in acorn-jsx@5.2.0 ([#2583] @golopot)

[7.19.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.18.3...v7.19.0
[#2583]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2583
[#2582]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2582
[#2575]: https://github.com/jsx-eslint/eslint-plugin-react/issue/2575
[#2572]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2572
[#2570]: https://github.com/jsx-eslint/eslint-plugin-react/issue/2570
[#2568]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2568
[#2560]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2560
[#2557]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2557
[#2292]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2292
[#1819]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1819

## [7.18.3] - 2020-02-02

### Fixed
 * [`jsx-indent`][]: don't check literals not within JSX ([#2564][] @toshi-toma)

[7.18.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.18.2...v7.18.3
[#2564]: https://github.com/jsx-eslint/eslint-plugin-react/issue/2564

## [7.18.2] - 2020-02-01

### Fixed
 * [`jsx-indent`][]: avoid a crash on non-string literals ([#2561][] @ljharb)

[7.18.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.18.1...v7.18.2
[#2561]: https://github.com/jsx-eslint/eslint-plugin-react/issue/2561

## [7.18.1] - 2020-02-01

### Fixed
 * [`jsx-indent`][]: Does not check indents for JSXText ([#2542][] @toshi-toma)
 * [`jsx-props-no-spreading`][]: add support for namespaced jsx components ([#2534][] @jonathanpalma)
 * [`jsx-no-target-blank`][]: allow rel to be an expression ([#2544][] @odinho)
 * [`sort-comp`][]: `|` isn’t a valid regex flag; `u` and `s` are (@ljharb)

### Changed
 * [Docs] use `markdown-magic` to automatically sort all rules alphabetically ([#1742][] @ybiquitous)
 * [Docs] [`jsx-props-no-spreading`][]: fix typo to use correct rule ([#2547][] @jonggyun))

[7.18.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.18.0...v7.18.1
[#2547]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2547
[#2544]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2544
[#2542]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2542
[#2534]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2534
[#1742]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1742

## [7.18.0] - 2020-01-15

### Added
 * [`require-default-props`][]: add option to ignore functional components ([#2532][] @RedTn)
 * [`function-component-definition`][]: Enforce a specific function type for function components ([#2414][] @Stefanwullems)
 * [`no-adjacent-inline-elements`][]: Prevent adjacent inline elements not separated by whitespace ([#1155][] @SeanHayes)
 * [`jsx-no-script-url`][]: prevent usage of `javascript:` URLs ([#2419][] @sergei-startsev)

### Fixed
 * [`jsx-pascal-case`][]: false negative with namespacing ([#1337][] @mfyuce)
 * [`jsx-curly-brace-presence`][]: Fix `curly-brace-presence` edge cases ([#2523][] @rafbgarcia)
 * [`prop-types`][]: Does not validate missing propTypes for LogicalExpression ([#2533][] @toshi-toma)
 * [`no-unknown-property`][]: allowTransparency does not exist in React >= v16.1 ([#1538][] @dawidvdh)
 * [`jsx-curly-brace-presence`][]: Fix error related to tags line break ([#2521][] @rafbgarcia)
 * [`no-typos`][]: Compilation error when method name is string instead of identifier ([#2514][] @shijistar)
 * [`jsx-curly-brace-presence`][]: allow trailing spaces in TemplateLiteral ([#2507][] @doochik)
 * [`no-unused-prop-types`], [`no-unused-state`]: fix false positives when using TS type assertions ([#2536][] @kdmadej)

### Changed
 * [Docs] [`no-render-return-value`][]: Fix title ([#2540][] @micnic)
 * [Refactor]: remove unused codes in util/propTypes ([#2288][] @golopot)
 * [`no-typos`]: check static lifecycle methods ([#2006][] @bsonntag)
 * [Docs] [`jsx-first-prop-new-line`][]: Fix rule name in "Rule Options" section ([#2535][] @barreira)
 * [Tests] [`no-unused-prop-types`][]: Added test cases ([#977][] @dozoisch)
 * [Tests] avoid running tests on pretest job
 * [meta] Move eslint-plugin-eslint-plugin to devDeps ([#2510][] @nstepien)
 * [Deps] update `array-includes`, `object.entries`, `object.fromentries`, `object.values`, `resolve`

[7.18.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.17.0...v7.18.0
[#2540]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2540
[#2536]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2536
[#2535]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2535
[#2533]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2533
[#2532]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2532
[#2523]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2523
[#2521]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2521
[#2514]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2514
[#2510]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2510
[#2507]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2507
[#2419]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2419
[#2414]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2414
[#2288]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2288
[#2006]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2006
[#1538]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1538
[#1337]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1337
[#1155]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1155
[#977]: https://github.com/jsx-eslint/eslint-plugin-react/pull/977

## [7.17.0] - 2019-11-28

### Added
 * [`jsx-no-target-blank`][]: add `allowReferrer` option ([#2478][] @eps1lon)
 * [`jsx-handler-names`][]: add `checkLocalVariables` option ([#2470][] @aub)
 * [`prop-types`][]: Support Flow Type spread ([#2446][] @moroine)
 * [`jsx-props-no-spreading`][]: add `explicitSpread` option to allow explicit spread of props ([#2449][] @pawelnvk)
 * [`jsx-no-target-blank`][]: warn on `target={'_blank'}` expressions ([#2451][] @timkraut)
 * [`function-component-definition`]: Enforce a specific function type for function components ([#2414][] @Stefanwullems)

### Fixed
 * [`sort-prop-types`][], [`jsx-sort-default-props`][]: disable broken autofix ([#2505][] @webOS101)
 * [`no-typos`][]: improve report location ([#2468][] @golopot)
 * [`jsx-no-literals`][]: trim whitespace for `allowedStrings` check ([#2436][] @cainlevy)
 * [`jsx-curly-brace-presence`][]: Fix filter of undefined error with whitespace inside jsx attr curlies ([#2460][] @dustinyoste)
 * [`no-render-return-value`][]: should warn when used in assignment expression ([#2462][] @jichu4n)
 * [`jsx-curly-brace-presence`][]: allow trailing spaces in literal ([#2448][] @doochik)

### Changed
 * [Deps] update `jsx-ast-utils`, `object.fromentries`, `resolve`
 * [eslint] fix func-names and change object-shorthand to 'always' ([#2483][] @golopot)
 * [Docs] `jsx-first-prop-new-line`: Fix documentation formatting ([#2489][] @pjg)
 * [Docs] [`prop-types`][]: Update 'skipUndeclared' in rule options ([#2504][] @cjnickel)
 * [Docs] [`jsx-first-prop-new-line`][]: fix wrong rule name ([#2500][] @zgayjjf)
 * [eslint] enable eslint-plugin-eslint-plugin ([#2469][] @golopot)
 * [Docs] [`jsx-props-no-multi-spaces`][]: suggest using core rule instead ([#2463][] @golopot)
 * [Docs] [`jsx-first-prop-new-line`][]: add rule options ([#2465][] @SerdarMustafa1)
 * [Docs] [`jsx-no-target-blank`][]: Add section about overriding for trusted links ([#2438][] @aschriner)
 * [Docs] fix typo ([#2453][] @cainwatson)
 * [Docs] [`no-unused-prop-types`][]: clean up prose ([#2273][] @coryhouse)
 * [Docs] [`jsx-no-bind`][]: add section about React Hooks ([#2443][] @kdex)

[7.17.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.16.0...v7.17.0
[#2532]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2532
[#2505]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2505
[#2504]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2504
[#2500]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2500
[#2489]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2489
[#2483]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2483
[#2478]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2478
[#2470]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2470
[#2469]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2469
[#2468]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2468
[#2465]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2465
[#2463]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2463
[#2460]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2460
[#2453]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2453
[#2451]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2451
[#2449]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2449
[#2448]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2448
[#2446]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2446
[#2443]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2443
[#2438]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2438
[#2436]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2436
[#2414]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2414
[#2273]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2273

## [7.16.0] - 2019-10-04

### Added
* [`jsx-sort-default-props`][]: make rule fixable ([#2429][] @emroussel)

### Fixed
* [`jsx-no-useless-fragment`][]: use `array-includes` over `.includes` for back compat (@ljharb)
* [`jsx-curly-brace-presence`][]: allow necessary white-space literal ([#2437][] @uniqname)
* [`jsx-curly-brace-presence`][]: warns incorrectly on trailing whitespace ([#2431][] @BC-M)
* [`no-unused-prop-types`][]: false positive when nested destructuring ([#2428][] @golopot)

[7.16.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.15.1...v7.16.0
[#2437]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2437
[#2431]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2431
[#2429]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2429
[#2428]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2428

## [7.15.1] - 2019-10-01

### Fixed
* [`jsx-curly-brace-presence`][]: bail out checks when JSXElements are passed as props ([#2426][] @vedadeepta)

### Changed
* [Docs] [`prefer-es6-class`][]: Fix typos ([#2425][] @spencerbyw)

[7.15.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.15.0...v7.15.1
[#2426]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2426
[#2425]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2425

## [7.15.0] - 2019-09-30

### Added
* add [`jsx-no-useless-fragment`][] rule ([#2261][] @golopot)
* [`jsx-handler-name`][]: allow `false` to disable `eventHandlerPrefix`/`eventHandlerPropPrefix` ([#2410][] @tanmoyopenroot)
* [`sort-comp`][]: add `static-variables` grouping ([#2408][] @vedadeepta)
* [`jsx-no-literals`][]: Add `allowedStrings` option ([#2380][] @benhollander)
* [`no-multi-comp`][]: Added handling for `forwardRef` and `memo` wrapping components declared in the same file ([#2184][] @jenil94)
* [`jsx-pascal-case`][]: `allowAllCaps` option now allows `SCREAMING_SNAKE_CASE` ([#2364][] @TylerR909)

### Fixed
* [`jsx-indent`][]: Fix false positive when a jsx element is the last statement within a do expression (with tests) ([#2200][] @Kenneth-KT)
* [`jsx-curly-brace-presence`][]: fix jsx tags in braces ([#2422][] @tanmoyopenroot)
* [`display-name`][]: Fix false positives ([#2399][] @BPScott)
* [`jsx-curly-brace-presence`][]: report unnecessary curly braces with children on next line ([#2409][] @vedadeepta)
* [`no-unused-prop-types`][]: false positive with callback ([#2375][] @golopot)
* Fix prop-types detection collision on renamed props ([#2383][] @yannickcr)
* [`jsx-sort-props`][]: use localeCompare rather than comparison operator ([#2391][] @tanmoyopenroot)
* [`jsx-pascal-case`][]: allow one-letter-named components ([#2395][] @Haegin)
* [`jsx-wrap-multilines`][]: fix incorrect formatting ([#2392][] @tanmoyopenroot)
* [`require-optimization`][]: fix when using arrow function in class components ([#2385][] @jenil94)
* [`no-deprecated`][]: Deprecate cWM/cWRP/cWU lifecycle methods since React 16.9.0 ([#2378][] @meowtec)
* [`jsx-key`][]: improve docs and confusing error message ([#2367][] @kaykayehnn)
* Recognize props wrapped in flow $ReadOnly<> utility type ([#2361][] @lukeapage)
* [`prop-types`][]: false positive with setState updator ([#2359][] @golopot)

### Changed
* [Docs] [`no-access-state-in-setstate`][]: update grammar ([#2418][] @neaumusic)
* [`jsx-curly-brace-presence`][], [`jsx-one-expression-per-line`][], [`no-danger-with-children`][]: add `isWhiteSpaces` to `lib/util/jsx` ([#2409][] @vedadeepta)

[7.15.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.14.3...v7.15.0
[#2422]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2422
[#2410]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2410
[#2409]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2409
[#2408]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2408
[#2402]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2402
[#2399]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2399
[#2395]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2395
[#2392]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2392
[#2391]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2391
[#2385]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2385
[#2383]: https://github.com/jsx-eslint/eslint-plugin-react/issue/2383
[#2380]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2380
[#2378]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2378
[#2375]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2375
[#2367]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2367
[#2364]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2364
[#2361]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2361
[#2359]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2359
[#2261]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2261
[#2200]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2200
[#2184]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2184

## [7.14.3] - 2019-07-23

### Fixed
* Fix [`prop-types`][] to ignore validation when Flow indexers are used ([#2330][] @yannickcr)
* Fix error being thrown after the first warning when react version cannot be detected ([#2336][] @abhishekdev)
* Fix component detection when `memo` and `forwardRef` are used together ([#2349][] @yannickcr)

### Changed
* Documentation improvements (@ljharb, [#2354][] @golopot)

[7.14.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.14.2...v7.14.3
[#2330]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2330
[#2336]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2336
[#2349]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2349
[#2354]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2354

## [7.14.2] - 2019-06-24

### Fixed
* Fix [`prop-types`][] crash on for...of destructuring ([#2326][] @yannickcr)

[7.14.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.14.1...v7.14.2
[#2326]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2326

## [7.14.1] - 2019-06-24

### Fixed
* Fix [`prop-types`][] crash on multiple destructuring ([#2319][] @golopot)

[7.14.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.14.0...v7.14.1
[#2319]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2319

## [7.14.0] - 2019-06-23

### Added
* Add [`jsx-curly-newline`][] rule ([#1493][] @golopot)
* Add support for nested destructuring to [`prop-types`][] ([#296][] [#1422][] @golopot)
* Add support for variables defined as props to [`prop-types`][] and [`no-unused-prop-types`][] ([#442][] [#833][] [#1002][] [#1116][] [#1257][] [#1764][] @golopot)
* Add `checkFragmentShorthand` option to [`jsx-key`][] ([#2316][] @kaykayehnn)

### Fixed
* Fix [`no-did-mount-set-state`][] and [`no-did-update-set-state`][] to handle cDU and cDM defined as class properties ([#1595][] @jaaberg)
* Fix [`sort-prop-types`][] cash when a shape PropType is defined in a variable ([#1749][] @alexzherdev)
* Fix [`no-unused-state`][] false positive when using state of non-lifecycle method ([#2274][] @golopot)
* Fix [`static-property-placement`][] false positive when accessing static property inside method ([#2283][] @dmason30)
* Fix [`prop-type`][] detection for annotated props with default value ([#2298][] @yannickcr)

### Changed
* Add ESLint 6.0.0 as valid peerDependency (@yannickcr)
* Improve [`no-render-return-value`][] performance ([#2259][] @golopot)
* Change [`jsx-sort-props`][] to report errors only on the identifier ([#2312][] @MrHen)
* Change to warn only once if react version cannot be detected ([#2276][] @ljharb)
* Documentation improvements ([#2263][] @dimitropoulos, [#2262][] @ybiquitous, [#2295][] @battaglr, [#2302][] @Jason-Cooke, [#2303][] @golopot)
* Code refactoring ([#2265][] [#2267][] [#2286][] [#2294][] @golopot, @ljharb)
* Tests improvements ([#2304][] [#1047][] @golopot, @yannickcr)

[7.14.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.13.0...v7.14.0
[#296]: https://github.com/jsx-eslint/eslint-plugin-react/issues/296
[#442]: https://github.com/jsx-eslint/eslint-plugin-react/issues/442
[#833]: https://github.com/jsx-eslint/eslint-plugin-react/issues/833
[#1002]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1002
[#1047]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1047
[#1116]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1116
[#1257]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1257
[#1422]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1422
[#1493]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1493
[#1595]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1595
[#1749]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1749
[#1764]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1764
[#2259]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2259
[#2262]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2262
[#2263]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2263
[#2265]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2265
[#2267]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2267
[#2274]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2274
[#2276]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2276
[#2283]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2283
[#2286]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2286
[#2294]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2294
[#2295]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2295
[#2298]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2298
[#2302]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2302
[#2303]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2303
[#2304]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2304
[#2312]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2312
[#2316]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2316

## [7.13.0] - 2019-05-03

### Added
* Make [`jsx-sort-props`][] fully fixable ([#2250][], @guliashvili)
* [`boolean-prop-naming`][]: add `validateNested` option to validate shape prop names ([#2234][], @pawelnvk)
* add [`static-property-placement`][] rule ([#2193][], @dmason30)
* add "detect" for flow version ([#2233][], @jedwards1211)
* [`jsx-indent`][]: Add `indentLogicalExpressions` option ([#2227][], @mdnsk)
* add [`jsx-props-no-spreading`][] ([#2191][], @ashbhir)
* [`no-string-refs`][]: Added `noTemplateLiteral` option ([#2167][], @jenil94)
* add `linkComponents` setting ([#2116][], @gbakernet)
* [`jsx-no-target-blank`][]: add support for `linkComponents` setting ([#2116][], @gbakernet)
* Add [`state-in-constructor`][] rule ([#1945][], @lukyth)
* Add [`prefer-read-only-props`][] rule ([#2110][], @golopot)
* [`no-unescaped-entities`][]: more friendly error message; add config to adjust ([#2016][], @stevemao)

### Fixed
* [`jsx-props-no-multi-spaces`][]: support generic components (ts) ([#2256][], @mateuszsokola)
* [`prop-types`][]: fix case with destructuring and default param ([#2246][], @golopot)
* [`prefer-stateless-function`][]: Ignoring pure components without props and context usage ([#2238][], @pawelnvk)
* `propTypes`: resolveSuperParameterPropsType: add null check ([#2232][], @jedwards1211)
* [`self-closing-comp`][]: stop reporting single-line spaces ([#2210][], @golopot)
* [`require-render-return`][]: more accurate report location ([#2229][], @golopot)
* [`sort-prop-types`][]: Fix sorting props with numeric keys ([#2230][], @pawelnvk)
* [`display-name`][]: fix false negative around nested functions ([#2225][], @dwelle)
* [`no-unknown-property`][]: fix case like `<Foo.bar>` ([#2207][], @golopot)
* [`jsx-curly-brace-presence`][]: accept multiline template string ([#2203][], @golopot)
* [`jsx-one-expression-per-line`][]: fix when using tabs ([#2198][], @Ohar)
* [`prop-types`][]: Fix false positive on computed member expression ([#2202][], @golopot)
* [`jsx-sort-default-props`][]: fix case with spread ([#2182][], @VincentLanglet)
* [`no-this-in-sfc`][]: Fix false positive on SFC defined as object property ([#2147][], @yannickcr)
* [`sort-comp`][]: correctly recognize instance variables declared without explicit value ([#2183][], @yannickcr)
* [`no-unused-state`][]: fix set state callback destructing & state use inside callback ([#2151][], @barakyosi)
* [`no-multi-comp`][]: correctly ignore wrapped stateless components: ([#2145][], @yannickcr)
* [`display-name`][]: avoid crash on for..of ([#2137][], @ljharb)

### Changed
* [Docs] [`no-access-state-in-setstate`][]: Use syntax highlighting for examples ([#2160][], @pReya)
* [Docs] [`jsx-fragments`][]: add "fixable" note ([#2143][], @joshunger)
* [Docs] Added shared settings info, React version default note ([#2180][], @samsch)
* [Tests] [`jsx-curly-spacing`][]: add regression test case ([#2206][], @ColCh)

[7.13.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.12.4...v7.13.0
[#2256]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2256
[#2250]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2250
[#2246]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2246
[#2238]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2238
[#2234]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2234
[#2233]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2233
[#2232]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2232
[#2230]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2230
[#2229]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2229
[#2227]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2227
[#2225]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2225
[#2210]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2210
[#2207]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2207
[#2206]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2206
[#2203]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2203
[#2202]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2202
[#2198]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2198
[#2193]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2193
[#2191]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2191
[#2183]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2183
[#2182]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2182
[#2180]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2180
[#2167]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2167
[#2147]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2147
[#2145]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2145
[#2143]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2143
[#2137]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2137
[#2116]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2116
[#2110]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2110
[#2016]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2016
[#1945]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1945

## [7.12.4] - 2019-01-16

### Fixed
* [`no-unused-prop-types`][]: avoid a crash ([#2131][], @ljharb)
* [`prop-types`][]: avoid further crashes from nonexistent nodes in unusedPropTypes ([#2127][], @ljharb)
* [`prop-types`][]: Read name of callee object ([#2125][], @CrOrc)
* [`prop-types`][]: Ignore reassignments when matching props declarations with components ([#2051][], [#1957][], @yannickcr)
* [`prop-types`][], [`no-unused-prop-types`][], [`require-default-props`][]: Detect components with return statement in switch/case ([#2118][], @yannickcr)

### Changed
* [`prop-types`][], [`no-typos`][]: add passing test cases ([#2123][], [#2128][], [#2136][], [#2134][], @ljharb)

[7.12.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.12.3...v7.12.4
[#2136]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2136
[#2134]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2134
[#2131]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2131
[#2128]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2128
[#2127]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2127
[#2125]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2125
[#2123]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2123
[#2118]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2118
[#2051]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2051
[#1957]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1957

## [7.12.3] - 2019-01-04

### Fixed
* [`jsx-indent`][]: Prevent crash on valueless props ([#2120][], @jomasti)
* [`jsx-fragments`][]: avoid crashing on self-closing fragments ([#2113][], @alexzherdev)
* [`no-unused-prop-types`][]: Fix propType detection inside class bodies ([#2115][], @drx)
* [`no-unused-prop-types`][]: fix issue with propTypes misclassifying props ([#2111][], @drx)
* [`display-name`][]: fix false positive for `React.memo` ([#2109][], @jomasti)

### Changed
* [Docs] add a missing comma in the JSON settings ([#2117][], @haideralsh)
* [Docs] update README to document React version detection ([#2114][], @mohsinulhaq)

[7.12.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.12.2...v7.12.3
[#2120]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2120
[#2117]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2117
[#2115]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2115
[#2114]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2114
[#2113]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2113
[#2111]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2111
[#2109]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2109

## [7.12.2] - 2019-01-02

### Fixed
* [`prop-types`][]: avoid crash on used prevProps ([#2095][], @ljharb)
* Version warning: Link does not end with '.' ([#2103][], @yoyo837))
* [`forbid-prop-types`][]: fix crash with propWrapper check on MemberExpressions ([#2104][], @ljharb)

[7.12.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.12.1...v7.12.2
[#2104]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2104
[#2103]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2103
[#2095]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2095

## [7.12.1] - 2019-01-01

### Fixed
* [`no-unused-state`][]: Fix crash with class fields ([#2098][], @jomasti)
* [`prop-types`][]: Fix false positives inside lifecycle methods ([#2099][], @jomasti)
* [`jsx-max-depth`][]: avoid a crash ([#2102][], @ljharb)
* [`jsx-wrap-multilines`][]: avoid crash when no trailing newline ([#2100][], @ljharb)

### Changed
* Fix CHANGELOG.md ([#2097][], @alexzherdev)

[7.12.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.12.0...v7.12.1
[#2102]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2102
[#2100]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2100
[#2099]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2099
[#2098]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2098
[#2097]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2097

## [7.12.0] - 2018-12-27

### Added
* [`no-typos`]: Support createClass ([#1828][], @alexzherdev)
* Support detecting React.forwardRef/React.memo ([#2089][], @jomasti)
* [`jsx-indent`][]: add `checkAttributes` option for JSX attribute indentation ([#2086][], @jomasti)
* Change allowed `propWrapperFunctions` setting values ([#2065][], @jomasti)
* add [`jsx-fragments`][] rule to enforce fragment syntax ([#1994][], @alexzherdev)
* Support "detect" option for React version setting ([#1978][], @alexzherdev)
* Support shorthand fragment syntax in many rules ([#1956][], @alexzherdev)
* [`jsx-no-literals`][]: print node value in warning message ([#2008][], @jlgonzalezdev)

### Fixed
* [`jsx-max-depth`][]: Fix depth of JSX siblings in a JSXEpressionContainer ([#1824][], @alexzherdev)
* [`no-array-index-key`][]: fix in React.Children methods ([#2085][], @himynameisdave)
* [`no-unused-state`][]: handle functional setState ([#2084][], @jomasti)
* version errors should log to stderr, not stdout ([#2082][], @ljharb)
* [`no-deprecated`][]: Disable legacy lifecycle methods linting for now ([#2069][], @sergei-startsev)
* ensure that react and flow versions can be numbers ([#2056][], @ljharb)
* [`forbid-foreign-prop-types`][]: ensure `allowInPropTypes` option applies to class fields ([#2040][], @Sheile)
* [`jsx-wrap-multilines`][]: catch single missing newlines ([#1984][], @MrHen)
* [`jsx-first-prop-new-line`][]: Fix for parsers (like TypeScript) ([#2026][], @HauptmannEck)
* [`sort-comp`][]: Fix fixer in case of more than 10 props ([#2012][], @tihonove)
* [`no-unused-state`][] Don't depend on state parameter name ([#1829][], @alexzherdev)
* [`no-this-in-sfc`][] fix for class properties ([#1995][], @sergei-startsev)
* [`no-this-in-sfc`][] fix rule behavior for arrow functions inside a class field ([#1989][], @sergei-startsev)
* [`destructuring-assignment`][]: handle nested props usage ([#1983][], @alexzherdev)
* [`sort-prop-types`][]: fix string property order ([#1977][], @metreniuk)
* [`jsx-no-target-blank`][]: don’t crash when there’s no value ([#1949][], @ljharb)
* [`prop-types`][], [`no-unused-prop-types`][]: better handle object spread ([#1939][], @alexzherdev)

### Changed
* [`jsx-fragments`][]: improve message text ([#2032][], @alexzherdev)
* [`no-unsafe`][]: handle all unsafe life-cycle methods ([#2075][], @sergei-startsev)
* [`require-default-props`][]: Change error message naming from singular defaultProp to plural defaultProps ([#2064][], @jseminck)
* [Refactor] Extract used `propTypes` detection ([#1946][], @alexzherdev)
* [Refactor] Extract `defaultProps` detection ([#1942][], @alexzherdev)
* [Refactor] Extract required `propTypes` detection ([#2001][], @alexzherdev)
* [Docs] [`no-did-mount-set-state`][], [`no-did-update-set-state`][], [`no-will-update-set-state`][]: fix docs URLs ([#2090][], @JBallin)
* [Docs] Remove statement on GC in jsx-no-bind ([#2067][], @rickhanlonii)
* [Docs] [`jsx-sort-props`][]: Fix small mistake ([#2044][], @dimitarnestorov)
* [Docs] [`no-unescaped-entities`][]: add more escape examples ([#2015][], @stevemao)
* [Docs] [`display-name`][]: mention default `ignoreTranspilerName` value ([#2002][], @OliverJAsh)
* [Docs] [`jsx-no-target-blank`][]: Add full example ([#1988][], @atomcorp)
* [Docs] Update [`jsx-no-target-blank`][].md ([#1953][], @brunocoelho)
* [Changelog] fix "Ignore class properties" contributor ([#1941][], @alexzherdev)
* [Tests] Remove redundant `require('babel-eslint')` from tests ([#2004][], @sergei-startsev)
* [Tests] [`prop-types`][]: Add tests for prop-types destructuring ([#2029][], @sstern6)
* [Tests] [`display-name`][]: add false positive component detection for destructured createElement ([#1098][], @arian)

[7.12.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.11.1...v7.12.0
[#2090]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2090
[#2089]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2089
[#2086]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2086
[#2085]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2085
[#2084]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2084
[#2082]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2082
[#2075]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2075
[#2069]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2069
[#2067]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2067
[#2065]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2065
[#2064]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2064
[#2056]: https://github.com/jsx-eslint/eslint-plugin-react/issues/2056
[#2044]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2044
[#2040]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2040
[#2032]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2032
[#2029]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2029
[#2026]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2026
[#2015]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2015
[#2012]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2012
[#2008]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2008
[#2004]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2004
[#2002]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2002
[#2001]: https://github.com/jsx-eslint/eslint-plugin-react/pull/2001
[#1995]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1995
[#1994]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1994
[#1989]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1989
[#1988]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1988
[#1984]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1984
[#1983]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1983
[#1978]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1978
[#1977]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1977
[#1956]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1956
[#1953]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1953
[#1949]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1949
[#1946]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1946
[#1942]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1942
[#1941]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1941
[#1939]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1939
[#1829]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1829
[#1828]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1828
[#1824]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1824
[#1098]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1098

## [7.11.1] - 2018-08-14
### Fixed
* stop crashing when assigning to propTypes ([#1932][], @alexzherdev)

### Changed
* Fix changelog links ([#1926][], @ferhatelmas)
* Fix changelog links ([#1929][], @alexzherdev)

[7.11.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.11.0...v7.11.1
[#1932]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1932
[#1929]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1929
[#1926]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1926

## [7.11.0] - 2018-08-13
### Added
* [`jsx-one-expression-per-line`][]: add "allow" option ([#1924][], @alexzherdev)
* [`sort-prop-types`][]: add autofix ([#1891][], @finnp)
* [`jsx-no-bind`][]: Add ignoreDOMComponents option ([#1868][], @alexzherdev)
* Output a warning if React version is missing in settings ([#1857][], @alexzherdev)

### Fixed
* [`destructuring-assignment`][]: Ignore class properties ([#1909][], @alexandernanberg)
* [`destructuring-assignment`][], component detection: ignore components with confidence = 0 ([#1907][], @alexzherdev)
* [`boolean-prop-naming`][]: Handle inline Flow type ([#1905][], @alexzherdev)
* [`jsx-props-no-multi-spaces`][]: Handle member expressions ([#1890][], @alexzherdev)
* [`sort-comp`][]: Allow methods to belong to any matching group ([#1858][], @nosilleg)
* [`jsx-sort-props`][]: Fix `reservedFirst` ([#1883][], @fleischie)
* [`prop-types`][]: (flow) Stop crashing on undefined or null properties ([#1860][], @nicholas-l)
* [`no-unknown-property`][]: Make attribute "charset" valid ([#1863][], @silvenon)
* [`no-deprecated`][]: report identifier AST node instead of the class node ([#1854][], @jsnajdr)
* [`button-has-type`][]: Account for pragma ([#1851][], @alexzherdev)
* [`button-has-type`][]: improve error message when an identifier is used as the value ([#1874][], @ljharb)
* support JSXText nodes alongside Literal nodes (@ljharb)

### Changed
* Extract propTypes detection code ([#1911][], @alexzherdev)
* Fix broken links in changelog ([#1849][], @alexzherdev)
* [`no-unused-state`][]: combine spread visitors (@ljharb)
* [`jsx-one-expression-per-line`][]: Fix JSX Syntax in docs ([#1867][], @peter-mouland)
* [`jsx-max-depth`][], [`jsx-sort-default-props`][]: add missing docs urls ([#1880][], @flyerhzm)
* [`jsx-indent`][]: add test cases ([#1892][], @alexzherdev)
* [`prop-types`][]: add test cases ([#1898][], @alexzherdev)
* Add a helper function for determining function-like expressions ([#1914][], @alexzherdev)
* [`jsx-props-no-multi-spaces`][]: update docs ([#1918][], @BenRichter)

[7.11.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.10.0...v7.11.0
[#1924]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1924
[#1918]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1918
[#1914]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1914
[#1911]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1911
[#1909]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1909
[#1907]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1907
[#1905]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1905
[#1898]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1898
[#1892]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1892
[#1891]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1891
[#1890]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1890
[#1883]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1883
[#1880]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1880
[#1874]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1874
[#1868]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1868
[#1867]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1867
[#1863]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1863
[#1860]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1860
[#1858]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1858
[#1857]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1857
[#1854]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1854
[#1851]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1851
[#1849]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1849

## [7.10.0] - 2018-06-24
### Added
* Allow eslint ^5 ([#1843][] @papandreou, @ljharb)
* [`no-unsafe`][] rule ([#1831][], [#1830][] @sergei-startsev)
* [`no-will-update-set-state`][]: Account for `UNSAFE_` methods ([#1845][], [#1844][] @alexzherdev)

### Fixed
* [`no-typos`][]: Fix static propTypes handling ([#1827][], [#1677][] @alexzherdev)
* [`destructuring-assignment`][]: Allow LHS ([#1825][], [#1728][] @alexzherdev)
* [`no-unused-prop-types`][]: Fix crash when encountering mixed union and intersection flow types ([#1806][] @yannickcr)

### Changed
* Typo fixes in [`jsx-no-target-blank`][] ([#1805][] @ferhatelmas))

[7.10.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.9.1...v7.10.0
[#1845]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1845
[#1844]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1844
[#1843]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1843
[#1831]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1831
[#1830]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1830
[#1827]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1827
[#1825]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1825
[#1806]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1806
[#1805]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1805
[#1728]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1728
[#1677]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1677

## [7.9.1] - 2018-06-03
* Nothing was fixed; this is a republish with some updated deps. ([#1804][] @ljharb)

[7.9.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.9.0...v7.9.1
[#1804]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1804

## [7.9.0] - 2018-06-03
### Added
* Add [`jsx-props-no-multi-spaces`][] rule ([#1755][] @ThiefMaster)
* Add `first` option to [`jsx-indent-props`][] ([#398][] @ThiefMaster)
* Add `enforceDynamicLinks` option to [`jsx-no-target-blank`][] ([#1737][] @kenearley)

### Fixed
* Fix static lifecycle methods validation in [`sort-comp`][] ([#1793][] @lynxtaa)
* Fix crash in [`no-typos`][] when encountering anonymous react imports ([#1796][] @jsg2021)
* Fix ESLint 3 support ([#1779][])

### Changed
* Documentation improvements ([#1794][] @lencioni)
* Update Travis CI configuration to test on multiple ESLint verions

[7.9.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.8.2...v7.9.0
[#1755]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1755
[#398]: https://github.com/jsx-eslint/eslint-plugin-react/issues/398
[#1737]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1737
[#1793]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1793
[#1796]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1796
[#1779]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1779
[#1794]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1794

## [7.8.2] - 2018-05-13
### Fixed
* Fix crash in [`boolean-prop-naming`][] when encountering a required shape prop type ([#1791][] @pcorpet)

[7.8.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.8.1...v7.8.2
[#1791]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1791

## [7.8.1] - 2018-05-12
### Fixed
* Fix crash in [`no-deprecated`][] when encountering a class constructor ([#1785][] @taddei)

[7.8.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.8.0...v7.8.1
[#1785]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1785

## [7.8.0] - 2018-05-11
### Added
* Add support for fragments to [`react-in-jsx-scope`][] ([#1758][])
* Add support for Flow generic PropType to [`require-default-props`][] ([#1724][] @Miziak)
* Add component whitelist option to [`forbid-component-props`][] ([#1732][] @ThiefMaster)
* Add support for React 16.3 lifecycle methods to [`no-unused-prop-types`][] ([#1681][] @bvaughn)
* Add support for React 16.3 lifecycle methods to [`sort-comp`][] ([#1767][] @joe-denea)
* Add support for React 16.3 lifecycle methods to [`no-typos`][]
* Add support for `prevState` and `nextState` to [`no-unused-state`][] ([#1759][])
* Add warnings for `componentWillMount`, `componentWillReceiveProps` and `componentWillUpdate` lifecycle methods in [`no-deprecated`][] ([#1750][] @sergei-startsev)

### Fixed
* Fix [`no-typos`][] false positive on custom `PropType` classes ([#1389][] @brettdh)
* Fix [`boolean-prop-naming`][] to handle required props ([#1389][] @louisscruz)
* Fix [`jsx-curly-brace-presence`][] to allow whitespace JSX container ([#1717][] @sharmilajesupaul)
* Fix [`jsx-no-bind`][] to handle ternary conditions ([#1722][] @gwenaellarmet)

### Changed
* Documentation improvements ([#1699][] @ronanmathew, [#1743][] @ybiquitous, [#1753][] @awthwathje, [#1783][] @chentsulin, [#1703][] @ferhatelmas)

[7.8.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.7.0...v7.8.0
[#1758]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1758
[#1724]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1724
[#1732]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1732
[#1681]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1681
[#1767]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1767
[#1759]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1759
[#1750]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1750
[#1389]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1389
[#1717]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1717
[#1722]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1722
[#1699]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1699
[#1743]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1743
[#1753]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1753
[#1783]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1783
[#1703]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1703

## [7.7.0] - 2018-02-19
### Added
* [`forbid-foreign-prop-types`][]: add `allowInPropTypes` option ([#1655][] @iansu)
* Add [`jsx-max-depth`][] rule ([#1260][] @chriswong)

### Fixed
* [`no-access-state-in-setstate`][]: Exclude references to this.state in setState callback ([#1610][] @pfhayes)
* [`no-danger-with-children`][]: prevent infinite loop ([#1571][] @ljharb)
* [`sort-prop-types`][]: Fix sortShapeProp when shape is not an object literal ([#1669][] @justinanastos)
* [`jsx-child-element-spacing`][]: fix error location ([#1666][] @pfhayes)
* [`no-unused-prop-types`][]: fix for createClass ([#1675][] @yuri-sakharov)
* [`prop-types`][]: include nextProps checking in shouldComponentUpdate ([#1690][] @amerryma)
* [`jsx-curly-spacing`][]: refactor to fix start and end-braces in a single pass ([#1414][] @s-h-a-d-o-w)

### Changed
* [`jsx-child-element-spacing`][]: add missing docs ([#1665][] @pfhayes); fix docs ([#1670][] @SammyM)

[7.7.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.6.1...v7.7.0
[#1690]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1690
[#1675]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1675
[#1670]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1670
[#1669]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1669
[#1666]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1666
[#1665]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1665
[#1655]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1655
[#1610]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1610
[#1414]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1414
[#1260]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1260
[#1571]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1571

## [7.6.1] - 2018-01-28
### Fixed
* Flow: fix crash in [`prop-types`][] with recursive type annotations ([#1653][] @jetpacmonkey)
* Fix [`no-unknown-property`][] to properly recognize `crossOrigin` instead of `crossorigin`, and allow it on `link` tags. ([#1659][] @jzDev)
* Fix [`no-access-state-in-setstate`][] to handle object spread ([#1657][] @ljharb)

[7.6.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.6.0...v7.6.1
[#1659]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1659
[#1657]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1657
[#1653]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1653

## [7.6.0] - 2018-01-25
### Added
* Add [`forbid-dom-props`][] rule ([#1562][] @davazp)
* Add [`jsx-child-element-spacing`][] rule ([#1515][] @pfhayes)
* Add [`no-this-in-sfc`][] rule ([#1435][] @jomasti)
* Add [`jsx-sort-default-props`][] rule ([#281][] @b0gok)
* Add `message` option to [`boolean-prop-naming`][] ([#1588][] @louisscruz)
* Add `beforeClosing` option to [`jsx-tag-spacing`][] ([#1396][] @cjskillingstad)
* Add `instance-methods` and `instance-variables` to [`sort-comp`][] ([#599][] @RDGthree)
* Add `propWrapperFunctions` support for [`boolean-prop-naming`][] ([#1478][] @jomasti)
* Add warning for `React.addons.TestUtils` in [`no-deprecated`][] ([#1644][] @nirnaor)
* Add URL to rule documentation to the rules metadata ([#1635][] @Arcanemagus)

### Fixed
* Fix crashes in [`no-access-state-in-setstate`][] ([#1559][] @jomasti, [#1611][] @pfhayes)
* Fix crash in [`require-optimization`][] when encountering arrays with empty items as values in object ([#1621][] @kamataryo)
* Fix crash in [`no-unused-prop-types`][] when passing an empty function as a PropType ([#1542][] [#1581][] @kevinzwhuang)
* Fix crash in [`no-typos`][] when using `PropType.shape` without arguments ([#1471][] @mrichmond)
* Fix crash when using Unions in flow propTypes ([#1468][] @justinanastos)
* Fix missing meta in [`jsx-tag-spacing`][] ([#1650][] @flyerhzm)
* Fix [`no-unused-state`][] to detect usage of `this.state` as an object ([#1572][])
* Fix [`no-access-state-in-setstate`][] to detect when the `state` variable is destructured from `this.state` ([#1597][] @jaaberg)
* Fix [`jsx-no-literals`][] to correctly find string literals part of BinaryExpressions ([#1511][] @jaaberg)
* Fix [`no-typos`][] false positive on custom propTypes with isRequired ([#1607][] @lfades)
* Fix [`prop-types`][] to check for `nextProps` in `componentWillReceiveProps` ([#1636][] @xjmdoo)
* Fix [`no-unknown-property`][] to not pascal-casing `crossorigin` attribute and only allow it on script/img/video ([#1642][] @ljharb)

### Changed
* Improve [`jsx-wrap-multilines`][] auto fix ([#1576][] @sharmilajesupaul)
* Export `defaultConfig` from [`sort-comp`][] rule for programmatic use ([#1578][] @Andarist)
* Documentation improvements ([#1552][] @TSMMark, [#1566][] @lukeapage, [#1624][] @alexilyaev, @ljharb)
* Update dependencies (@ljharb)

[7.6.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.5.1...v7.6.0
[#1562]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1562
[#1515]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1515
[#1435]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1435
[#281]: https://github.com/jsx-eslint/eslint-plugin-react/issues/281
[#1588]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1588
[#1396]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1396
[#599]: https://github.com/jsx-eslint/eslint-plugin-react/issues/599
[#1478]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1478
[#1644]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1644
[#1635]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1635
[#1559]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1559
[#1611]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1611
[#1621]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1621
[#1542]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1542
[#1581]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1581
[#1471]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1471
[#1468]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1468
[#1650]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1650
[#1572]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1572
[#1597]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1597
[#1511]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1511
[#1607]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1607
[#1636]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1636
[#1642]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1642
[#1576]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1576
[#1578]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1578
[#1552]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1552
[#1566]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1566
[#1624]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1624

## [7.5.1] - 2017-11-19
### Fixed
* Fix [`jsx-no-bind`][] crash ([#1543][] @jomasti)
* Fix [`no-unused-prop-types`][] crash ([#1542][] @jomasti)

### Changed
* Documentation improvements ([#1546][] @jseminck)

[7.5.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.5.0...v7.5.1
[#1543]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1543
[#1542]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1542
[#1546]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1546

## [7.5.0] - 2017-11-18
### Added
* Add [`jsx-one-expression-per-line`][] rule ([#1497][] @TSMMark)
* Add [`destructuring-assignment`][] rule ([#1462][] @DianaSuvorova)
* Add [`no-access-state-in-setstate`][] rule ([#1374][] @jaaberg)
* Add [`button-has-type`][] rule ([#1525][] @Hypnosphi)
* Add warnings for `React.DOM` factories in [`no-deprecated`][] ([#1530][] @backjo)
* Add `sortShapeProp` option to [`sort-prop-types`][] ([#1476][] @jomasti)
* Add `parens-new-line` option to [`jsx-wrap-multilines`][] ([#1475][] @jomasti)
* Add `checkContextTypes` and `checkChildContextTypes` options to [`forbid-prop-types`][] ([#1533][] @jomasti)
* Add `forbidDefaultForRequired ` option to [`require-default-props`][] ([#1524][] @jomasti)
* Add new nodes support to [`jsx-wrap-multilines`][] ([#1384][] @evgeny-petukhov)

### Fixed
* Fix [`jsx-curly-brace-presence`][] auto fix by bailing out when some chars exist ([#1479][] [#1449][] @jackyho112)
* Fix [`boolean-prop-naming`][] crash with Object spread ([#1485][] @track0x1)
* Fix [`no-unused-state`][] to correctly handle arrow function class method ([#1363][] @jackyho112)
* Fix incompatibility with [`typescript-eslint-parser`](https://github.com/eslint/typescript-eslint-parser) ([#1496][] @timothykang)
* Fix [`jsx-no-bind`][] to only warn for props and account for variable declaration ([#1444][] [#1395][] [#1417][] @jackyho112)
* Fix [`no-unused-prop-types`][] to handle props usage in custom prop validators ([#1518][] @petersendidit)
* Fix [`prefer-stateless-function`][] to account for `contextTypes` and `defaultProps` ([#1521][] @jomasti)
* Fix [`jsx-no-comment-textnodes`][] to not warn when using two slashes via html entities at the beginning of a literal ([#1517][] @jomasti)
* Fix [`default-props-match-prop-types`][] crash ([#1499][] @jomasti)
* Fix [`no-unused-prop-types`][] to handle props used in the `setState` update callback ([#1507][] @petersendidit)
* Fix alignment bug in [`jsx-indent`][] ([#1246][] @jseminck)

### Changed
* Documentation improvements ([#1438][] @jseminck, [#1464][] @AlaaAttya, [#1494][] @piperchester, [#1467][] @felicio, [#1512][] @adam-golab)
* Code refactoring ([#1423][] [#1398][] @jseminck, [#1500][] [#1514][] @Aladdin-ADD, [#1502][] @SimenB, [#1508][] [#1526][] @jomasti, @ljharb)
* Update dependencies ([#1450][] @leebyron, @ljharb)

[7.5.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.4.0...v7.5.0
[#1497]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1497
[#1462]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1462
[#1374]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1374
[#1525]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1525
[#1530]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1530
[#1476]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1476
[#1475]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1475
[#1533]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1533
[#1524]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1524
[#1384]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1384
[#1479]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1479
[#1449]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1449
[#1485]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1485
[#1363]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1363
[#1496]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1496
[#1444]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1444
[#1395]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1395
[#1417]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1417
[#1518]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1518
[#1521]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1521
[#1517]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1517
[#1499]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1499
[#1507]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1507
[#1246]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1246
[#1438]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1438
[#1464]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1464
[#1494]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1494
[#1467]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1467
[#1512]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1512
[#1423]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1423
[#1500]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1500
[#1514]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1514
[#1502]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1502
[#1508]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1508
[#1526]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1526
[#1398]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1398
[#1450]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1450

## [7.4.0] - 2017-09-24
### Added
* Add Flow 0.53 support ([#1376][] @jseminck)
* Add [`jsx-curly-brace-presence`][] rule ([#1310][] @jackyho112)
* Add support for Flow IntersectionTypeAnnotation to [`prop-types`][] and [`no-unused-prop-types`][] ([#1364][] [#1323][] @jseminck)
* Add support for Flow TypedArgument to [`no-unused-prop-types`][] ([#1412][] @jseminck)
* Add support for Flow ClassExpressions to [`prop-types`][] ([#1400][] @jseminck)
* Add support for Flow read-only props to [`no-unused-prop-types`][] ([#1388][] @jseminck)
* Add more tests for [`prop-types`][] and [`no-unused-prop-types`][] ([#1381][] @DianaSuvorova)
* Add support for increment and decrement operations to [`no-direct-mutation-state`][] ([#1386][] @zpao)

### Fixed
* Fix [`no-unused-state`][] to ignore computed property keys ([#1361][] @jackyho112)
* Fix [`no-typos`][] crash ([#1406][] @jseminck)
* Fix [`boolean-prop-naming`][] crash ([#1409][] @EvHaus)
* Fix [`prop-types`][] and [`no-unused-prop-types`][] crash with IntersectionTypeAnnotation ([#1413][] @jseminck)

### Changed
* Documentation improvements ([#1392][] @xcatliu, [#1403][] @piperchester, [#1432][] @jneuendorf)

[7.4.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.3.0...v7.4.0
[#1376]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1376
[#1310]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1310
[#1364]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1364
[#1323]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1323
[#1412]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1412
[#1400]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1400
[#1388]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1388
[#1381]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1381
[#1361]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1361
[#1406]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1406
[#1409]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1409
[#1392]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1392
[#1403]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1403
[#1386]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1386
[#1413]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1413
[#1432]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1432

## [7.3.0] - 2017-08-21
### Added
* Add checks for `propTypes`, `contextTypes` and `childContextTypes` to [`no-typos`][] ([#213][] @DianaSuvorova)

### Fixed
* Fix [`boolean-prop-naming`][] crash ([#1369][] @EvHaus)
* Fix [`no-typos`][] crash ([#1353][] @jseminck)
* Fix [`require-default-props`][] stopping when it finds a component without props ([#1380][] @brgibson)
* Fix [`no-direct-mutation-state`][] detection with nested components ([#1382][])

### Changed
* Documentation improvements ([#1383][] @mjomble)

[7.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.2.1...v7.3.0
[#213]: https://github.com/jsx-eslint/eslint-plugin-react/issues/213
[#1369]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1369
[#1353]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1353
[#1380]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1380
[#1382]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1382
[#1383]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1383

## [7.2.1] - 2017-08-14
### Fixed
* Fix [`forbid-prop-types`][] crash on identifiers ([#1352][] @ljharb)
* Fix [`boolean-prop-naming`][] crash with propTypes wrapper ([#1354][] @dustinsoftware)
* Fix [`prop-types`][] false positive with local variable `props` ([#1288][] @DianaSuvorova)
* Fix wrapped propTypes detection ([#1366][])

### Changed
* Documentation improvements ([#1123][] @penx)

[7.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.2.0...v7.2.1
[#1352]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1352
[#1354]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1354
[#1288]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1288
[#1366]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1366
[#1123]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1123

## [7.2.0] - 2017-08-09
### Added
* Add [`no-unused-state`][] rule ([#1103][] @wbinnssmith)
* Add [`boolean-prop-naming`][] rule ([#1264][] @EvHaus)
* Add [`no-typos`][] rule ([#1189][] @jseminck, [#1294][] @haridusenadeera)
* Add auto fix for [`jsx-sort-props`][] ([#1273][] @Overload119)
* Add `getters` and `setters` groups to [`sort-comp`][] ([#100][] @RDGthree)
* Add `noStrings` option to [`jsx-no-literals`][] ([#1202][] @deecewan)
* Add inverse option for `always`/`never` to [`jsx-boolean-value`][] ([#1249][] @ljharb)

### Fixed
* Fix [`no-direct-mutation-state`][] to disallow `this.state` mutation in constructor ([#832][] @burabure)
* Fix [`jsx-no-target-blank`][] crash on empty `rel` attribute ([#1269][] @dustinsoftware)
* Fix [`sort-comp`][] component detection with `ClassExpression` ([#1076][] @webOS101)
* Fix [`no-unused-prop-types`][] detection with async class properties and methods ([#1053][] @benstepp)
* Fix [`void-dom-elements-no-children`][] crash ([#1226][] @kokobeware)
* Fix [`no-danger-with-children`][] to ignore line breaks ([#1262][])
* Fix [`no-danger-with-children`][] crash with undefined ([#1287][])
* Fix [`jsx-no-target-blank`][] crash ([#1296][] @jseminck)
* Fix [`no-unused-prop-types`][] to no longer ignore components with no used props ([#1303][] @DianaSuvorova)
* Fix [`jsx-no-duplicate-props`][] crash ([#969][] @marcelmokos)
* Fix [`jsx-no-literals`][] false positives ([#1301][] @davidyorr)
* Fix [`no-find-dom-node`][] detection with named imports ([#785][] @Hypnosphi)
* Fix proTypes-related rules detection with wrapped propTypes ([#1266][] @dustinsoftware)
* Fix [`no-unused-prop-types`][] detection with propTypes wrapped in a function ([#1253][] @dustinsoftware)
* Fix [`no-unused-prop-types`][] detection with destructured use of properties ([#816][] @DianaSuvorova)
* Fix [`no-unused-prop-types`][] detection with inline functions ([#1309][] @DianaSuvorova)
* Fix [`no-unused-prop-types`][] `skipShapeProps` option with Flow annotations ([#1335][] @DianaSuvorova)
* Fix [`jsx-curly-spacing`][] schema incompatibility with ESLint 4.2.0 ([#1290][] @jseminck)

### Changed
* Documentation improvements ([#1261][] @mminer, [#1005][] @yooungt13, [#1289][] @konekoya, [#1308][] @xcatliu, [#1306][] @egberts, [#1329][] [#1344][] @DianaSuvorova)
* ES6-ify codebase ([#1274][] [#1277][] [#1281][] @dfilipidisz)
* Code refactoring (@ljharb)
* Update Travis CI and AppVeyor CI configurations (@lencioni)

[7.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.1.0...v7.2.0
[#1103]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1103
[#1273]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1273
[#1264]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1264
[#1189]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1189
[#1294]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1294
[#100]: https://github.com/jsx-eslint/eslint-plugin-react/issues/100
[#1202]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1202
[#1249]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1249
[#832]: https://github.com/jsx-eslint/eslint-plugin-react/issues/832
[#1269]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1269
[#1076]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1076
[#1053]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1053
[#1226]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1226
[#1262]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1262
[#1287]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1287
[#1296]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1296
[#1303]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1303
[#969]: https://github.com/jsx-eslint/eslint-plugin-react/issues/969
[#1301]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1301
[#785]: https://github.com/jsx-eslint/eslint-plugin-react/issues/785
[#1266]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1266
[#1253]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1253
[#816]: https://github.com/jsx-eslint/eslint-plugin-react/issues/816
[#1309]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1309
[#1261]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1261
[#1005]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1005
[#1289]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1289
[#1308]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1308
[#1306]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1306
[#1329]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1329
[#1274]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1274
[#1277]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1277
[#1281]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1281
[#1335]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1335
[#1344]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1344
[#1290]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1290

## [7.1.0] - 2017-06-13
### Added
* Add [`default-props-match-prop-types`][] rule ([#1022][] @webOS101)
* Add [`no-redundant-should-component-update`][] rule ([#985][] @jomasti)
* Add [`jsx-closing-tag-location`][] rule ([#1206][] @rsolomon)
* Add auto fix for [`jsx-max-props-per-line`][] ([#949][] @snowypowers)
* Add support for lifecycle methods with `nextProps`/`prevProps` in [`no-unused-prop-types`][] ([#1213][] @jseminck)
* Add Flow SuperTypeParameters support to [`prop-types`][] ([#1236][] @gpeal)
* Add `children` option to [`jsx-curly-spacing`][] ([#857][] @fatfisz)

### Fixed
* Fix [`prefer-stateless-function`][] `ignorePureComponents` option when using class expressions ([#1122][] @dreid)
* Fix [`void-dom-elements-no-children`][] crash ([#1195][] @oliviertassinari)
* Fix [`require-default-props`][] quoted `defaultProps` detection ([#1201][])
* Fix [`jsx-sort-props`][] bug with `ignoreCase` and `callbacksLast` options set to `true` ([#1175][] @jseminck)
* Fix [`no-unused-prop-types`][] false positive ([#1183][] [#1135][] @jseminck)
* Fix [`jsx-no-target-blank`][] to not issue errors for non-external URLs ([#1216][] @gfx)
* Fix [`prop-types`][] quoted Flow types detection ([#1132][] @ethanjgoldberg)
* Fix [`no-array-index-key`][] crash with `key` without value ([#1242][] @jseminck)

### Changed
* Set ESLint 4.0.0 as valid peerDependency
* Dead code removal ([#1227][] @jseminck)
* Update dependencies (@ljharb)
* Documentation improvements ([#1071][] @adnasa, [#1199][] @preco21, [#1222][] @alexilyaev, [#1231][] @vonovak, [#1239][] @webOS101, [#1241][] @102)

[7.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.0.1...v7.1.0
[#1022]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1022
[#949]: https://github.com/jsx-eslint/eslint-plugin-react/pull/949
[#985]: https://github.com/jsx-eslint/eslint-plugin-react/issues/985
[#1213]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1213
[#1236]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1236
[#1206]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1206
[#857]: https://github.com/jsx-eslint/eslint-plugin-react/issues/857
[#1122]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1122
[#1195]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1195
[#1201]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1201
[#1175]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1175
[#1183]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1183
[#1135]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1135
[#1216]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1216
[#1132]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1132
[#1242]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1242
[#1227]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1227
[#1071]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1071
[#1199]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1199
[#1222]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1222
[#1231]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1231
[#1239]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1239
[#1241]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1241

## [7.0.1] - 2017-05-13
### Fixed
* Fix [`jsx-curly-spacing`][] `allowMultiline` option being undefined in some cases ([#1179][] @fatfisz)
* Fix [`jsx-curly-spacing`][] newline with object literals bug ([#1180][] @fatfisz)
* Fix [`prop-types`][] to not mark class static function as valid propTypes definition ([#1174][])
* Fix [`prop-types`][] crash with Flow spread operator ([#1178][])
* Fix [`void-dom-elements-no-children`][] crash on faulty `createElement` detection ([#1101][])
* Fix [`require-default-props`][] error message for quoted props ([#1161][])

### Changed
* Update dependencies
* Documentation improvements ([#1173][] @luftywiranda13, [#1192][] @markus-willems)

[7.0.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v7.0.0...v7.0.1
[#1179]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1179
[#1180]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1180
[#1174]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1174
[#1178]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1178
[#1101]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1101
[#1161]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1161
[#1173]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1173
[#1192]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1192

## [7.0.0] - 2017-05-06
### Added
* Add [`no-will-update-set-state`][] rule ([#1139][] @ManThursday)
* Add import and destructuring support to [`no-deprecated`][]
* Add `reservedFirst` option to [`jsx-sort-props`][] ([#1134][] @MatthewHerbst)

### Breaking
* Update rules for React 15.5.0:
  * Add warnings for `React.PropTypes` and `React.createClass` in [`no-deprecated`][] ([#1148][] @Calyhre)
  * Update `createClass` component factory to `createReactClass`. This is used for React component detection, if you still using `React.createClass` use the [shared settings](README.md#configuration) to specify `createClass` as component factory
* Drop Node.js < 4 support ([#1038][] @ljharb)
* Add [`no-danger-with-children`][] rule to recommended rules ([#748][] @ljharb)
* Add [`no-string-refs`][] rule to recommended rules ([#749][] @ljharb)
* Add [`jsx-key`][] rule to recommended rules ([#750][] @ljharb)
* Add [`jsx-no-comment-textnodes`][] rule to recommended rules ([#751][] @ljharb)
* Add [`jsx-no-target-blank`][] rule to recommended rules ([#752][] @ljharb)
* Add [`no-unescaped-entities`][] rule to recommended rules ([#841][] @ljharb)
* Add [`no-children-prop`][] rule to recommended rules ([#842][] @ljharb)
* Remove deprecated [`wrap-multilines`][] rule, use [`jsx-wrap-multilines`][] instead
* Remove deprecated [`no-comment-textnodes`][] rule, use [`jsx-no-comment-textnodes`][] instead
* Remove deprecated [`require-extension`][] rule, use the [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) [`extensions`](https://github.com/benmosher/eslint-plugin-import/blob/master/docs/rules/extensions.md) rule instead
* Deprecate [`jsx-space-before-closing`][] rule, use the [`jsx-tag-spacing`][] rule instead. [`jsx-space-before-closing`][] still works but will trigger a warning ([#1070][] @afairb)
* [`jsx-first-prop-new-line`][] default is now `multiline-multiprop` ([#802][] @kokarn)
* [`jsx-wrap-multilines`][] now checks arrow functions without block body. It can be deactivated in [rule options](docs/rules/jsx-wrap-multilines.md#rule-details) ([#790][] @ColCh)
* [`jsx-no-undef`][] will not check the global scope by default. You can force it with the [`allowGlobals`](docs/rules/jsx-no-undef.md#allowglobals) option ([#1013][] @jomasti)

### Fixed
* Fix [`no-unused-prop-types`][] false positive with `nextProps` ([#1079][] @Kerumen)
* Fix [`prefer-stateless-function`][] to not warn on classes with decorators ([#1034][] @benstepp)

### Changed
* Update dependencies ([#1119][] @danez)
* Documentation improvements ([#1121][] @omerzach, [#1130][] @dreid, [#1131][] @shoesandsocks, [#1149][] @Adzz, [#1151][] @MatthewHerbst, [#1167][] @Slumber86)

[7.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.10.3...v7.0.0
[#1134]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1134
[#1038]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1038
[#802]: https://github.com/jsx-eslint/eslint-plugin-react/pull/802
[#790]: https://github.com/jsx-eslint/eslint-plugin-react/issues/790
[#1013]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1013
[#1070]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1070
[#748]: https://github.com/jsx-eslint/eslint-plugin-react/issues/748
[#749]: https://github.com/jsx-eslint/eslint-plugin-react/issues/749
[#750]: https://github.com/jsx-eslint/eslint-plugin-react/issues/750
[#751]: https://github.com/jsx-eslint/eslint-plugin-react/issues/751
[#752]: https://github.com/jsx-eslint/eslint-plugin-react/issues/752
[#841]: https://github.com/jsx-eslint/eslint-plugin-react/issues/841
[#842]: https://github.com/jsx-eslint/eslint-plugin-react/issues/842
[#1139]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1139
[#1148]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1148
[#1079]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1079
[#1034]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1034
[#1119]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1119
[#1121]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1121
[#1130]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1130
[#1131]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1131
[#1149]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1149
[#1151]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1151
[#1167]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1167

## [6.10.3] - 2017-03-20
### Fixed
* Revert [#1057][] due to issues with [`jsx-indent`][] ([#1117][])

[6.10.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.10.2...v6.10.3

## [6.10.2] - 2017-03-19
### Fixed
* Fix [`jsx-indent`][] indentation calculation with nested JSX ([#1117][])

[6.10.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.10.1...v6.10.2
[#1117]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1117

## [6.10.1] - 2017-03-19
### Fixed
* Fix [`jsx-indent`][] auto fix with tabs ([#1057][] @kentcdodds @webOS101)
* Fix [`jsx-indent`][] crash ([#1061][] @iancmyers)
* Fix [`void-dom-elements-no-children`][] crash and fix it to only checks for a createElement call from
React ([#1073][] @jomasti)
* Fix component detection that caused a false positive in [`no-multi-comp`][] ([#1088][] @benstepp)

[6.10.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.10.0...v6.10.1
[#1057]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1057
[#1061]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1061
[#1073]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1073
[#1088]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1088

## [6.10.0] - 2017-02-16
### Added
* Add [`forbid-foreign-prop-types`][] rule ([#696][] @iancmyers)
* Add [`void-dom-elements-no-children`][] rule ([#709][] @lencioni)
* Add [`forbid-elements`][] rule ([#887][] @kentor)
* Add `noSortAlphabetically` option to [`jsx-sort-props`][] ([#541][] [#786][] @markus101)
* Add `when` option to [`jsx-max-props-per-line`][] ([#878][] @kentor)
* Add support for `nextProps` to [`prop-types`][] ([#814][])

### Fixed
* Fix [`require-default-props`][] crash ([#1029][])
* Fix [`require-default-props`][] rule when using Flow type from assignment ([#1043][] @wyze @CarlRosell)
* Fix [`style-prop-object`][] to not warn with explicit `null` or `undefined` ([#812][] @ljharb)
* Fix [`no-unused-prop-types`][] props detection in stateless components ([#885][] @BarryThePenguin)
* Fix [`display-name`] false positive with `document.createElement` ([#996][] @jomasti)
* Fix ESLint 2 compatibility (@ljharb)

### Changed
* Tests improvements (@ljharb)
* Documentation improvements ([#958][] @Jorundur, [#1010][] @amilajack, [#1041][] @EvNaverniouk, [#1050][] @lencioni, [#1062][] @dguo)

[6.10.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.9.0...v6.10.0
[#696]: https://github.com/jsx-eslint/eslint-plugin-react/issues/696
[#709]: https://github.com/jsx-eslint/eslint-plugin-react/issues/709
[#887]: https://github.com/jsx-eslint/eslint-plugin-react/issues/887
[#541]: https://github.com/jsx-eslint/eslint-plugin-react/issues/541
[#786]: https://github.com/jsx-eslint/eslint-plugin-react/issues/786
[#878]: https://github.com/jsx-eslint/eslint-plugin-react/issues/878
[#814]: https://github.com/jsx-eslint/eslint-plugin-react/issues/814
[#1029]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1029
[#1043]: https://github.com/jsx-eslint/eslint-plugin-react/issues/1043
[#812]: https://github.com/jsx-eslint/eslint-plugin-react/issues/812
[#885]: https://github.com/jsx-eslint/eslint-plugin-react/issues/885
[#996]: https://github.com/jsx-eslint/eslint-plugin-react/issues/996
[#958]: https://github.com/jsx-eslint/eslint-plugin-react/pull/958
[#1010]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1010
[#1041]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1041
[#1050]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1050
[#1062]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1062

## [6.9.0] - 2017-01-08
### Added
* Add support for variable reference to [`sort-prop-types`][] ([#622][])

### Fixed
* Fix Node.js 0.10 support ([#1000][] @ljharb)
* Fix [`prop-types`][] to correctly assign props to components ([#991][])

### Changed
* Documentation improvements ([#995][] @rutsky)

[6.9.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.8.0...v6.9.0
[#622]: https://github.com/jsx-eslint/eslint-plugin-react/issues/622
[#1000]: https://github.com/jsx-eslint/eslint-plugin-react/pull/1000
[#991]: https://github.com/jsx-eslint/eslint-plugin-react/issues/991
[#995]: https://github.com/jsx-eslint/eslint-plugin-react/pull/995

## [6.8.0] - 2016-12-05
### Added
* Add [`no-array-index-key`][] rule ([#978][] @lencioni)
* Add [`require-default-props`][] rule ([#528][]  @vitorbal)
* Add support for flow variance syntax to [`prop-types`][] ([#961][] @ajhyndman)

### Fixed
* Fix [`jsx-indent`][] with multiline jsx in ternaries ([#966][])
* Fix component detection to ignore async functions ([#989][] @taion)
* Fix [`jsx-curly-spacing`][] autofix to not delete comments ([#648][])
* Fix auto-enabling of `eslint-plugin-react` in exported configurations ([#984][] @jamischarles)

### Changed
* Update dependencies
* Documentation improvements ([#960][] @evilebottnawi, [#973][] @JamesWatling, [#982][] @captbaritone)

[6.8.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.7.1...v6.8.0
[#978]: https://github.com/jsx-eslint/eslint-plugin-react/pull/978
[#528]: https://github.com/jsx-eslint/eslint-plugin-react/issues/528
[#961]: https://github.com/jsx-eslint/eslint-plugin-react/issues/961
[#966]: https://github.com/jsx-eslint/eslint-plugin-react/issues/966
[#989]: https://github.com/jsx-eslint/eslint-plugin-react/pull/989
[#648]: https://github.com/jsx-eslint/eslint-plugin-react/issues/648
[#984]: https://github.com/jsx-eslint/eslint-plugin-react/pull/984
[#960]: https://github.com/jsx-eslint/eslint-plugin-react/pull/960
[#973]: https://github.com/jsx-eslint/eslint-plugin-react/pull/973
[#982]: https://github.com/jsx-eslint/eslint-plugin-react/pull/982

## [6.7.1] - 2016-11-15
### Fixed
* Fix [`jsx-tag-spacing`][] crash when options object isn't passed ([#955][] @daltones)

[6.7.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.7.0...v6.7.1
[#955]: https://github.com/jsx-eslint/eslint-plugin-react/issues/955

## [6.7.0] - 2016-11-14
### Added
* Add [`jsx-tag-spacing`][] rule ([#693][] @Kovensky)

### Fixed
* Fix [`jsx-indent`][] for parenthesized ternaries ([#945][] @voxpelli)
* Fix [`jsx-indent`][] for multiline ternaries
* Fix [`jsx-indent`][] for arrays in jsx ([#947][])
* Fix [`no-danger-with-children`][] crash with spread on global variables ([#921][])
* Fix [`jsx-wrap-multilines`][] ternaries handling ([#916][])

### Changed
* Enable [`no-unused-prop-types`][] `skipShapeProps` option by default to limit false positive ([#953][] @everdimension)

[6.7.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.6.0...v6.7.0
[#693]: https://github.com/jsx-eslint/eslint-plugin-react/issues/693
[#945]: https://github.com/jsx-eslint/eslint-plugin-react/issues/945
[#947]: https://github.com/jsx-eslint/eslint-plugin-react/issues/947
[#921]: https://github.com/jsx-eslint/eslint-plugin-react/issues/921
[#916]: https://github.com/jsx-eslint/eslint-plugin-react/issues/916
[#953]: https://github.com/jsx-eslint/eslint-plugin-react/pull/953

## [6.6.0] - 2016-11-06
### Added
* Add [`jsx-first-prop-new-line`][] auto fix ([#886][] @snowypowers)

### Fixed
* Fix [`no-unused-prop-types`][] crash with destructured prop-types ([#938][])
* Fix [`jsx-indent`][] in multi-line conditional expressions ([#901][], [#907][])
* Fix [`sort-comp`][] bad error message if 2 methods in the same group must be moved ([#507][])

### Changed
* Documentation improvements ([#941][] @pwmckenna)

[6.6.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.5.0...v6.6.0
[#886]: https://github.com/jsx-eslint/eslint-plugin-react/pull/886
[#938]: https://github.com/jsx-eslint/eslint-plugin-react/issues/938
[#901]: https://github.com/jsx-eslint/eslint-plugin-react/issues/901
[#907]: https://github.com/jsx-eslint/eslint-plugin-react/issues/907
[#507]: https://github.com/jsx-eslint/eslint-plugin-react/issues/507
[#941]: https://github.com/jsx-eslint/eslint-plugin-react/pull/941

## [6.5.0] - 2016-11-01
### Added
* Add tab support to [`jsx-closing-bracket-location`][] auto fixer ([#909][] @arperry)
* Add tab and space support to [`jsx-indent`][] auto fixer ([#608][] @jayphelps)
* Add `multiline-multiprop` option to [`jsx-first-prop-new-line`][] ([#883][] @kentor)

### Fixed
* Fix [`forbid-component-props`][] crash with self reference JSX element ([#839][] @xeodou)
* Fix [`jsx-indent`][] to ignore lines starting by literals ([#900][])
* Fix [`no-set-state`][] to correctly detect `setState` in arrow functions ([#931][])

### Changed
* Update dependencies
* Add `deprecated` metadata to deprecated rules ([#911][] @randycoulman)
* Auto-enable `eslint-plugin-react` in exported configurations ([#925][] @MoOx)
* Documentation improvements ([#910][] @Wilfred, [#932][] @gnarf)

[6.5.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.4.1...v6.5.0
[#909]: https://github.com/jsx-eslint/eslint-plugin-react/pull/909
[#608]: https://github.com/jsx-eslint/eslint-plugin-react/pull/608
[#883]: https://github.com/jsx-eslint/eslint-plugin-react/pull/883
[#839]: https://github.com/jsx-eslint/eslint-plugin-react/pull/839
[#900]: https://github.com/jsx-eslint/eslint-plugin-react/issues/900
[#931]: https://github.com/jsx-eslint/eslint-plugin-react/issues/931
[#911]: https://github.com/jsx-eslint/eslint-plugin-react/pull/911
[#925]: https://github.com/jsx-eslint/eslint-plugin-react/pull/925
[#910]: https://github.com/jsx-eslint/eslint-plugin-react/pull/910
[#932]: https://github.com/jsx-eslint/eslint-plugin-react/pull/932

## [6.4.1] - 2016-10-10
### Fixed
* Fix [`jsx-indent`][] for arrays ([#897][], [#898][])
* Fix [`jsx-indent`][] to allow multi-line logical expressions with one level of indent ([#896][])

[6.4.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.4.0...v6.4.1
[#897]: https://github.com/jsx-eslint/eslint-plugin-react/issues/897
[#898]: https://github.com/jsx-eslint/eslint-plugin-react/issues/898
[#896]: https://github.com/jsx-eslint/eslint-plugin-react/pull/896

## [6.4.0] - 2016-10-09
### Added
* Add `skipUndeclared` option to [`prop-types`][] ([#846][] @pfhayes)

### Fixed
* Fix [`jsx-no-bind`][] crash on arrow functions ([#854][])
* Fix [`display-name`][] false negative on es6-style method in `React.createClass` ([#852][])
* Fix [`prefer-stateless-function`][] to allow components with `childContextTypes` ([#853][])
* Fix [`no-children-prop`][] spread support ([#862][] @randycoulman)
* Fix [`no-unused-prop-types`][] to ignore validation when spread is used ([#840][])
* Fix [`jsx-closing-bracket-location`][] for multi-line prop ([#889][])
* Fix [`jsx-indent`][] in multi-line function calls ([#895][])
* Fix [`jsx-indent`][] in multi-line logical expressions ([#540][])

### Changed
* Update dependencies
* Documentation improvements ([#860][] @fson, [#863][] @corydolphin, [#830][] @eelyafi, [#876][] @manovotny, [#877][] @gaearon)

[6.4.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.3.0...v6.4.0
[#846]: https://github.com/jsx-eslint/eslint-plugin-react/pull/846
[#854]: https://github.com/jsx-eslint/eslint-plugin-react/issues/854
[#852]: https://github.com/jsx-eslint/eslint-plugin-react/issues/852
[#853]: https://github.com/jsx-eslint/eslint-plugin-react/issues/853
[#862]: https://github.com/jsx-eslint/eslint-plugin-react/pull/862
[#840]: https://github.com/jsx-eslint/eslint-plugin-react/issues/840
[#889]: https://github.com/jsx-eslint/eslint-plugin-react/issues/889
[#895]: https://github.com/jsx-eslint/eslint-plugin-react/issues/895
[#540]: https://github.com/jsx-eslint/eslint-plugin-react/issues/540
[#860]: https://github.com/jsx-eslint/eslint-plugin-react/pull/860
[#863]: https://github.com/jsx-eslint/eslint-plugin-react/pull/863
[#830]: https://github.com/jsx-eslint/eslint-plugin-react/pull/830
[#876]: https://github.com/jsx-eslint/eslint-plugin-react/pull/876
[#877]: https://github.com/jsx-eslint/eslint-plugin-react/pull/877

## [6.3.0] - 2016-09-20
### Added
* Add [`no-children-prop`][] rule ([#720][] @benstepp)
* Add [`no-unescaped-entities`][] rule ([#681][] @pfhayes)
* Add JSXExpressionContainer support to [`jsx-indent`][] rule ([#838][] @eelyafi)

### Fixed
* Fix [`style-prop-object`][] crash ([#834][])
* Fix [`style-prop-object`][] false positive on computed properties ([#820][])
* Fix [`style-prop-object`][] to deal with null and spread props that can't be resolved ([#809][] [#812][] @petersendidit)

[6.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.2.2...v6.3.0
[#720]: https://github.com/jsx-eslint/eslint-plugin-react/issues/720
[#681]: https://github.com/jsx-eslint/eslint-plugin-react/pull/681
[#838]: https://github.com/jsx-eslint/eslint-plugin-react/pull/838
[#834]: https://github.com/jsx-eslint/eslint-plugin-react/issues/834
[#820]: https://github.com/jsx-eslint/eslint-plugin-react/issues/820
[#809]: https://github.com/jsx-eslint/eslint-plugin-react/issues/809
[#812]: https://github.com/jsx-eslint/eslint-plugin-react/issues/812

## [6.2.2] - 2016-09-15
### Fixed
* Fix [`no-unused-prop-types`][] crash ([#825][] @EvNaverniouk)
* Fix [`jsx-no-target-blank`][] crash ([#821][])

[6.2.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.2.1...v6.2.2
[#821]: https://github.com/jsx-eslint/eslint-plugin-react/issues/821
[#825]: https://github.com/jsx-eslint/eslint-plugin-react/pull/825

## [6.2.1] - 2016-09-13
### Fixed
* Fix false positive in [`no-unused-prop-types`][] ([#792][] @EvNaverniouk)
* Fix [`jsx-no-target-blank`][] to target only anchor elements ([#793][] @aduth)
* Fix [`jsx-no-target-blank`][] to be case insensitive [#796][] @dmnd)
* Fix [`jsx-uses-vars`][] shadowed variables handling ([#799][])

### Changed
* Update dependencies
* Documentation improvements (@ljharb, [#794][] @dougshamoo, [#813][] @AndiDog, [#815][] @chris-vaszauskas)

[6.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.2.0...v6.2.1
[#792]: https://github.com/jsx-eslint/eslint-plugin-react/pull/792
[#793]: https://github.com/jsx-eslint/eslint-plugin-react/pull/793
[#794]: https://github.com/jsx-eslint/eslint-plugin-react/pull/794
[#796]: https://github.com/jsx-eslint/eslint-plugin-react/pull/796
[#799]: https://github.com/jsx-eslint/eslint-plugin-react/issues/799
[#813]: https://github.com/jsx-eslint/eslint-plugin-react/pull/813
[#815]: https://github.com/jsx-eslint/eslint-plugin-react/pull/815

## [6.2.0] - 2016-08-28
### Added
* Add [`no-unused-prop-types`][] rule ([#226][] @EvNaverniouk)
* Add [`style-prop-object`][] rule ([#715][] @petersendidit)
* Add auto fix for [`self-closing-comp`][] ([#770][] @pl12133)
* Add support for `typeAnnotations` in [`sort-comp`][] ([#235][] @dozoisch)
* Add support for `PureComponent` in [`prefer-stateless-function`][] ([#781][] @tiemevanveen)

### Fixed
* Fix [`jsx-uses-vars`][] to work better with [`prefer-const`](https://eslint.org/docs/rules/prefer-const). You'll need to upgrade to ESLint 3.4.0 to completely fix the compatibility issue ([#716][])
* Fix [`require-render-return`][] crash ([#784][])
* Fix related components detection in [`prop-types`][] ([#735][])
* Fix component detection to ignore functions expression without a parent component

### Changed
* Update dependencies
* Documentation improvements (@lencioni)

[6.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.1.2...v6.2.0
[#226]: https://github.com/jsx-eslint/eslint-plugin-react/issues/226
[#715]: https://github.com/jsx-eslint/eslint-plugin-react/issues/715
[#770]: https://github.com/jsx-eslint/eslint-plugin-react/pull/770
[#235]: https://github.com/jsx-eslint/eslint-plugin-react/issues/235
[#781]: https://github.com/jsx-eslint/eslint-plugin-react/pull/781
[#716]: https://github.com/jsx-eslint/eslint-plugin-react/issues/716
[#784]: https://github.com/jsx-eslint/eslint-plugin-react/issues/784
[#735]: https://github.com/jsx-eslint/eslint-plugin-react/issues/735

## [6.1.2] - 2016-08-17
### Fixed
* Fix nested spread handling in [`no-danger-with-children`][] ([#771][] @petersendidit)

### Changed
* Documentation improvements

[6.1.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.1.1...v6.1.2
[#771]: https://github.com/jsx-eslint/eslint-plugin-react/issues/771

## [6.1.1] - 2016-08-16
### Fixed
* Fix [`prop-types`][] on annotated components ([#766][])
* Fix [`no-danger-with-children`][] spread support ([#767][] @petersendidit)

### Changed
* Documentation improvements ([#769][] @daltones)

[6.1.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.1.0...v6.1.1
[#766]: https://github.com/jsx-eslint/eslint-plugin-react/issues/766
[#767]: https://github.com/jsx-eslint/eslint-plugin-react/issues/767
[#769]: https://github.com/jsx-eslint/eslint-plugin-react/pull/769

## [6.1.0] - 2016-08-14
### Added
* Add `React.PureComponent` support ([#737][])
* Add [`forbid-component-props`][] rule ([#314][] @lencioni)
* Add [`no-danger-with-children`][] rule ([#710][] @petersendidit)
* Add pragma for `createClass` factory method ([#725][] @zurawiki)

### Fixed
* Fix Node.js 0.10 support ([#746][])
* Fix [`prop-types`][] on annotated components ([#729][])
* Fix [`require-optimization`][] test for function declaration ([#744][] @Tom910)
* Fix [`jsx-uses-vars`][] to handle nested object properties ([#761][] @yayalice)
* Fix rules metadata

### Changed
* Update dependencies
* Documentation improvements ([#759][] @embrown, [#703][] [#753][] @lencioni, [#739][] @ljharb, [#731][] @wKich, [#745][] @petersendidit, [#659][] @dguo)

[6.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v6.0.0...v6.1.0
[#737]: https://github.com/jsx-eslint/eslint-plugin-react/issues/737
[#710]: https://github.com/jsx-eslint/eslint-plugin-react/issues/710
[#725]: https://github.com/jsx-eslint/eslint-plugin-react/pull/725
[#746]: https://github.com/jsx-eslint/eslint-plugin-react/issues/746
[#729]: https://github.com/jsx-eslint/eslint-plugin-react/issues/729
[#744]: https://github.com/jsx-eslint/eslint-plugin-react/pull/744
[#761]: https://github.com/jsx-eslint/eslint-plugin-react/pull/761
[#759]: https://github.com/jsx-eslint/eslint-plugin-react/pull/759
[#703]: https://github.com/jsx-eslint/eslint-plugin-react/pull/703
[#753]: https://github.com/jsx-eslint/eslint-plugin-react/pull/753
[#739]: https://github.com/jsx-eslint/eslint-plugin-react/issues/739
[#731]: https://github.com/jsx-eslint/eslint-plugin-react/pull/731
[#745]: https://github.com/jsx-eslint/eslint-plugin-react/pull/745
[#659]: https://github.com/jsx-eslint/eslint-plugin-react/pull/659
[#314]: https://github.com/jsx-eslint/eslint-plugin-react/pull/314

## [6.0.0] - 2016-08-01
### Added
* Add an `all` shareable configuration with all rules enabled ([#674][] @pfhayes)
* Add [`no-find-dom-node`][] rule ([#678][])
* Add `shorthandLast` option to [`jsx-sort-props`][] ([#391][] @mathieumg)
* Add `allowDecorators` option to [`require-optimization`][] ([#669][] @Tom910)

### Breaking
* Deprecate [`require-extension`][] rule, use the [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) [`extensions`](https://github.com/benmosher/eslint-plugin-import/blob/master/docs/rules/extensions.md) rule instead. [`require-extension`][] still works but will trigger a warning
* Enable `allow-in-func` mode by default in [`no-did-mount-set-state`][] and [`no-did-update-set-state`][] rules ([#702][] @lencioni)
* Enable html tags check by default in `self-closing-comp`
* Remove `pragma` option from `jsx-uses-react`, use the [shared settings](README.md#configuration) to specify a custom pragma ([#700][] @lencioni)
* Remove `react` option from [`no-deprecated`][] rule, use the [shared settings](README.md#configuration) to specify the React version ([#700][] @lencioni)
* Add [`require-render-return`][] rule to recommended rules
* Remove [`no-danger`][] from recommended rules ([#636][] @mjackson)
* Remove [`no-did-mount-set-state`][] and [`no-did-update-set-state`][] from recommended rules ([#596][])
* Remove deprecated [`jsx-sort-prop-types`][] rule, use [`sort-prop-types`][] instead ([#549][] @lencioni)
* Rename [`no-comment-textnodes`][] to [`jsx-no-comment-textnodes`][]. [`no-comment-textnodes`][] still works but will trigger a warning ([#668][] @lencioni)
* Rename [`wrap-multilines`][] to [`jsx-wrap-multilines`][]. [`wrap-multilines`][] still works but will trigger a warning ([#668][] @lencioni)
* Add ESLint as peerDependency ([#657][] @jokeyrhyme)
* Add Node.js 0.10 as minimum required version ([#657][] @jokeyrhyme)

### Fixed
* Fix [`jsx-handler-names`][] incorrectly flagging `only` ([#571][] @lencioni)
* Fix spread props cash in [`jsx-no-target-blank`][] ([#679][] @randycoulman)
* Fix [`require-optimization`][] warning on stateless components ([#687][])
* Fix [`jsx-uses-vars`][] that incorrectly marked some variables as used ([#694][] @lencioni)
* Fix [`no-unknown-property`][] check on SVG attributes ([#718][])
* Fix [`jsx-no-bind`][] reporting errors on render functions that don't return JSX ([#663][] @petersendidit)
* Fix [`jsx-closing-bracket-location`][] autofix when `location` is set to `props-aligned` ([#684][] @pfhayes)
* Fix [`prop-types`][] for destructured arguments being assigned to the parent stateless component in some cases ([#698][])
* Fix [`prop-types`][] for JSX return being assigned to the parent function in some cases ([#504][])
* Fix [`jsx-curly-spacing`][] for reporting on JSX content by mistake ([#671][])
* Fix [`prop-types`][] crash when accessing constructor on props ([#654][])
* Fix [`jsx-filename-extension`][] to not check filenames on text input ([#662][] @ljharb)
* Fix [`jsx-no-comment-textnodes`][] incorrectly catching urls ([#664][] @petersendidit)

### Changed
* Only report [`jsx-filename-extension`][] warning once per file ([#660][] @mathieumg)
* Update SVG and DOM attribute list for `no-unknown-property`
* Update rules to use the new ESLint rule format ([#661][] @petersendidit)
* Update dependencies
* Documentation improvements ([#724][] @lencioni)
* Update Travis CI and AppVeyor CI configurations (@ljharb)

[6.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.2.2...v6.0.0
[#571]: https://github.com/jsx-eslint/eslint-plugin-react/issues/571
[#728]: https://github.com/jsx-eslint/eslint-plugin-react/pull/728
[#679]: https://github.com/jsx-eslint/eslint-plugin-react/pull/679
[#687]: https://github.com/jsx-eslint/eslint-plugin-react/issues/687
[#694]: https://github.com/jsx-eslint/eslint-plugin-react/issues/694
[#718]: https://github.com/jsx-eslint/eslint-plugin-react/issues/718
[#723]: https://github.com/jsx-eslint/eslint-plugin-react/pull/723
[#702]: https://github.com/jsx-eslint/eslint-plugin-react/pull/702
[#700]: https://github.com/jsx-eslint/eslint-plugin-react/pull/700
[#636]: https://github.com/jsx-eslint/eslint-plugin-react/pull/636
[#596]: https://github.com/jsx-eslint/eslint-plugin-react/issues/596
[#661]: https://github.com/jsx-eslint/eslint-plugin-react/issues/661
[#724]: https://github.com/jsx-eslint/eslint-plugin-react/pull/724
[#674]: https://github.com/jsx-eslint/eslint-plugin-react/issues/674
[#678]: https://github.com/jsx-eslint/eslint-plugin-react/issues/678
[#391]: https://github.com/jsx-eslint/eslint-plugin-react/issues/391
[#669]: https://github.com/jsx-eslint/eslint-plugin-react/pull/669
[#663]: https://github.com/jsx-eslint/eslint-plugin-react/issues/663
[#684]: https://github.com/jsx-eslint/eslint-plugin-react/pull/684
[#698]: https://github.com/jsx-eslint/eslint-plugin-react/issues/698
[#504]: https://github.com/jsx-eslint/eslint-plugin-react/issues/504
[#671]: https://github.com/jsx-eslint/eslint-plugin-react/issues/671
[#549]: https://github.com/jsx-eslint/eslint-plugin-react/issues/549
[#668]: https://github.com/jsx-eslint/eslint-plugin-react/issues/668
[#660]: https://github.com/jsx-eslint/eslint-plugin-react/pull/660
[#654]: https://github.com/jsx-eslint/eslint-plugin-react/issues/654
[#662]: https://github.com/jsx-eslint/eslint-plugin-react/issues/662
[#664]: https://github.com/jsx-eslint/eslint-plugin-react/issues/664
[#657]: https://github.com/jsx-eslint/eslint-plugin-react/pull/657

## [5.2.2] - 2016-06-17
### Fixed
* Fix [`jsx-no-bind`][] crash ([#641][])

[5.2.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.2.1...v5.2.2
[#641]: https://github.com/jsx-eslint/eslint-plugin-react/issues/641

## [5.2.1] - 2016-06-17
### Fixed
* Fix [`jsx-pascal-case`][] for namespaced components ([#637][] @evcohen)

[5.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.2.0...v5.2.1
[#637]: https://github.com/jsx-eslint/eslint-plugin-react/issues/637

## [5.2.0] - 2016-06-17
### Added
* Add [`require-optimization`][] rule ([#240][] @EvNaverniouk)
* Add [`jsx-filename-extension`][] rule  ([#495][] @lencioni)
* Add [`no-render-return-value`][] rule ([#531][] @iamdustan)
* Add [`no-comment-textnodes`][] rule ([#616][] @benvinegar)
* Add `objectLiterals` option to [`jsx-curly-spacing`][] ([#388][], [#211][] @casesandberg @ljharb)
* Add option to [`self-closing-comp`][] to check html tags ([#572][] @gitim)
* Add `ignore` option to [`no-unknown-property`][] rule ([#631][] @insin)
* Add support for ES7 bind operator to [`jsx-handler-names`][] ([#630][])
* Add support for explicit declaration that class extends React.Component ([#68][] @gausie)

### Fixed
* Fix [`jsx-closing-bracket-location`][] multiline prop support ([#493][] @tuures)
* Fix [`prop-types`][] for props that where not assigned to the right component ([#591][])
* Fix [`display-name`][] when JSON style is used for defining components ([#590][] @gitim)
* Fix [`jsx-no-bind`][] for bind detection in render when assigned to a variable ([#474][] @petersendidit)
* Fix [`jsx-curly-spacing`][] for spread operator ([#606][] @gitim)
* Fix [`sort-comp`][] crash on spread operator ([#624][])
* Fix [`prop-types`][] crash when destructuring props with spread only

### Changed
* Update dependencies
* Add [doctrine](https://github.com/eslint/doctrine) as a dependency ([#68][] @gausie)
* Add [jsx-ast-utils](https://github.com/evcohen/jsx-ast-utils) as a dependency ([#634][] @evcohen)
* Documentation improvements ([#594][] @lencioni, [#598][] @mLuby, [#633][] @appsforartists)

[5.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.1.1...v5.2.0
[#68]: https://github.com/jsx-eslint/eslint-plugin-react/issues/68
[#211]: https://github.com/jsx-eslint/eslint-plugin-react/issues/211
[#240]: https://github.com/jsx-eslint/eslint-plugin-react/issues/240
[#388]: https://github.com/jsx-eslint/eslint-plugin-react/issues/388
[#474]: https://github.com/jsx-eslint/eslint-plugin-react/issues/474
[#493]: https://github.com/jsx-eslint/eslint-plugin-react/pull/493
[#495]: https://github.com/jsx-eslint/eslint-plugin-react/issues/495
[#531]: https://github.com/jsx-eslint/eslint-plugin-react/issues/531
[#572]: https://github.com/jsx-eslint/eslint-plugin-react/issues/572
[#590]: https://github.com/jsx-eslint/eslint-plugin-react/issues/590
[#591]: https://github.com/jsx-eslint/eslint-plugin-react/issues/591
[#594]: https://github.com/jsx-eslint/eslint-plugin-react/pull/594
[#598]: https://github.com/jsx-eslint/eslint-plugin-react/pull/598
[#606]: https://github.com/jsx-eslint/eslint-plugin-react/issues/606
[#616]: https://github.com/jsx-eslint/eslint-plugin-react/pull/616
[#624]: https://github.com/jsx-eslint/eslint-plugin-react/issues/624
[#630]: https://github.com/jsx-eslint/eslint-plugin-react/issues/630
[#631]: https://github.com/jsx-eslint/eslint-plugin-react/pull/631
[#633]: https://github.com/jsx-eslint/eslint-plugin-react/pull/633
[#634]: https://github.com/jsx-eslint/eslint-plugin-react/pull/634

## [5.1.1] - 2016-05-10
### Fixed
* Fix [`require-render-return`][] crash ([#589][])

[5.1.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.1.0...v5.1.1
[#589]: https://github.com/jsx-eslint/eslint-plugin-react/issues/589

## [5.1.0] - 2016-05-10
### Added
* Add [`jsx-no-target-blank`][] rule ([#582][] @Gasparila)
* Add `allowAllCaps` and `ignore` options to [`jsx-pascal-case`][] ([#575][])
* Add class properties support to [`require-render-return`][] ([#564][])

### Fixed
* Fix [`jsx-closing-bracket-location`][] fixer ([#533][] @dtinth)
* Fix [`require-render-return`][] to only check valid render methods ([#563][])
* Fix detection to allow simple `this` usage in fonctional components ([#576][])
* Fix [`forbid-prop-types`][] crash ([#579][])
* Fix comment handling in [`jsx-curly-spacing`][] ([#584][])

### Changed
* Update dependencies
* Documentation improvements (@coryhouse, [#581][] @scurker, [#588][])

[5.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.0.1...v5.1.0
[#582]: https://github.com/jsx-eslint/eslint-plugin-react/pull/582
[#575]: https://github.com/jsx-eslint/eslint-plugin-react/issues/575
[#564]: https://github.com/jsx-eslint/eslint-plugin-react/issues/564
[#533]: https://github.com/jsx-eslint/eslint-plugin-react/issues/533
[#563]: https://github.com/jsx-eslint/eslint-plugin-react/issues/563
[#576]: https://github.com/jsx-eslint/eslint-plugin-react/issues/576
[#579]: https://github.com/jsx-eslint/eslint-plugin-react/issues/579
[#584]: https://github.com/jsx-eslint/eslint-plugin-react/pull/584
[#559]: https://github.com/jsx-eslint/eslint-plugin-react/pull/559
[#581]: https://github.com/jsx-eslint/eslint-plugin-react/pull/581
[#588]: https://github.com/jsx-eslint/eslint-plugin-react/issues/588

## [5.0.1] - 2016-04-18
### Fixed
* Fix [`require-render-return`][] to not check stateless functions ([#550][])

[5.0.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v5.0.0...v5.0.1
[#550]: https://github.com/jsx-eslint/eslint-plugin-react/issues/550

## [5.0.0] - 2016-04-17
### Added
* Add [`jsx-first-prop-new-line`][] rule ([#410][] @jseminck)

### Breaking
* Update rules for React 15:
  * Add warnings for `LinkedStateMixin`, `ReactPerf.printDOM` and `ReactPerf.getMeasurementsSummaryMap` in `no-deprecated`
  * Allow stateless components to return `null` in [`prefer-stateless-function`][]
  * Remove SVG attributes warnings ([#490][])

If you're still not using React 15 you can keep the old behavior by setting the React version to `0.14` in the [shared settings](README.md#configuration).

### Fixed
* Rewrite [`require-render-return`][] rule ([#542][], [#543][])
* Fix [`prefer-stateless-function`][] crash ([#544][])
* Fix external propTypes handling ([#545][])
* Do not mark inline functions in JSX as components ([#546][])

### Changed
* Update dependencies
* Documentation improvements

[5.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.3.0...v5.0.0
[#410]: https://github.com/jsx-eslint/eslint-plugin-react/issues/410
[#490]: https://github.com/jsx-eslint/eslint-plugin-react/issues/490
[#542]: https://github.com/jsx-eslint/eslint-plugin-react/issues/542
[#543]: https://github.com/jsx-eslint/eslint-plugin-react/issues/543
[#544]: https://github.com/jsx-eslint/eslint-plugin-react/issues/544
[#545]: https://github.com/jsx-eslint/eslint-plugin-react/issues/545
[#546]: https://github.com/jsx-eslint/eslint-plugin-react/issues/546

## [4.3.0] - 2016-04-07
### Added
* Add [`require-render-return`][] rule ([#482][] @shmuga)
* Add auto fix for [`jsx-equals-spacing`][] ([#506][] @peet)
* Add auto fix for [`jsx-closing-bracket-location`][] ([#511][] @KevinGrandon)

### Fixed
* Fix [`prefer-stateless-function`][] for conditional JSX ([#516][])
* Fix [`jsx-pascal-case`][] to support single letter component names ([#505][] @dthielman)

### Changed
* Update dependencies
* Documentation improvements ([#509][] @coryhouse, [#526][] @ahoym)

[4.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.2.3...v4.3.0
[#482]: https://github.com/jsx-eslint/eslint-plugin-react/issues/482
[#506]: https://github.com/jsx-eslint/eslint-plugin-react/pull/506
[#511]: https://github.com/jsx-eslint/eslint-plugin-react/pull/511
[#516]: https://github.com/jsx-eslint/eslint-plugin-react/issues/516
[#505]: https://github.com/jsx-eslint/eslint-plugin-react/issues/505
[#509]: https://github.com/jsx-eslint/eslint-plugin-react/pull/509
[#526]: https://github.com/jsx-eslint/eslint-plugin-react/pull/526

## [4.2.3] - 2016-03-15
### Fixed
* Fix class properties retrieval in [`prefer-stateless-function`][] ([#499][])

[4.2.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.2.2...v4.2.3
[#499]: https://github.com/jsx-eslint/eslint-plugin-react/issues/499

## [4.2.2] - 2016-03-14
### Fixed
* Rewrite [`prefer-stateless-function`][] rule ([#491][])
* Fix [`self-closing-comp`][] to treat non-breaking spaces as content ([#496][])
* Fix detection for direct props in [`prop-types`][] ([#497][])
* Fix annotated function detection in [`prop-types`][] ([#498][])
* Fix `this` usage in [`jsx-no-undef`][] ([#489][])

### Changed
* Update dependencies
* Add shared setting for React version

[4.2.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.2.1...v4.2.2
[#491]: https://github.com/jsx-eslint/eslint-plugin-react/issues/491
[#496]: https://github.com/jsx-eslint/eslint-plugin-react/issues/496
[#497]: https://github.com/jsx-eslint/eslint-plugin-react/issues/497
[#498]: https://github.com/jsx-eslint/eslint-plugin-react/issues/498
[#489]: https://github.com/jsx-eslint/eslint-plugin-react/issues/489

## [4.2.1] - 2016-03-08
### Fixed
* Fix [`sort-prop-types`][] crash with spread operator ([#478][])
* Fix stateless components detection when conditionally returning JSX ([#486][])
* Fix case where props were not assigned to the right component ([#485][])
* Fix missing `getChildContext` lifecycle method in [`prefer-stateless-function`][] ([#492][])

[4.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.2.0...v4.2.1
[#478]: https://github.com/jsx-eslint/eslint-plugin-react/issues/478
[#486]: https://github.com/jsx-eslint/eslint-plugin-react/issues/486
[#485]: https://github.com/jsx-eslint/eslint-plugin-react/issues/485
[#492]: https://github.com/jsx-eslint/eslint-plugin-react/issues/492

## [4.2.0] - 2016-03-05
### Added
* Add support for Flow annotations on stateless components ([#467][])
* Add [`prefer-stateless-function`][] rule ([#214][])
* Add auto fix for [`jsx-indent-props`][] ([#483][] @shioju)

### Fixed
* Fix [`jsx-no-undef`][] crash on objects ([#469][])
* Fix propTypes detection when declared before the component ([#472][])

### Changed
* Update dependencies
* Documentation improvements ([#464][] @alex-tan, [#466][] @awong-dev, [#470][] @Gpx; [#462][] @thaggie)

[4.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.1.0...v4.2.0
[#467]: https://github.com/jsx-eslint/eslint-plugin-react/issues/467
[#214]: https://github.com/jsx-eslint/eslint-plugin-react/issues/214
[#483]: https://github.com/jsx-eslint/eslint-plugin-react/pull/483
[#469]: https://github.com/jsx-eslint/eslint-plugin-react/issues/469
[#472]: https://github.com/jsx-eslint/eslint-plugin-react/issues/472
[#464]: https://github.com/jsx-eslint/eslint-plugin-react/pull/464
[#466]: https://github.com/jsx-eslint/eslint-plugin-react/pull/466
[#470]: https://github.com/jsx-eslint/eslint-plugin-react/pull/470
[#462]: https://github.com/jsx-eslint/eslint-plugin-react/pull/462

## [4.1.0] - 2016-02-23
### Added
* Add component detection for class expressions
* Add displayName detection for class expressions in [`display-name`][] ([#419][])

### Fixed
* Fix used props detection in components for which we are not confident in [`prop-types`][] ([#420][])
* Fix false positive in [`jsx-key`][] ([#456][] @jkimbo)

### Changed
* Documentation improvements ([#457][] @wyze)

[4.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v4.0.0...v4.1.0
[#419]: https://github.com/jsx-eslint/eslint-plugin-react/issues/419
[#420]: https://github.com/jsx-eslint/eslint-plugin-react/issues/420
[#456]: https://github.com/jsx-eslint/eslint-plugin-react/pull/456
[#457]: https://github.com/jsx-eslint/eslint-plugin-react/pull/457

## [4.0.0] - 2016-02-19
### Added
* Add [`jsx-space-before-closing`][] rule ([#244][] @ryym)
* Add support for destructing in function signatures to [`prop-types`][] ([#354][] @lencioni)

### Breaking
* Add support for static methods to `sort-comp`. Static methods must now be declared first, see [rule documentation](docs/rules/sort-comp.md) ([#128][] @lencioni)
* Add shareable config in place of default configuration. [`jsx-uses-vars`][] is not enabled by default anymore, see [documentation](README.md#recommended-configuration) ([#192][])
* Rename `jsx-sort-prop-types` to [`sort-prop-types`][]. `jsx-sort-prop-types` still works but will trigger a warning ([#87][] @lencioni)
* Remove deprecated `jsx-quotes` rule ([#433][] @lencioni)
* [`display-name`][] now accept the transpiler name by default. You can use the `ignoreTranspilerName` option to get the old behavior, see [rule documentation](docs/rules/display-name.md#ignoretranspilername) ([#440][] @lencioni)

### Fixed
* Only ignore lowercase JSXIdentifier in [`jsx-no-undef`][] ([#435][])
* Fix [`jsx-handler-names`][] regex ([#425][])
* Fix destructured props detection in [`prop-types`][] ([#443][])

### Changed
* Update dependencies ([#426][] @quentin-)
* Documentation improvements ([#414][] @vkrol, [#370][] @tmcw, [#441][] [#429][] @lencioni, [#432][] @note89, [#438][] @jmann6)

[4.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.16.1...v4.0.0
[#244]: https://github.com/jsx-eslint/eslint-plugin-react/issues/244
[#354]: https://github.com/jsx-eslint/eslint-plugin-react/issues/354
[#128]: https://github.com/jsx-eslint/eslint-plugin-react/issues/128
[#192]: https://github.com/jsx-eslint/eslint-plugin-react/issues/192
[#87]: https://github.com/jsx-eslint/eslint-plugin-react/issues/87
[#440]: https://github.com/jsx-eslint/eslint-plugin-react/pull/440
[#435]: https://github.com/jsx-eslint/eslint-plugin-react/issues/435
[#425]: https://github.com/jsx-eslint/eslint-plugin-react/issues/425
[#443]: https://github.com/jsx-eslint/eslint-plugin-react/issues/443
[#426]: https://github.com/jsx-eslint/eslint-plugin-react/pull/426
[#414]: https://github.com/jsx-eslint/eslint-plugin-react/pull/414
[#370]: https://github.com/jsx-eslint/eslint-plugin-react/pull/370
[#441]: https://github.com/jsx-eslint/eslint-plugin-react/pull/441
[#429]: https://github.com/jsx-eslint/eslint-plugin-react/pull/429
[#432]: https://github.com/jsx-eslint/eslint-plugin-react/pull/432
[#438]: https://github.com/jsx-eslint/eslint-plugin-react/pull/438
[#433]: https://github.com/jsx-eslint/eslint-plugin-react/pull/433

## [3.16.1] - 2016-01-24
### Fixed
* Fix [`jsx-sort-prop-types`][] issue with custom propTypes ([#408][] @alitaheri)

[3.16.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.16.0...v3.16.1
[#408]: https://github.com/jsx-eslint/eslint-plugin-react/issues/408

## [3.16.0] - 2016-01-24
### Added
* Add [`jsx-equals-spacing`][] rule ([#394][] @ryym)
* Add auto fix for `wrap-multiline`
* Add auto fix for `jsx-boolean-value`
* Add auto fix for `no-unknown-property`
* Add auto fix for [`jsx-curly-spacing`][] ([#407][] @ewendel)
* Add `requiredFirst` option to [`jsx-sort-prop-types`][] ([#392][] @chrislaskey)
* Add `ignoreRefs` option to [`jsx-no-bind`][] ([#330][] @silvenon)

### Fixed
* Ignore `ref` in [`jsx-handler-names`][] (again) ([#396][])

### Changed
* Update dependencies

[3.16.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.15.0...v3.16.0
[#394]: https://github.com/jsx-eslint/eslint-plugin-react/issues/394
[#407]: https://github.com/jsx-eslint/eslint-plugin-react/pull/407
[#392]: https://github.com/jsx-eslint/eslint-plugin-react/pull/392
[#330]: https://github.com/jsx-eslint/eslint-plugin-react/issues/330
[#396]: https://github.com/jsx-eslint/eslint-plugin-react/issues/396

## [3.15.0] - 2016-01-12
### Added
* Add support for flow annotations to [`prop-types`][] ([#382][] @phpnode)

### Fixed
* Fix [`prop-types`][] crash when initializing class variable with an empty object ([#383][])
* Fix [`prop-types`][] crash when propTypes are using the spread operator ([#389][])

### Changed
* Improve [`sort-comp`][] error messages ([#372][] @SystemParadox)
* Update dependencies

[3.15.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.14.0...v3.15.0
[#382]: https://github.com/jsx-eslint/eslint-plugin-react/pull/382
[#383]: https://github.com/jsx-eslint/eslint-plugin-react/issues/383
[#389]: https://github.com/jsx-eslint/eslint-plugin-react/issues/389
[#372]: https://github.com/jsx-eslint/eslint-plugin-react/pull/372

## [3.14.0] - 2016-01-05
### Added
* Add [`jsx-indent`][] rule ([#342][])
* Add shared setting for pragma configuration ([#228][] @NickStefan)

### Fixed
* Fix crash in [`jsx-key`][] ([#380][] @nfcampos)
* Fix crash in [`forbid-prop-types`][] ([#377][] @nfcampos)
* Ignore `ref` in [`jsx-handler-names`][] ([#375][])

### Changed
* Add AppVeyor CI to run tests on a Windows platform
* Add [`sort-comp`][] codemod to [`sort-comp`][] documentation ([#381][] @turadg)

[3.14.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.13.1...v3.14.0
[#342]: https://github.com/jsx-eslint/eslint-plugin-react/issues/342
[#228]: https://github.com/jsx-eslint/eslint-plugin-react/issues/228
[#380]: https://github.com/jsx-eslint/eslint-plugin-react/pull/380
[#377]: https://github.com/jsx-eslint/eslint-plugin-react/pull/377
[#375]: https://github.com/jsx-eslint/eslint-plugin-react/issues/375
[#381]: https://github.com/jsx-eslint/eslint-plugin-react/pull/381

## [3.13.1] - 2015-12-26
### Fixed
* Fix crash in [`jsx-key`][] ([#373][] @lukekarrys)

[3.13.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.13.0...v3.13.1
[#373]: https://github.com/jsx-eslint/eslint-plugin-react/issues/373

## [3.13.0] - 2015-12-24
### Added
* Add [`no-string-refs`][] rule ([#341][] @Intellicode)
* Add support for propTypes assigned via a variable in [`prop-types`][] ([#355][])

### Fixed
* Fix `never` option in [`prefer-es6-class`][]
* Fix [`jsx-key`][] false-positives ([#320][] @silvenon)

### Changed
* Documentation improvements ([#368][] @lencioni, [#370][] @tmcw, [#371][])
* Update dependencies

[3.13.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.12.0...v3.13.0
[#341]: https://github.com/jsx-eslint/eslint-plugin-react/issues/341
[#355]: https://github.com/jsx-eslint/eslint-plugin-react/issues/355
[#320]: https://github.com/jsx-eslint/eslint-plugin-react/issues/320

[#368]: https://github.com/jsx-eslint/eslint-plugin-react/pull/368
[#370]: https://github.com/jsx-eslint/eslint-plugin-react/pull/370
[#371]: https://github.com/jsx-eslint/eslint-plugin-react/issues/371

## [3.12.0] - 2015-12-20
### Added
* Add [`no-deprecated`][] rule ([#356][] @graue)
* Add [`no-is-mounted`][] rule ([#37][] @lencioni)
* Add `never` option to [`prefer-es6-class`][] rule ([#359][] @pwmckenna)

### Fixed
* Fix [`jsx-pascal-case`][] to stop checking lower cased components ([#329][])
* Fix crash in component detection class ([#364][])

### Changed
* Add link to [eslint-plugin-react-native](https://github.com/Intellicode/eslint-plugin-react-native) in Readme
* Update dependencies

[3.12.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.11.3...v3.12.0
[#356]: https://github.com/jsx-eslint/eslint-plugin-react/pull/356
[#37]: https://github.com/jsx-eslint/eslint-plugin-react/issues/37
[#359]: https://github.com/jsx-eslint/eslint-plugin-react/pull/359
[#329]: https://github.com/jsx-eslint/eslint-plugin-react/issues/329
[#364]: https://github.com/jsx-eslint/eslint-plugin-react/issues/364

## [3.11.3] - 2015-12-05
### Fixed
* Fix crash in [`prop-types`][] when reassigning props ([#345][])
* Fix [`jsx-handler-names`][] for stateless components ([#346][])

### Changed
* Update [`jsx-handler-names`][] error messages to be less specific ([#348][] @jakemmarsh)

[3.11.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.11.2...v3.11.3
[#345]: https://github.com/jsx-eslint/eslint-plugin-react/issues/345
[#346]: https://github.com/jsx-eslint/eslint-plugin-react/issues/346
[#348]: https://github.com/jsx-eslint/eslint-plugin-react/pull/348

## [3.11.2] - 2015-12-01
### Fixed
* Allow numbers in [`jsx-pascal-case`][] ([#339][])
* Fix [`jsx-handler-names`][] crash with arrays ([#340][])

### Changed
* Add `allow-in-func` option to [`no-did-update-set-state`][] documentation

[3.11.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.11.1...v3.11.2
[#339]: https://github.com/jsx-eslint/eslint-plugin-react/issues/339
[#340]: https://github.com/jsx-eslint/eslint-plugin-react/issues/340

## [3.11.1] - 2015-11-29
### Fixed
* Fix SVG attributes support for [`no-unknown-property`][] ([#338][])

[3.11.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.11.0...v3.11.1
[#338]: https://github.com/jsx-eslint/eslint-plugin-react/issues/338

## [3.11.0] - 2015-11-29
### Added
* Add [`jsx-handler-names`][] rule ([#315][] @jakemmarsh)
* Add SVG attributes support to [`no-unknown-property`][] ([#318][])
* Add shorthandFirst option to [`jsx-sort-props`][] ([#336][] @lucasmotta)

### Fixed
* Fix destructured props detection in stateless components ([#326][])
* Fix props validation for nested stateless components ([#331][])
* Fix [`require-extension`][] to ignore extension if it's part of the package name ([#319][])

### Changed
* Allow consecutive uppercase letters in [`jsx-pascal-case`][] ([#328][] @lencioni)
* Update dependencies

[3.11.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.10.0...v3.11.0
[#315]: https://github.com/jsx-eslint/eslint-plugin-react/pull/315
[#318]: https://github.com/jsx-eslint/eslint-plugin-react/issues/318
[#336]: https://github.com/jsx-eslint/eslint-plugin-react/pull/336
[#326]: https://github.com/jsx-eslint/eslint-plugin-react/issues/326
[#331]: https://github.com/jsx-eslint/eslint-plugin-react/issues/331
[#319]: https://github.com/jsx-eslint/eslint-plugin-react/issues/319
[#328]: https://github.com/jsx-eslint/eslint-plugin-react/issues/328

## [3.10.0] - 2015-11-21
### Added
* Add [`jsx-pascal-case`][] rule ([#306][] @jakemmarsh)

### Fixed
* Fix crash on incomplete class property declaration ([#317][] @dapetcu21)
* Fix crash with ESLint 1.10.0 ([#323][] @lukekarrys)

[3.10.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.9.0...v3.10.0
[#306]: https://github.com/jsx-eslint/eslint-plugin-react/pull/306
[#317]: https://github.com/jsx-eslint/eslint-plugin-react/issues/317
[#323]: https://github.com/jsx-eslint/eslint-plugin-react/issues/323

## [3.9.0] - 2015-11-17
### Added
* Add [`jsx-key`][] rule ([#293][] @benmosher)
* Add `allow-in-func` option to [`no-did-update-set-state`][] ([#300][])
* Add option to only enforce [`jsx-closing-bracket-location`][] rule to one type of tag (nonEmpty or selfClosing) ([#307][])

### Fixed
* Fix crash when destructuring with only the rest spread ([#269][])
* Fix variables detection when searching for related components ([#303][])
* Fix [`no-unknown-property`][] to not check custom elements ([#308][] @zertosh)

### Changed
* Improve [`jsx-closing-bracket-location`][] error message ([#301][] @alopatin)
* Update dependencies

[3.9.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.8.0...v3.9.0
[#293]: https://github.com/jsx-eslint/eslint-plugin-react/pull/293
[#300]: https://github.com/jsx-eslint/eslint-plugin-react/issues/300
[#307]: https://github.com/jsx-eslint/eslint-plugin-react/issues/307
[#269]: https://github.com/jsx-eslint/eslint-plugin-react/issues/269
[#303]: https://github.com/jsx-eslint/eslint-plugin-react/issues/303
[#308]: https://github.com/jsx-eslint/eslint-plugin-react/pull/308
[#301]: https://github.com/jsx-eslint/eslint-plugin-react/pull/301

## [3.8.0] - 2015-11-07
### Added
* Add ignoreStateless option to [`no-multi-comp`][] ([#290][])

### Fixed
* Fix classes with properties to always be marked as components ([#291][])
* Fix ES5 class detection when using `createClass` by itself ([#297][])
* Fix direct props detection ([#298][])
* Ignore functions containing the keyword `this` during component detection

[3.8.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.7.1...v3.8.0
[#290]: https://github.com/jsx-eslint/eslint-plugin-react/issues/290
[#291]: https://github.com/jsx-eslint/eslint-plugin-react/issues/291
[#297]: https://github.com/jsx-eslint/eslint-plugin-react/issues/297
[#298]: https://github.com/jsx-eslint/eslint-plugin-react/issues/298

## [3.7.1] - 2015-11-05
### Fixed
* Fix [`sort-comp`][] crash on stateless components ([#285][])
* Fix crash in ES5 components detection ([#286][])
* Fix ES5 components detection from nested functions ([#287][])

[3.7.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.7.0...v3.7.1
[#285]: https://github.com/jsx-eslint/eslint-plugin-react/issues/285
[#286]: https://github.com/jsx-eslint/eslint-plugin-react/issues/286
[#287]: https://github.com/jsx-eslint/eslint-plugin-react/issues/287

## [3.7.0] - 2015-11-05
### Added
* Add [`jsx-no-bind`][] rule ([#184][] @Daniel15)
* Add line-aligned option to [`jsx-closing-bracket-location`][] ([#243][] @alopatin)

### Fixed
* Fix a lot of issues about components detection, mostly related to stateless components ([#264][], [#267][], [#268][], [#276][], [#277][], [#280][])

### Changed
* Update dependencies

[3.7.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.6.3...v3.7.0
[#184]: https://github.com/jsx-eslint/eslint-plugin-react/issues/184
[#243]: https://github.com/jsx-eslint/eslint-plugin-react/issues/243
[#264]: https://github.com/jsx-eslint/eslint-plugin-react/issues/264
[#267]: https://github.com/jsx-eslint/eslint-plugin-react/issues/267
[#268]: https://github.com/jsx-eslint/eslint-plugin-react/issues/268
[#276]: https://github.com/jsx-eslint/eslint-plugin-react/issues/276
[#277]: https://github.com/jsx-eslint/eslint-plugin-react/issues/277
[#280]: https://github.com/jsx-eslint/eslint-plugin-react/issues/280

## [3.6.3] - 2015-10-20
### Fixed
* Fix [`display-name`][] for stateless components ([#256][])
* Fix [`prop-types`][] props validation in constructor ([#259][])
* Fix typo in README ([#261][] @chiedojohn)

[3.6.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.6.2...v3.6.3
[#256]: https://github.com/jsx-eslint/eslint-plugin-react/issues/256
[#259]: https://github.com/jsx-eslint/eslint-plugin-react/issues/259
[#261]: https://github.com/jsx-eslint/eslint-plugin-react/pull/261

## [3.6.2] - 2015-10-18
### Fixed
* Fix wrong prop-types detection ([#255][])

[3.6.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.6.1...v3.6.2
[#255]: https://github.com/jsx-eslint/eslint-plugin-react/issues/255

## [3.6.1] - 2015-10-18
### Fixed
* Fix props validation in constructor ([#254][])

[3.6.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.6.0...v3.6.1
[#254]: https://github.com/jsx-eslint/eslint-plugin-react/issues/254

## [3.6.0] - 2015-10-18
### Added
* Add support for stateless function components to [`display-name`][] and [`prop-types`][] ([#237][])
* Add callbacksLast option to [`jsx-sort-props`][] and [`jsx-sort-prop-types`][] ([#242][] @Daniel15)
* Add [`prefer-es6-class`][] rule ([#247][] @hamiltondanielb)

### Fixed
* Fix [`forbid-prop-types`][] crash with destructured PropTypes ([#230][] @epmatsw)
* Fix [`forbid-prop-types`][] to do not modify AST directly ([#249][] @rhysd)
* Fix [`prop-types`][] crash with empty destructuring ([#251][])
* Fix [`prop-types`][] to not validate computed keys in destructuring ([#236][])

### Changed
* Update dependencies
* Improve components detection ([#233][])
* Documentation improvements ([#248][] @dguo)

[3.6.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.5.1...v3.6.0
[#237]: https://github.com/jsx-eslint/eslint-plugin-react/issues/237
[#242]: https://github.com/jsx-eslint/eslint-plugin-react/pull/242
[#247]: https://github.com/jsx-eslint/eslint-plugin-react/issues/247
[#230]: https://github.com/jsx-eslint/eslint-plugin-react/issues/230
[#249]: https://github.com/jsx-eslint/eslint-plugin-react/issues/249
[#251]: https://github.com/jsx-eslint/eslint-plugin-react/issues/251
[#236]: https://github.com/jsx-eslint/eslint-plugin-react/issues/236
[#233]: https://github.com/jsx-eslint/eslint-plugin-react/issues/233
[#248]: https://github.com/jsx-eslint/eslint-plugin-react/pull/248

## [3.5.1] - 2015-10-01
### Fixed
* Fix [`no-direct-mutation-state`][] to report only in React components ([#229][])
* Fix [`forbid-prop-types`][] for arrayOf and instanceOf ([#230][])

### Changed
* Documentation improvements ([#232][] @edge)

[3.5.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.5.0...v3.5.1
[#229]: https://github.com/jsx-eslint/eslint-plugin-react/issues/229
[#230]: https://github.com/jsx-eslint/eslint-plugin-react/issues/230
[#232]: https://github.com/jsx-eslint/eslint-plugin-react/pull/232

## [3.5.0] - 2015-09-28
### Added
* Add [`no-direct-mutation-state`][] rule ([#133][], [#201][] @petersendidit)
* Add [`forbid-prop-types`][] rule ([#215][] @pwmckenna)

### Fixed
* Fix no-did-mount/update-set-state rules, these rules were not working on ES6 classes

### Changed
* Update dependencies
* Documentation improvements ([#222][] @Andersos)

[3.5.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.4.2...v3.5.0
[#133]: https://github.com/jsx-eslint/eslint-plugin-react/issues/133
[#201]: https://github.com/jsx-eslint/eslint-plugin-react/issues/201
[#215]: https://github.com/jsx-eslint/eslint-plugin-react/issues/215
[#222]: https://github.com/jsx-eslint/eslint-plugin-react/pull/222

## [3.4.2] - 2015-09-18
### Fixed
* Only display the `jsx-quotes` deprecation warning with the default formatter ([#221][])

[3.4.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.4.1...v3.4.2
[#221]: https://github.com/jsx-eslint/eslint-plugin-react/issues/221

## [3.4.1] - 2015-09-17
### Fixed
* Fix `jsx-quotes` rule deprecation message ([#220][])

[3.4.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.4.0...v3.4.1
[#220]: https://github.com/jsx-eslint/eslint-plugin-react/issues/220

## [3.4.0] - 2015-09-16
### Added
* Add namespaced JSX support to [`jsx-no-undef`][] ([#219][] @zertosh)
* Add option to [`jsx-closing-bracket-location`][] to configure different styles for self-closing and non-empty tags ([#208][] @evocateur)

### Deprecated
* Deprecate `jsx-quotes` rule, will now trigger a warning if used ([#217][])

[3.4.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.3.2...v3.4.0
[#219]: https://github.com/jsx-eslint/eslint-plugin-react/pull/219
[#208]: https://github.com/jsx-eslint/eslint-plugin-react/pull/208
[#217]: https://github.com/jsx-eslint/eslint-plugin-react/issues/217

## [3.3.2] - 2015-09-10
### Changed
* Add `state` in lifecycle methods for [`sort-comp`][] rule ([#197][] @mathieudutour)
* Treat component with render which returns `createElement` as valid ([#206][] @epmatsw)

### Fixed
* Fix allowed methods on arrayOf in [`prop-types`][] ([#146][])
* Fix default configuration for [`jsx-boolean-value`][] ([#210][])

[3.3.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.3.1...v3.3.2
[#146]: https://github.com/jsx-eslint/eslint-plugin-react/issues/146
[#197]: https://github.com/jsx-eslint/eslint-plugin-react/pull/197
[#206]: https://github.com/jsx-eslint/eslint-plugin-react/pull/206
[#210]: https://github.com/jsx-eslint/eslint-plugin-react/issues/210

## [3.3.1] - 2015-09-01
### Changed
* Update dependencies
* Update changelog to follow the Keep a CHANGELOG standards
* Documentation improvements ([#198][] @lencioni)

### Fixed
* Fix [`jsx-closing-bracket-location`][] for multiline props ([#199][])

[3.3.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.3.0...v3.3.1
[#198]: https://github.com/jsx-eslint/eslint-plugin-react/pull/198
[#199]: https://github.com/jsx-eslint/eslint-plugin-react/issues/199

## [3.3.0] - 2015-08-26
### Added
* Add [`jsx-indent-props`][] rule ([#15][], [#181][])
* Add `no-set-state rule` ([#197][] @markdalgleish)
* Add [`jsx-closing-bracket-location`][] rule ([#14][], [#64][])

### Changed
* Update dependencies

### Fixed
* Fix crash on propTypes declarations with an empty body ([#193][] @mattyod)

[3.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.2.3...v3.3.0
[#15]: https://github.com/jsx-eslint/eslint-plugin-react/issues/15
[#181]: https://github.com/jsx-eslint/eslint-plugin-react/issues/181
[#197]: https://github.com/jsx-eslint/eslint-plugin-react/pull/197
[#14]: https://github.com/jsx-eslint/eslint-plugin-react/issues/14
[#64]: https://github.com/jsx-eslint/eslint-plugin-react/issues/64
[#193]: https://github.com/jsx-eslint/eslint-plugin-react/pull/193

## [3.2.3] - 2015-08-16
### Changed
* Update dependencies

### Fixed
* Fix object rest/spread handling ([#187][] @xjamundx, [#189][] @Morantron)

[3.2.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.2.2...v3.2.3
[#187]: https://github.com/jsx-eslint/eslint-plugin-react/pull/187
[#189]: https://github.com/jsx-eslint/eslint-plugin-react/pull/189

## [3.2.2] - 2015-08-11
### Changed
* Remove peerDependencies ([#178][])

[3.2.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.2.1...v3.2.2
[#178]: https://github.com/jsx-eslint/eslint-plugin-react/issues/178

## [3.2.1] - 2015-08-08
### Fixed
* Fix crash when propTypes don't have any parent ([#182][])
* Fix jsx-no-literals reporting errors outside JSX ([#183][] @CalebMorris)

[3.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.2.0...v3.2.1
[#182]: https://github.com/jsx-eslint/eslint-plugin-react/issues/182
[#183]: https://github.com/jsx-eslint/eslint-plugin-react/pull/183

## [3.2.0] - 2015-08-04
### Added
* Add [`jsx-max-props-per-line`][] rule ([#13][])
* Add [`jsx-no-literals`][] rule ([#176][] @CalebMorris)

### Changed
* Update dependencies

### Fixed
* Fix object access in [`jsx-no-undef`][] ([#172][])

[3.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.1.0...v3.2.0
[#13]: https://github.com/jsx-eslint/eslint-plugin-react/issues/13
[#176]: https://github.com/jsx-eslint/eslint-plugin-react/pull/176
[#172]: https://github.com/jsx-eslint/eslint-plugin-react/issues/172

## [3.1.0] - 2015-07-28
### Added
* Add event handlers to [`no-unknown-property`][] ([#164][] @mkenyon)
* Add customValidators option to [`prop-types`][] ([#145][] @CalebMorris)

### Changed
* Update dependencies
* Documentation improvements ([#167][] @ngbrown)

### Fixed
* Fix comment handling in [`jsx-curly-spacing`][] ([#165][])

[3.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v3.0.0...v3.1.0
[#164]: https://github.com/jsx-eslint/eslint-plugin-react/pull/164
[#145]: https://github.com/jsx-eslint/eslint-plugin-react/issues/145
[#165]: https://github.com/jsx-eslint/eslint-plugin-react/issues/165
[#167]: https://github.com/jsx-eslint/eslint-plugin-react/pull/167

## [3.0.0] - 2015-07-21
### Added
* Add jsx-no-duplicate-props rule ([#161][] @hummlas)
* Add allowMultiline option to the [`jsx-curly-spacing`][] rule ([#156][] @mathieumg)

### Breaking
* In [`jsx-curly-spacing`][] braces spanning multiple lines are now allowed with `never` option ([#156][] @mathieumg)

### Fixed
* Fix multiple var and destructuring handling in [`prop-types`][] ([#159][])
* Fix crash when retrieving propType name ([#163][])

[3.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.7.1...v3.0.0
[#161]: https://github.com/jsx-eslint/eslint-plugin-react/pull/161
[#156]: https://github.com/jsx-eslint/eslint-plugin-react/pull/156
[#159]: https://github.com/jsx-eslint/eslint-plugin-react/issues/159
[#163]: https://github.com/jsx-eslint/eslint-plugin-react/issues/163

## [2.7.1] - 2015-07-16
### Changed
* Update peerDependencies requirements ([#154][])
* Update codebase for ESLint v1.0.0
* Change oneOfType to actually keep the child types ([#148][] @CalebMorris)
* Documentation improvements ([#147][] @lencioni)

[2.7.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.7.0...v2.7.1
[#154]: https://github.com/jsx-eslint/eslint-plugin-react/issues/154
[#148]: https://github.com/jsx-eslint/eslint-plugin-react/issues/148
[#147]: https://github.com/jsx-eslint/eslint-plugin-react/pull/147

## [2.7.0] - 2015-07-11
### Added
* Add [`no-danger`][] rule ([#138][] @scothis)
* Add [`jsx-curly-spacing`][] rule ([#142][])

### Fixed
* Fix properties limitations on propTypes ([#139][])
* Fix component detection ([#144][])

[2.7.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.6.4...v2.7.0
[#138]: https://github.com/jsx-eslint/eslint-plugin-react/pull/138
[#142]: https://github.com/jsx-eslint/eslint-plugin-react/issues/142
[#139]: https://github.com/jsx-eslint/eslint-plugin-react/issues/139
[#144]: https://github.com/jsx-eslint/eslint-plugin-react/issues/144

## [2.6.4] - 2015-07-02
### Fixed
* Fix simple destructuring handling ([#137][])

[2.6.4]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.6.3...v2.6.4
[#137]: https://github.com/jsx-eslint/eslint-plugin-react/issues/137

## [2.6.3] - 2015-06-30
### Fixed
* Fix ignore option for [`prop-types`][] rule ([#135][])
* Fix nested props destructuring ([#136][])

[2.6.3]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.6.2...v2.6.3
[#135]: https://github.com/jsx-eslint/eslint-plugin-react/issues/135
[#136]: https://github.com/jsx-eslint/eslint-plugin-react/issues/136

## [2.6.2] - 2015-06-28
### Fixed
* Fix props validation when using a prop as an object key ([#132][])

[2.6.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.6.1...v2.6.2
[#132]: https://github.com/jsx-eslint/eslint-plugin-react/issues/132

## [2.6.1] - 2015-06-28
### Fixed
* Fix crash in [`prop-types`][] when encountering an empty variable declaration ([#130][])

[2.6.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.6.0...v2.6.1
[#130]: https://github.com/jsx-eslint/eslint-plugin-react/issues/130

## [2.6.0] - 2015-06-28
### Added
* Add support for nested propTypes ([#62][] [#105][] @Cellule)
* Add [`require-extension`][] rule ([#117][] @scothis)
* Add support for computed string format in [`prop-types`][] ([#127][] @Cellule)
* Add ES6 methods to [`sort-comp`][] default configuration ([#97][] [#122][])
* Add support for props destructuring directly on the this keyword
* Add `acceptTranspilerName` option to [`display-name`][] rule ([#75][])
* Add schema to validate rules options

### Changed
* Update dependencies

### Fixed
* Fix test command for Windows ([#114][] @Cellule)
* Fix detection of missing displayName and propTypes when `ecmaFeatures.jsx` is false ([#119][] @rpl)
* Fix propTypes destructuring with properties as string ([#118][] @Cellule)
* Fix [`jsx-sort-prop-types`][] support for keys as string ([#123][] @Cellule)
* Fix crash if a ClassProperty has only one token ([#125][])
* Fix invalid class property handling in [`jsx-sort-prop-types`][] ([#129][])

[2.6.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.5.2...v2.6.0
[#62]: https://github.com/jsx-eslint/eslint-plugin-react/issues/62
[#105]: https://github.com/jsx-eslint/eslint-plugin-react/issues/105
[#114]: https://github.com/jsx-eslint/eslint-plugin-react/pull/114
[#117]: https://github.com/jsx-eslint/eslint-plugin-react/pull/117
[#119]: https://github.com/jsx-eslint/eslint-plugin-react/pull/119
[#118]: https://github.com/jsx-eslint/eslint-plugin-react/issues/118
[#123]: https://github.com/jsx-eslint/eslint-plugin-react/pull/123
[#125]: https://github.com/jsx-eslint/eslint-plugin-react/issues/125
[#127]: https://github.com/jsx-eslint/eslint-plugin-react/pull/127
[#97]: https://github.com/jsx-eslint/eslint-plugin-react/issues/97
[#122]: https://github.com/jsx-eslint/eslint-plugin-react/issues/122
[#129]: https://github.com/jsx-eslint/eslint-plugin-react/issues/129
[#75]: https://github.com/jsx-eslint/eslint-plugin-react/issues/75

## [2.5.2] - 2015-06-14
### Fixed
* Fix regression in [`jsx-uses-vars`][] with `babel-eslint` ([#110][])

[2.5.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.5.1...v2.5.2
[#110]: https://github.com/jsx-eslint/eslint-plugin-react/issues/110

## [2.5.1] - 2015-06-14
### Changed
* Update dependencies
* Documentation improvements ([#99][] @morenoh149)

### Fixed
* Fix [`prop-types`][] crash when propTypes definition is invalid ([#95][])
* Fix [`jsx-uses-vars`][] for ES6 classes ([#96][])
* Fix hasOwnProperty that is taken for a prop ([#102][])

[2.5.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.5.0...v2.5.1
[#95]: https://github.com/jsx-eslint/eslint-plugin-react/issues/95
[#96]: https://github.com/jsx-eslint/eslint-plugin-react/issues/96
[#102]: https://github.com/jsx-eslint/eslint-plugin-react/issues/102
[#99]: https://github.com/jsx-eslint/eslint-plugin-react/pull/99

## [2.5.0] - 2015-06-04
### Added
* Add option to make [`wrap-multilines`][] more granular ([#94][] @PiPeep)

### Changed
* Update dependencies
* Documentation improvements ([#92][] [#93][] @lencioni)

[2.5.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.4.0...v2.5.0
[#94]: https://github.com/jsx-eslint/eslint-plugin-react/pull/94
[#92]: https://github.com/jsx-eslint/eslint-plugin-react/pull/92
[#93]: https://github.com/jsx-eslint/eslint-plugin-react/pull/93

## [2.4.0] - 2015-05-30
### Added
* Add pragma option to [`jsx-uses-react`][] ([#82][] @dominicbarnes)
* Add context props to [`sort-comp`][] ([#89][] @zertosh)

### Changed
* Update dependencies
* Documentation improvement ([#91][] @matthewwithanm)

### Fixed
* Fix itemID in [`no-unknown-property`][] rule ([#85][] @cody)
* Fix license field in package.json ([#90][] @zertosh)
* Fix usage of contructor in [`sort-comp`][] options ([#88][])

[2.4.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.3.0...v2.4.0
[#82]: https://github.com/jsx-eslint/eslint-plugin-react/pull/82
[#89]: https://github.com/jsx-eslint/eslint-plugin-react/pull/89
[#85]: https://github.com/jsx-eslint/eslint-plugin-react/pull/85
[#90]: https://github.com/jsx-eslint/eslint-plugin-react/pull/90
[#88]: https://github.com/jsx-eslint/eslint-plugin-react/issues/88
[#91]: https://github.com/jsx-eslint/eslint-plugin-react/pull/91

## [2.3.0] - 2015-05-14
### Added
* Add [`sort-comp`][] rule ([#39][])
* Add `allow-in-func` option to [`no-did-mount-set-state`][] ([#56][])

### Changed
* Update dependencies
* Improve errors locations for `prop-types`

### Fixed
* Fix quoted propTypes in ES6 ([#77][])

[2.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.2.0...v2.3.0
[#39]: https://github.com/jsx-eslint/eslint-plugin-react/issues/39
[#77]: https://github.com/jsx-eslint/eslint-plugin-react/issues/77
[#56]: https://github.com/jsx-eslint/eslint-plugin-react/issues/56

## [2.2.0] - 2015-04-22
### Added
* Add [`jsx-sort-prop-types`][] rule ([#38][] @AlexKVal)

### Changed
* Documentation improvements ([#71][] @AlexKVal)

### Fixed
* Fix variables marked as used when a prop has the same name ([#69][] @burnnat)

[2.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.1.1...v2.2.0
[#38]: https://github.com/jsx-eslint/eslint-plugin-react/issues/38
[#69]: https://github.com/jsx-eslint/eslint-plugin-react/pull/69
[#71]: https://github.com/jsx-eslint/eslint-plugin-react/pull/71

## [2.1.1] - 2015-04-17
### Added
* Add support for classes static properties ([#43][])
* Add tests for the `babel-eslint` parser
* Add ESLint as peerDependency ([#63][] @AlexKVal)

### Changed
* Documentation improvements ([#55][] @AlexKVal, [#60][] @chriscalo)

[2.1.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.1.0...v2.1.1
[#43]: https://github.com/jsx-eslint/eslint-plugin-react/issues/43
[#63]: https://github.com/jsx-eslint/eslint-plugin-react/pull/63
[#55]: https://github.com/jsx-eslint/eslint-plugin-react/pull/55
[#60]: https://github.com/jsx-eslint/eslint-plugin-react/pull/60

## [2.1.0] - 2015-04-06
### Added
* Add [`jsx-boolean-value`][] rule ([#11][])
* Add support for static methods in [`display-name`][] and [`prop-types`][] ([#48][])

### Changed
* Update [`jsx-sort-props`][] to reset the alphabetical verification on spread ([#47][] @zertosh)
* Update [`jsx-uses-vars`][] to be enabled by default ([#49][] @banderson)

### Fixed
* Fix describing comment for hasSpreadOperator() method ([#53][] @AlexKVal)

[2.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.0.2...v2.1.0
[#47]: https://github.com/jsx-eslint/eslint-plugin-react/pull/47
[#49]: https://github.com/jsx-eslint/eslint-plugin-react/pull/49
[#11]: https://github.com/jsx-eslint/eslint-plugin-react/issues/11
[#48]: https://github.com/jsx-eslint/eslint-plugin-react/issues/48
[#53]: https://github.com/jsx-eslint/eslint-plugin-react/pull/53

## [2.0.2] - 2015-03-31
### Fixed
* Fix ignore rest spread when destructuring props ([#46][])
* Fix component detection in [`prop-types`][] and [`display-name`][] ([#45][])
* Fix spread handling in [`jsx-sort-props`][] ([#42][] @zertosh)

[2.0.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.0.1...v2.0.2
[#46]: https://github.com/jsx-eslint/eslint-plugin-react/issues/46
[#45]: https://github.com/jsx-eslint/eslint-plugin-react/issues/45
[#42]: https://github.com/jsx-eslint/eslint-plugin-react/pull/42

## [2.0.1] - 2015-03-30
### Fixed
* Fix props detection when used in an object ([#41][])

[2.0.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v2.0.0...v2.0.1
[#41]: https://github.com/jsx-eslint/eslint-plugin-react/issues/41

## [2.0.0] - 2015-03-29
### Added
* Add [`jsx-sort-props`][] rule ([#16][])
* Add [`no-unknown-property`][] rule ([#28][])
* Add ignore option to [`prop-types`][] rule

### Changed
* Update dependencies

### Breaking
* In [`prop-types`][] the children prop is no longer ignored

### Fixed
* Fix components are now detected when using ES6 classes ([#24][])
* Fix [`prop-types`][] now return the right line/column ([#33][])
* Fix props are now detected when destructuring ([#27][])
* Fix only check for computed property names in [`prop-types`][] ([#36][] @burnnat)

[2.0.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.6.1...v2.0.0
[#16]: https://github.com/jsx-eslint/eslint-plugin-react/issues/16
[#28]: https://github.com/jsx-eslint/eslint-plugin-react/issues/28
[#24]: https://github.com/jsx-eslint/eslint-plugin-react/issues/24
[#33]: https://github.com/jsx-eslint/eslint-plugin-react/issues/33
[#27]: https://github.com/jsx-eslint/eslint-plugin-react/issues/27
[#36]: https://github.com/jsx-eslint/eslint-plugin-react/pull/36

## [1.6.1] - 2015-03-25
### Changed
* Update `jsx-quotes` documentation

### Fixed
* Fix [`jsx-no-undef`][] with `babel-eslint` ([#30][])
* Fix `jsx-quotes` on Literal childs ([#29][])

[1.6.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.6.0...v1.6.1
[#30]: https://github.com/jsx-eslint/eslint-plugin-react/issues/30
[#29]: https://github.com/jsx-eslint/eslint-plugin-react/issues/29

## [1.6.0] - 2015-03-22
### Added
* Add [`jsx-no-undef`][] rule
* Add `jsx-quotes` rule ([#12][])
* Add `@jsx` pragma support ([#23][])

### Changed
* Allow `this.getState` references (not calls) in lifecycle methods ([#22][] @benmosher)
* Update dependencies

### Fixed
* Fix [`react-in-jsx-scope`][] in Node.js env
* Fix usage of propTypes with an external object ([#9][])

[1.6.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.5.0...v1.6.0
[#12]: https://github.com/jsx-eslint/eslint-plugin-react/issues/12
[#23]: https://github.com/jsx-eslint/eslint-plugin-react/issues/23
[#9]: https://github.com/jsx-eslint/eslint-plugin-react/issues/9
[#22]: https://github.com/jsx-eslint/eslint-plugin-react/pull/22

## [1.5.0] - 2015-03-14
### Added
* Add [`jsx-uses-vars`][] rule

### Fixed
* Fix [`jsx-uses-react`][] for ESLint 0.17.0

[1.5.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.4.1...v1.5.0

## [1.4.1] - 2015-03-03
### Fixed
* Fix `this.props.children` marked as missing in props validation ([#7][])
* Fix usage of `this.props` without property ([#8][])

[1.4.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.4.0...v1.4.1
[#7]: https://github.com/jsx-eslint/eslint-plugin-react/issues/7
[#8]: https://github.com/jsx-eslint/eslint-plugin-react/issues/8

## [1.4.0] - 2015-02-24
### Added
* Add [`react-in-jsx-scope`][] rule ([#5][] @glenjamin)
* Add [`jsx-uses-react`][] rule ([#6][] @glenjamin)

### Changed
* Update [`prop-types`][] to check props usage insead of propTypes presence ([#4][])

[1.4.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.3.0...v1.4.0
[#4]: https://github.com/jsx-eslint/eslint-plugin-react/issues/4
[#5]: https://github.com/jsx-eslint/eslint-plugin-react/pull/5
[#6]: https://github.com/jsx-eslint/eslint-plugin-react/pull/6

## [1.3.0] - 2015-02-24
### Added
* Add [`no-did-mount-set-state`][] rule
* Add [`no-did-update-set-state`][] rule

### Changed
* Update dependencies

[1.3.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.2.2...v1.3.0

## [1.2.2] - 2015-02-09
### Changed
* Update dependencies

### Fixed
* Fix childs detection in [`self-closing-comp`][] ([#3][])

[1.2.2]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.2.1...v1.2.2
[#3]: https://github.com/jsx-eslint/eslint-plugin-react/issues/3

## [1.2.1] - 2015-01-29
### Changed
* Update Readme
* Update dependencies
* Update [`wrap-multilines`][] and [`self-closing-comp`][] rules for ESLint 0.13.0

[1.2.1]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.2.0...v1.2.1

## [1.2.0] - 2014-12-29
### Added
* Add [`self-closing-comp`][] rule

### Fixed
* Fix [`display-name`][] and [`prop-types`][] rules

[1.2.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.1.0...v1.2.0

## [1.1.0] - 2014-12-28
### Added
 * Add [`display-name`][] rule
 * Add [`wrap-multilines`][] rule
 * Add rules documentation
 * Add rules tests

[1.1.0]: https://github.com/jsx-eslint/eslint-plugin-react/compare/v1.0.0...v1.1.0

## 1.0.0 - 2014-12-16
### Added
 * First revision

[`react/jsx-runtime`]: https://github.com/jsx-eslint/eslint-plugin-react/blob/HEAD/index.js#L163-L176

[`boolean-prop-naming`]: docs/rules/boolean-prop-naming.md
[`button-has-type`]: docs/rules/button-has-type.md
[`checked-requires-onchange-or-readonly`]: docs/rules/checked-requires-onchange-or-readonly.md
[`default-props-match-prop-types`]: docs/rules/default-props-match-prop-types.md
[`destructuring-assignment`]: docs/rules/destructuring-assignment.md
[`display-name`]: docs/rules/display-name.md
[`forbid-component-props`]: docs/rules/forbid-component-props.md
[`forbid-dom-props`]: docs/rules/forbid-dom-props.md
[`forbid-elements`]: docs/rules/forbid-elements.md
[`forbid-foreign-prop-types`]: docs/rules/forbid-foreign-prop-types.md
[`forbid-prop-types`]: docs/rules/forbid-prop-types.md
[`forward-ref-uses-ref`]: docs/rules/forward-ref-uses-ref.md
[`function-component-definition`]: docs/rules/function-component-definition.md
[`hook-use-state`]: docs/rules/hook-use-state.md
[`iframe-missing-sandbox`]: docs/rules/iframe-missing-sandbox.md
[`jsx-boolean-value`]: docs/rules/jsx-boolean-value.md
[`jsx-child-element-spacing`]: docs/rules/jsx-child-element-spacing.md
[`jsx-closing-bracket-location`]: docs/rules/jsx-closing-bracket-location.md
[`jsx-closing-tag-location`]: docs/rules/jsx-closing-tag-location.md
[`jsx-curly-brace-presence`]: docs/rules/jsx-curly-brace-presence.md
[`jsx-curly-newline`]: docs/rules/jsx-curly-newline.md
[`jsx-curly-spacing`]: docs/rules/jsx-curly-spacing.md
[`jsx-equals-spacing`]: docs/rules/jsx-equals-spacing.md
[`jsx-filename-extension`]: docs/rules/jsx-filename-extension.md
[`jsx-first-prop-new-line`]: docs/rules/jsx-first-prop-new-line.md
[`jsx-fragments`]: docs/rules/jsx-fragments.md
[`jsx-handler-names`]: docs/rules/jsx-handler-names.md
[`jsx-indent-props`]: docs/rules/jsx-indent-props.md
[`jsx-indent`]: docs/rules/jsx-indent.md
[`jsx-key`]: docs/rules/jsx-key.md
[`jsx-max-depth`]: docs/rules/jsx-max-depth.md
[`jsx-max-props-per-line`]: docs/rules/jsx-max-props-per-line.md
[`jsx-newline`]: docs/rules/jsx-newline.md
[`jsx-no-bind`]: docs/rules/jsx-no-bind.md
[`jsx-no-comment-textnodes`]: docs/rules/jsx-no-comment-textnodes.md
[`jsx-no-constructed-context-values`]: docs/rules/jsx-no-constructed-context-values.md
[`jsx-no-duplicate-props`]: docs/rules/jsx-no-duplicate-props.md
[`jsx-no-leaked-render`]: docs/rules/jsx-no-leaked-render.md
[`jsx-no-literals`]: docs/rules/jsx-no-literals.md
[`jsx-no-script-url`]: docs/rules/jsx-no-script-url.md
[`jsx-no-target-blank`]: docs/rules/jsx-no-target-blank.md
[`jsx-no-undef`]: docs/rules/jsx-no-undef.md
[`jsx-no-useless-fragment`]: docs/rules/jsx-no-useless-fragment.md
[`jsx-one-expression-per-line`]: docs/rules/jsx-one-expression-per-line.md
[`jsx-pascal-case`]: docs/rules/jsx-pascal-case.md
[`jsx-props-no-multi-spaces`]: docs/rules/jsx-props-no-multi-spaces.md
[`jsx-props-no-spread-multi`]: docs/rules/jsx-props-no-spread-multi.md
[`jsx-props-no-spreading`]: docs/rules/jsx-props-no-spreading.md
[`jsx-props-no-spreading`]: docs/rules/jsx-props-no-spreading.md
[`jsx-sort-default-props`]: docs/rules/jsx-sort-default-props.md
[`jsx-sort-prop-types`]: docs/rules/sort-prop-types.md
[`jsx-sort-props`]: docs/rules/jsx-sort-props.md
[`jsx-space-before-closing`]: docs/rules/jsx-space-before-closing.md
[`jsx-tag-spacing`]: docs/rules/jsx-tag-spacing.md
[`jsx-uses-react`]: docs/rules/jsx-uses-react.md
[`jsx-uses-vars`]: docs/rules/jsx-uses-vars.md
[`jsx-wrap-multilines`]: docs/rules/jsx-wrap-multilines.md
[`no-access-state-in-setstate`]: docs/rules/no-access-state-in-setstate.md
[`no-adjacent-inline-elements`]: docs/rules/no-adjacent-inline-elements.md
[`no-array-index-key`]: docs/rules/no-array-index-key.md
[`no-arrow-function-lifecycle`]: docs/rules/no-arrow-function-lifecycle.md
[`no-children-prop`]: docs/rules/no-children-prop.md
[`no-comment-textnodes`]: docs/rules/jsx-no-comment-textnodes.md
[`no-danger-with-children`]: docs/rules/no-danger-with-children.md
[`no-danger`]: docs/rules/no-danger.md
[`no-deprecated`]: docs/rules/no-deprecated.md
[`no-did-mount-set-state`]: docs/rules/no-did-mount-set-state.md
[`no-did-update-set-state`]: docs/rules/no-did-update-set-state.md
[`no-direct-mutation-state`]: docs/rules/no-direct-mutation-state.md
[`no-find-dom-node`]: docs/rules/no-find-dom-node.md
[`no-invalid-html-attribute`]: docs/rules/no-invalid-html-attribute.md
[`no-is-mounted`]: docs/rules/no-is-mounted.md
[`no-multi-comp`]: docs/rules/no-multi-comp.md
[`no-namespace`]: docs/rules/no-namespace.md
[`no-object-type-as-default-prop`]: docs/rules/no-object-type-as-default-prop.md
[`no-redundant-should-component-update`]: docs/rules/no-redundant-should-component-update.md
[`no-render-return-value`]: docs/rules/no-render-return-value.md
[`no-set-state`]: docs/rules/no-set-state.md
[`no-string-refs`]: docs/rules/no-string-refs.md
[`no-this-in-sfc`]: docs/rules/no-this-in-sfc.md
[`no-typos`]: docs/rules/no-typos.md
[`no-unescaped-entities`]: docs/rules/no-unescaped-entities.md
[`no-unknown-property`]: docs/rules/no-unknown-property.md
[`no-unsafe`]: docs/rules/no-unsafe.md
[`no-unstable-nested-components`]: docs/rules/no-unstable-nested-components.md
[`no-unused-class-component-methods`]: docs/rules/no-unused-class-component-methods.md
[`no-unused-prop-types`]: docs/rules/no-unused-prop-types.md
[`no-unused-state`]: docs/rules/no-unused-state.md
[`no-will-update-set-state`]: docs/rules/no-will-update-set-state.md
[`prefer-es6-class`]: docs/rules/prefer-es6-class.md
[`prefer-exact-props`]: docs/rules/prefer-exact-props.md
[`prefer-read-only-props`]: docs/rules/prefer-read-only-props.md
[`prefer-stateless-function`]: docs/rules/prefer-stateless-function.md
[`prop-types`]: docs/rules/prop-types.md
[`react-in-jsx-scope`]: docs/rules/react-in-jsx-scope.md
[`require-default-props`]: docs/rules/require-default-props.md
[`require-extension`]: docs/rules/require-extension.md
[`require-optimization`]: docs/rules/require-optimization.md
[`require-render-return`]: docs/rules/require-render-return.md
[`self-closing-comp`]: docs/rules/self-closing-comp.md
[`sort-comp`]: docs/rules/sort-comp.md
[`sort-default-props`]: docs/rules/sort-default-props.md
[`sort-prop-types`]: docs/rules/sort-prop-types.md
[`state-in-constructor`]: docs/rules/state-in-constructor.md
[`static-property-placement`]: docs/rules/static-property-placement.md
[`style-prop-object`]: docs/rules/style-prop-object.md
[`void-dom-elements-no-children`]: docs/rules/void-dom-elements-no-children.md
[`wrap-multilines`]: docs/rules/jsx-wrap-multilines.md
