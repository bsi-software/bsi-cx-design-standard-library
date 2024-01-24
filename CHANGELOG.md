# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.1] - 24.01.2024

### changes
* Prevent endless loop in the phone number element, which used to cause landingpages/websites to crash in the previous release (#372595)
* Proper translation of date picker (#371869)
* Make slot finder texts configurable and translatable (#371869)
* Make webcam image element translatable on configuration level (#368259)
* Upgrade dependencies

[1.4.1]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.4.1

## [1.4.0] - 15.01.2024

**Known issue with this release**
We do not recommend to use this release as it will cause the page to crash as soon as the phone number content element is included. Please upgrade to the next patch release (1.4.1) to resolve this issue.

### Important Change
We are now using the [CSP Distribution of Alpine.js](https://alpinejs.dev/advanced/csp). Thus, developers my no longer use any inline JavaScript in HTML/TWIG files associated with Alpine. Instead, there must always be a reference pointing to an associated alpine data object. We changed the implementation of a couple of components to comply with this new rule. The advantage of it is that content elements using Alpine.js are now shown properly in the 'Preview' mode of the content editor and in live mode without having to change the CSP settings. By using de CSP distribution of Alpine.js, it is no longer required to add `usafe-eval` to the CSP, which helps to increase security (#355743).

### Additional changes
* New style to display a button as a link (#357481)
* Remove unused caption for logo element (#364438)
* New style to use a fixed width for the header image element (#365087)
* Additonal spacer options (#365087)
* Better description for banner and header image (#365087)
* Replace Twitter with X, fix typo in YouTube (@#371665)
* Prevent from chosing the wrong input type for poll element (#355743)
* Upgrade dependencies

[1.4.0]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.4.0

## [1.3.0] - 04.12.2023

### Added
* Slot finder element
* Tooltips for info text in forms

### Changed
* Improved accessibility
* Format placeholder for form fields of type date and time

[1.3.0]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.3.0

## [1.2.3] - 22.09.2023

### Changed
* Fixed bug due to circle dependency
* Updated dependencies

[1.2.3]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.2.3

## [1.2.2] - 11.08.2023

Improvements:
* #358866 - always use latest flags - prevent import issues

[1.2.2]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.2.2


## [1.2.1] - 11.08.2023

New feature:
* An **Accordion** content element has been added


Improvements:
* #354376 - Allow manual date/time picker input
* #352221 - fix chart color access
* #358223 - fix form style for floating labels
* fix radio element with sharp style
* Dependencies updated

[1.2.1]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.2.1


## [1.2.0] - 15.03.2023

New feature:
* New content element to capture an image by accessing the camera. The camera to be accessed (front or back) is configurable. A fallback mode allows to upload in image manually, when camera access is impossible.

Improvements:
* A bug (#342733) has been fixed which prevented from using the telephone number field multiple times

[1.2.0]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.2.0


## [1.1.5] - 16.02.2023

### Changed

Improvements:
* This package is now available on NPM
* Updated dependencies

[1.1.5]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.5


## [1.1.4] - 03.02.2023

### Changed

Improvements:
* Updated news snippet element in order to solve validation error in CX story.
* Updated dependencies and solved security issues.

[1.1.4]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.4

## [1.1.3] - 09.12.2022

### Changed

Improvements:
* Updated style to swap the order of columns (of the two column element) not only on mobile devices.
* Solved security issues.

[1.1.3]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.3

## [1.1.2] - 04.11.2022

### Changed

New feature:
* Add style to swap the order of columns on mobile devices:
In a two-column element (e.g. with text in the left column and an image in the right column), a style can be set so that the order of the columns is swapped only on mobile devices. This enables the image to be displayed above the text in mobile view, even if the image remains in the right column in the desktop view.

Improvements:
* Update labels of spacer style

[1.1.2]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.2


## [1.1.1] - 21.10.2022

### Changed

Quality improvements:
* column elements: fix non-working column ratio style
* banner element: fix opacity issue
* text element: fix font size style
* form elements: empty info text by default (instead of lorem ipsum...)

[1.1.1]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.1

## [1.1.0] - 23.08.2022

### Changed

Refactoring of content elements:
* Use include instead of element.render(). For detailed information, visit migration guide: https://github.com/bsi-software/bsi-cx-design-master-template-web/blob/main/MIGRATION_GUIDE.md
* Extension of variables to overwrite and the use of properties.

[1.1.0]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.1.0


## [1.0.5] - 22.07.2022

### Changed

* fix form poll element

[1.0.5]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.5



## [1.0.4] - 19.07.2022

### Changed

* change form poll element to numeric output

[1.0.4]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.4


## [1.0.3] - 15.07.2022

### Changed

* add form type field, update design build dependency

[1.0.3]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.3


## [1.0.2] - 08.06.2022

### Changed

* add german labels

[1.0.2]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.2


## [1.0.1] - 27.05.2022

### Changed

* update repository title, add twig blocks in dropzones

[1.0.1]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.1


## [1.0.0] - 25.05.2022

### Added

* Standard library for CX designs.

[1.0.0]: https://github.com/bsi-software/bsi-cx-design-standard-library-web/releases/tag/1.0.0
