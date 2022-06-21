# Folder structure for PHP projects
I use [Composer](https://getcomposer.org/) for all my PHP projects. I also follow [PSR-4](https://www.php-fig.org/psr/psr-4/), and thus structure my folders according to Composer's and PSR-4's standards. 

| Folder | Contents
| :-- | :--
`/` | Repository files, such as readme, licenses and main `.gitignore`. Also `composer.json` and additional build setting files.
`/config` | Configuration files for the *source code* (not the repository).
`/docs` | Documentation.
`/lib` | Libraries that aren't in a Maven repository and thus need to be imported locally into Maven.
`/resources` | Resources, such as databases and images.
`/src` | Source code.
`/tests` | Source code and resources for tests.
`/vendor` | Generated files from Composer.
