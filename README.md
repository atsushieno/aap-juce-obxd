This is a port of an audio plugin [OB-Xd](https://github.com/reales/OB-Xd) to [aap-juce](https://github.com/atsushieno/aap-juce). See aap-juce README for details.

At this state this is nothing more than a mere port of the desktop application which is not very likely useful on Android yet. Take it more like a conceptual example port.

This repository contains JUCE as a dependency, but it is not really necessary. For now it is there because of identical build scripts with AudioPluginHost port and other apps. It may change in the future because we don't want to have copy of JUCE repo for every templated aap-juce project.

