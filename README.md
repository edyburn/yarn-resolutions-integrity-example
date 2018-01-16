## Example of resolutions interfering with the integrity check for `yarn install`

Run `yarn install`, then run `yarn install` again. For the second call, yarn will go through all of the installation steps even though the installation is up-to-date.

Tested with:
* yarn 1.3.2 (and 1.4.0)
* node 9.3.0
* linux 4.14 (x86_64)
