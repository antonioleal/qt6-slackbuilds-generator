# Qt6 SlackBuilds Generator 

This program generates a set of Slackware SlackBuilds to build Qt6 as separate modules. This will allow you to have smaller and more controlled Qt6 builds.

The packages depend on cmake-opt available at SlackBuils.org. Install this one first then proceed to install qt-prebuilt-environment.
Now install qt6-base that is provided as a separate SlackBuild, i.e. it is not generated.

Now run in order:

1st **qt6-slackbuilds-downloader** will download the source packages

2nd **qt6-slackbuilds-generator** will generate the SlackBuilds themselves in the 'output' folder.

Finally run **qt6-build-solution** to determine what packages are necessary and the order you should follow for your builds.