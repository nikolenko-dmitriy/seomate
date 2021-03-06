# SEOMate Changelog

## 1.1.4 - 2020-04-12

### Fixed
- Fixed an issue with encoding of meta attributes. Fixes #39.

## 1.1.3 - 2020-03-02

### Fixed
- Fixed a caching issue with native image transforms and `generateTransformsBeforePageLoad`. Fixes #35.

## 1.1.2 - 2020-02-17
### Added
- Added `craft.seomate.getMeta()` template variable that returns meta data based on the current page. Takes an seomate config object for additional configuration. Fixes #31.
- Added support for Imager X.

### Fixed
- Fixed an issue where seomate would throw an exception if a value in `defaultMeta` did not exist in the context. Fixes #24.

## 1.1.1 - 2019-09-21
### Fixed
- Fixes indentation and whitespace issues in default meta template. Fixes #22.
- The "SEO Preview" Preview Target is no longer available when editing entries without URLs

## 1.1.0 - 2019-08-10
### Added
- Added new `previewLabel` config setting
- Added SEO Preview as a Preview Target for Craft 3.2+. Fixes #16.

## 1.0.7 - 2019-07-04
### Added
- Added support for configuring custom sitemaps urls and additional sitemap urls on a per site basis.
- Added support for adding additional sitemaps, generated outside of SEOMate, to the main sitemap index (Thanks @jrm98). 

## 1.0.6 - 2019-07-04
### Fixed
- Fixes an issue where the "Close SEO Preview" button label could be applied to buttons inside the field panel in SEO Preview (fixes #13)

## 1.0.5 - 2019-07-03
### Added
- Added SEO Preview for Craft Commerce Products

### Changed
- Changed the behaviour of the output meta template, empty tags are no longer being rendered.

### Fixed
- Fixes an issue where elements without urls in some sites would create an error when getting alternate url (fixes #10)
- Fixes an issue where the "SEO Preview" button was missing for Entries in Craft 3.2.x (fixes #12)

## 1.0.4 - 2019-07-01
### Fixed
- Fixes an issue where SEO Preview settings could override native Live Preview settings (fixes #7). 

## 1.0.3 - 2019-06-30
### Added
- Added support for using matrix field syntax in `defaultMeta` (fixes #9). 

## 1.0.2 - 2019-05-19
### Fixed
- Fixed missing multi-byte handling of maxLength enforcement (Thanks @rungta). 
- Fixed namespace for PreviewAsset class (Thanks @Mosnar). 

## 1.0.1 - 2019-04-30
### Changed
- Changed order of when additional meta is added to make it overrideable from templates (Fixes #2). 

## 1.0.0 - 2019-04-26
### Added
- Initial public release
