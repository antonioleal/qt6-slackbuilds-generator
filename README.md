# Qt6 SlackBuilds Generator 

This program generates a set of SlackBuilds that build Qt6 as separate modules allowing you to have smaller and more controlled Qt6 builds. This is particular useful if you have a slow computer or need just a small subset on Qt. In any case the remaining packages can be build later as needed.

These packages depend on *cmake-opt* available at SlackBuils.org. Install it before continuing below.

Once *cmake-opt* is installed run in order:

1st the **downloader** to download the source packages from http://qt.io into the folder 'downloads'

2nd the **generator** to generate the SlackBuilds themselves in the 'output' folder.

Finally run **builder** to determine the dependencies required for the specific Qt package you need. The builder script will also allow you to build and install these.