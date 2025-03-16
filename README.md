# Supporting Regular Thunderbird Extension Developers

(*This repository has recently been forked and is undergoing changes! Some of it is WIP.*)
The goal of this repository is to provide useful information, code snippets, examples, scripts, APIs and tools to developers and maintainers of regular extensions for [Thunderbird](https://www.thunderbird.net/en-US/) and [BetterBird](https://betterbird.eu/), using Thunderbird's full internal API.

## Content

(TO BE REWRITTEN)

&nbsp;

## Introduction to Regular extensions, MailExtensions, WebExtension APIs and Experiments

(TO BE WRITTEN)

&nbsp;


## Loading a regular extensions through a MailExtensions

The different methods to update [legacy add-ons](https://developer.thunderbird.net/add-ons/about-add-ons#legacy-extension-types) are covered in the Thunderbird project's [Thunderbird add-on update guide](https://developer.thunderbird.net/add-ons/updating/tb78). It tries to steer you in the direction of 'MailExtensions', but still describes how your extension can be loaded, with limited modifications, in newer versions of Thunderbird, using the following resources:


|      | Description |
| ---- | ---- |
| [WindowListener API](https://github.com/thunderbird/addon-developer-support/wiki) | A regular extension loading mechanism, in the form of a WebExtension 'Experiment API'. It lets go to simplify the process to update legacy add-ons to MailExtensions. |
| [BootstrapLoader API](wrapper-apis/BootstrapLoader)) | A simpler loader, for 'Bootstap' Thunderbird extensions before version 68. *This loader is not currently maintained and likely to fail for newer Thunderbird versions (e.g. v128 and later). Please try using the WindowListener API to load your extension - that should be possible; otherwise consider helping in updating/maintaining this API.** |
| Update Tutorials | These were removed from the original repository's wiki; can you help access them? Open an issue or a PR. |
| [Scripts](scripts/)        | Scripts used by conversion steps after the initial update using the wrapper APIs. |
| [Tools](tools/)          | Tools to help developers update their add-ons more easily. |
| [UI](ui/)          | 3rd party libraries which can help to replace deprecated XUL elements. |

## Questions? Suggestions? Bug reports?

Please file an [issue](https://github.com/eyalroz/tb-extension-devel-support/issues).
