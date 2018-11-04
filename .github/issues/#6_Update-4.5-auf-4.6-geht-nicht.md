# Update 4.5 auf 4.6 geht nicht

## Versionen/Zusatzinformationen
Contao: 4.5

## Ort
Contao Manager

'''php
Loading composer repositories with package information
Updating dependencies
Your requirements could not be resolved to an installable set of packages.

  Problem 1
    - Conclusion: don't install contao/listing-bundle 4.5.14
    - contao/manager-bundle 4.6.7 requires contao/core-bundle 4.6.7 -> satisfiable by contao/core-bundle[4.6.7].
    - Conclusion: don't install contao/core-bundle 4.6.7
    - contao/manager-bundle 4.6.6 requires contao/core-bundle 4.6.6 -> satisfiable by contao/core-bundle[4.6.6].
    - Conclusion: don't install contao/core-bundle 4.6.6
    - contao/manager-bundle 4.6.5 requires contao/core-bundle 4.6.5 -> satisfiable by contao/core-bundle[4.6.5].
    - Conclusion: don't install contao/core-bundle 4.6.5
    - contao/manager-bundle 4.6.4 requires contao/core-bundle 4.6.4 -> satisfiable by contao/core-bundle[4.6.4].
    - Conclusion: don't install contao/core-bundle 4.6.4
    - contao/manager-bundle 4.6.3 requires contao/core-bundle 4.6.3 -> satisfiable by contao/core-bundle[4.6.3].
    - Conclusion: don't install contao/core-bundle 4.6.3
    - contao/manager-bundle 4.6.2 requires contao/core-bundle 4.6.2 -> satisfiable by contao/core-bundle[4.6.2].
    - Conclusion: don't install contao/core-bundle 4.6.2
    - Installation request for contao/listing-bundle (locked at 4.5.14, required as ^4.5) -> satisfiable by contao/listing-bundle[4.5.14].
    - contao/manager-bundle 4.6.1 requires contao/core-bundle 4.6.1 -> satisfiable by contao/core-bundle[4.6.1].
    - Conclusion: don't install contao/core-bundle 4.6.1
    - contao/listing-bundle 4.5.14 requires contao/core-bundle 4.5.14 -> satisfiable by contao/core-bundle[4.5.14].
    - Can only install one of: contao/core-bundle[4.6.0, 4.5.14].
    - Can only install one of: contao/core-bundle[4.6.0, 4.5.14].
    - contao/manager-bundle 4.6.0 requires contao/core-bundle 4.6.0 -> satisfiable by contao/core-bundle[4.6.0].
    - Installation request for contao/manager-bundle 4.6.* -> satisfiable by contao/manager-bundle[4.6.0, 4.6.1, 4.6.2, 4.6.3, 4.6.4, 4.6.5, 4.6.6, 4.6.7].

<warning>Running update with --no-dev does not mean require-dev is ignored, it just means the packages will not be installed. If dev requirements are blocking the update you have to resolve those problems.</warning>
Finished Composer Cloud resolving.
'''

[Zum Forenthread](https://community.contao.org/de/showthread.php?72497-Update-4-5-auf-4-6-geht-nicht)

# Lösung
Es müssen alle vorhandenen Pakete erst markiert werden.