# Change Log

## 2022-01-29, 0.5.0 release

* Use logarithm to calculate the height of the bars.

## 2022-01-09, 0.4.0 release

* Added night green version.

## 2021-12-22, 0.3.1 release

* Changed the maximum number of contributors to 9999

## 2021-12-22, 0.3.0 release

* Added season version for the Southern Hemisphere.
* Added night view version.
* Added night rainbow version.

## 2021-05-11, 0.2.0 release

* The repositories to be aggregated are only those owned by the user.
* Allow the number of repositories to be aggregated to be defined by environment variables.
  * `MAX_REPOS` : (optional) max repositories, default 100
* Make the colors of the four seasons mode every week and make a gradation.
  * The image colors of each season are as follows.
    * spring flowers
    * summer leaves
    * autumn leaves
    * winter snow
* Label the radar chart scale with "1-, 10, 100, 1K, 10K+".
* Supports Halloween mode on github.
* The USERNAME can also be specified from the argument.
  * Usage: `node dist/index.js <USER-NAME>` without env `USERNAME`

## 2021-05-09, 0.1.0 release

First release.
