# Qt6 SlackBuilds Generator 

This program generates a set of Slackware SlackBuilds to build Qt6 as separate modules. This will allow you to have smaller more controlled Qt6 builds.

The packages depend on cmake-opt available at SlackBuils.org. Install this one first then proceed to install qt6-base that is provided as a separate SlackBuild, i.e. it is not generated.

Now run in order:

1st **qt6-slackbuilds-downloader.sh** will download the source packages

2nd **qt6-slackbuilds-generator.sh** will generate the SlackBuilds themselves in the 'output' folder.
