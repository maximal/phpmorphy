phpMorphy
========

phpMorphy is morphological analyzer library for Russian, English and German languages.

 * Website (in Russian): http://phpmorphy.sourceforge.net/
 * SF project: http://sourceforge.net/projects/phpmorphy


This library allows to retrieve following morph information for any word:
 * base (normal) form;
 * all forms;
 * grammatical (part of speech, grammems) information.

## Speed
### Single word mode

| mode          | base form       | all forms     | all forms with gram. info |
|:------------- | ---------------:| -------------:| -------------------------:|
| FILE          | 1000            |  800          | 600                       |
| SHM           | 2200            | 1100          | 800                       |
| MEM           | 2500            | 1200          | 900                       |


### Bulk mode:

| mode          | base form       | all forms     | all forms with gram. info |
|:------------- | ---------------:| -------------:| -------------------------:|
| FILE          | 1700            | 800           | 700                       |
| SHM           | 3200            | 800           | 700                       |
| MEM           | 3500            | 800           | 700                       |


Note: 
> All values are words per second speed.
> Test platform: PHP 5.2.3, AMD Duron 800 with 512Mb memory, WinXP.


## Installation

See [INSTALL.md](INSTALL.md) file in current directory.

## Usage

See example in `./examples` directory.
