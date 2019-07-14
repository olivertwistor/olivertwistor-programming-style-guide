# How to read and use this template
The sections in this file (except this one) are intended to stay in the real *CHANGELOG.md*. Each section consists of a heading and describing text on what to write. Text within square brackets (*[* and *]*) denotes text you should replace, for example you should replace *[Version number - publish date]* with your own version number and publish date. Since this file is heavily based on [Keep a Changelog][1], you should be just fine by reading through how they have done things.

When you're done with filling each section with your own content, remove this first section (so this file starts with the heading *Changelog*). Also, rename this file to *CHANGELOG.md*.

Good luck and have fun!

# Changelog
[the two paragraphs in this section should not be removed]

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][1] and this project adheres to [Semantic Versioning 2.0.0][2].

## Unreleased
Here you may put all unreleased features, bug fixes etc, so someone who reads this file knows what to expect from the next release. It also helps you and other contributors to know what to write in the release notes when it's time for a new release. This should be formatted as a bullet point list.

If there are many items in the list, it may be helpful to have a nested list, like this:

* Added
    * [description of added feature 1]
    * [description of added feature 2]
    * ...
* Changed
    * [description of change feature 1]
    * [description of changed feature 2]
    * ...
* Deprecated
    * [description of deprecated feature 1]
    * [description of deprecated feature 2]
    * ...
* Removed
    * [description of removed feature 1]
    * [description of removed feature 2]
    * ...
* Fixed
    * [description of bug fix 1]
    * [description of bug fix 2]
    * ...

What *Added*, *Changed*, *Deprecated*, *Removed* and *Fixed* means is described in separate sections. However, if the list is short, it's more clear to write the items in one unnested list.

## [Version number of the release] - [publish date (yyyy-mm-dd)]
All headings of this type should be written in reverse chronological order, meaning that the release published most recently is the top-most one. That way it's easy to find what's changed with the newest version.

Version numbers should adhere to [Semantic Versioning 2.0.0][2]. Please follow the link to read how semantic versioning works.

Examples of how you can write this section heading:

* [1.2.0](#) - 2019-04-20
* [1.1.4](#) - 2019-04-19
* [1.0.0](#) - 2018-12-01
* [0.5.0](#) - 2018-05-30

Notice that the version numbers are links. Each version number should be linked to a place where the release can be downloaded. Since Github repositories have a releases section, linking to that is a good suggestion.

### Added
Features that have been added in this release should be listed here, in a bullet list. Please leave the description of each item rather short without being cryptic. This change log is not meant to substitute a manual, but rather to provide a quick overview of what to expect when upgrading to a new version.

For example, imagine a piece of software that lets the user input matrices and vectors, and do calculations on them. This is all well and good, but now for the latest release, the user can also visualize their matrices and vectors on a 3D plot. This new feature is likely to have a lot of settings and intricacies, something that's more appropriate to put in a manual than in a change log. With that said, "[a]ll notable changes to this project will be documented in this file", so the new feature still has to be described here, but in a shorter form.

Examples on what and how to write:

* A copyright notice is now present at the bottom of each generated page.
* The calculator has been outfitted with a graphing module. Read more about it in the [manual page on graphing](#).

### Changed
Existing features that has been changed goes here. A changed feature can both be something that's noticeable by the end-user and some change in the underlying architecture. Please note that removed features and code as well as
bug fixes should not be listed here, since they have their own sections.

Examples on what and how to write:

* Hyperlinks are no longer green and bold. They are now red and underlined, to better go with the colour scheme.
* Improved class documentation on the *Paint* class.

### Deprecated
Code that have been deprecated and thus shouldn't be used goes here. This section is important for those who use your project and are about to upgrade to a new version. Things mentioned here should serve as a guide on what users of the project need to change in order to prepare for the eventual removal of the deprecated code.

Only code that either belongs to a public API or in some other way manifests itself to users should be listed here.

Examples on what and how to write:

* The package `nu.olivertwistor.tool` shouldn't be used. All classes therein are also present in the package `nu.olivertwistor.tools`. The former package will be removed in the next version.
* The method `image::get_google_images(string $search_string) : array` can't filter out images with adult content. Please use `image::get_google_images(int $search_string, bool $safe_search) : array` instead.

### Removed
Functionality that has been removed goes here. Typically it has been in the section *Deprecated* in a previous release. The exception is if there was a serious security vulnerability that couldn't be fixed and had to be straight up removed.

Examples on what and how to write:

* Removed the ability to upload cute kittens to user profiles, due to popular demand. People were experiencing cuteness overload.
* The previously deprecated package `nu.olivertwistor.tool` is now removed.
* A vulnerability was discovered in the network module. Couldn't immediately fix it, so the whole module is removed to maintain security.

### Fixed
Bugs that have been fixed in this release goes here. In order to not let this section get unwieldy long, small and less important bug fixes don't have to be mentioned.

Examples on what and how to write:

* Fixed spelling errors in the help section.
* When the application starts, the sound effect now plays correctly.
* If the method `void Database#getConnection(String dsn)` can't connect to a database, it catches the resulting exception instead of making the application crash.


[1]: https://keepachangelog.com/en/1.0.0/
[2]: https://semver.org/
