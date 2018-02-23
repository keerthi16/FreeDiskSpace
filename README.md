# FreeDiskSpace
A simple utility for windows which return free disk space available for the given partition.

Note: application requires .NET 3.5 framework (or higher).

# Command line:
FreeDiskSpace.exe diskName (FreeDiskSpace.exe "C")

# Dev Env Notes:
preinstall script in package.json will build release version of package.  MSBuild.exe must be in path to build.  MSBuild.exe is available when installing Visual Studio.