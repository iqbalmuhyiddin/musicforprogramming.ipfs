# musicForProgramming("Changelog")

This project tries to follow [SemVer 2.0.0](https://semver.org/).

<!--
	When composing new changes to this list, try to follow convention.

	The WIP release shall be updated just before adding the Git tag.
	From (WIP) to (YYYY-MM-DD), ex: (2021-02-09) for 9th of Febuary, 2021

	A good source on conventions can be found here:
	https://changelog.md/
-->

## v1.2.0 (WIP)

- Changed episode routing from `?one` & `?two` to `?episode=1` & `?episode=2`.
  Old URLs are still supported, although not used in episode link list.
  (#10, thanks @DvdQzd!)

- Added `LICENSE` to IPFS directory & license notice to `build/bundle.js`. (#11)

## v1.1.0 (2021-10-04)

- Changed from `.mp3` files to `.ogg` files, reducing the size down to almost
  40%, dropping size of all audio files combined from 7GB to 3GB (#9)

## v1.0.1 (2021-10-01)

- Fixed file size doesn't update when switching page. (#1)

## v1.0.0 (2021-09-27)

- Added features, ported from musicforprogramming.net:

  - All 62 episodes
  - Responsive layout
  - Audio player
  - Episode page
  - Credits page
  - About page
  - `<a>` tags with special styling when on their current page

- Added History.pushState navigation, meaning no page reloads when navigation.
