# ISMPlugin

###Instanced Static Mesh Combining in the UE4 Editor

Based on the changes in Rama's [UE4 PR](https://github.com/EpicGames/UnrealEngine/pull/917).  Created because
 I needed the functionality, but didn't want to deal with compiling the engine from source and integrating the code.

To use this plugin, simply clone the ISMProject folder into a UE4 C++ enabled project like so:
```
  My Project\
    Content\
    Intermediate\
    Plugins\
      ISMPlugin\
        Resources\
        Source\
        ISMPlugin.uplugin
    Source\
    MyProject.uproject
```
And then compile the project.  From there, you can make it an engine-wide project by
copying the ISMPlugin folder into your `Unreal Engine/4.xx/Engine/Plugins/Editor` folder.