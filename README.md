# Support-Unity Memory Profiler Extension
Extension for the existing Unity memory profiler project, this is a WIP project which uses as a base the Memory Profiler project found in https://bitbucket.org/Unity-Technologies/memoryprofiler and uses the new memory profiler API introduced in Unity5.3a4, adding filters and search options with a node viewer for the objects and their references.

* Requires Unity 5.6 or newer in order to use the filters and table views
* Requires a IL2CPP build
* It uses the same snapshots taken with the Memory Profiler project from bitbucket (You can use as an example memory snapshot which is included in the repository)
* It's recommended to read snapshots taken from the same Unity version (for example analyse 5.6 snapshots using 5.6 editor,etc) 

![Alt text](/Documentation/Images/TreeView.jpg?raw=true "Memory Profiler Tree/Node Window")
![Alt text](/Documentation/Images/HeapView.jpg?raw=true "Memory Profiler Heap Window")

