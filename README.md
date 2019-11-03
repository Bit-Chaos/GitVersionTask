# GitVersionTask
test repository for demonstrating error inside GitVersionTask.

Once the project is opened inside the container, one gets the error: 

/workspaces/GitVersionTask/aspnetapp.csproj
/home/vscode/.nuget/packages/gitversiontask/5.1.1/build/GitVersionTask.targets(16,9): Error: Object reference not set to an instance of an object


```
Starting OmniSharp server at 11/3/2019, 2:32:12 PM
    Target: /workspaces/GitVersionTask

OmniSharp server started.
    Path: /home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/run
    PID: 649

[info]: OmniSharp.Stdio.Host
        Starting OmniSharp on debian 10.0 (x64)
[info]: OmniSharp.Services.DotNetCliService
        DotNetPath set to dotnet
[info]: OmniSharp.MSBuild.Discovery.MSBuildLocator
        Located 1 MSBuild instance(s)
            1: StandAlone 16.0 - "/home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild/Current/Bin"
[info]: OmniSharp.MSBuild.Discovery.MSBuildLocator
        MSBUILD_EXE_PATH environment variable set to '/home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild/Current/Bin/MSBuild.dll'
[info]: OmniSharp.MSBuild.Discovery.MSBuildLocator
        Registered MSBuild instance: StandAlone 16.0 - "/home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild/Current/Bin"
            MSBuildExtensionsPath = /home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild
            BypassFrameworkInstallChecks = true
            CscToolPath = /home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild/Current/Bin/Roslyn
            CscToolExe = csc.exe
            MSBuildToolsPath = /home/vscode/.vscode-server/extensions/ms-vscode.csharp-1.21.5/.omnisharp/1.34.5/omnisharp/.msbuild/Current/Bin
[info]: OmniSharp.Cake.CakeProjectSystem
        Detecting Cake files in '/workspaces/GitVersionTask'.
[info]: OmniSharp.Cake.CakeProjectSystem
        Could not find any Cake files
[info]: OmniSharp.MSBuild.ProjectSystem
        No solution files found in '/workspaces/GitVersionTask'
[info]: OmniSharp.MSBuild.ProjectManager
        Queue project update for '/workspaces/GitVersionTask/aspnetapp.csproj'
[info]: OmniSharp.Script.ScriptProjectSystem
        Detecting CSX files in '/workspaces/GitVersionTask'.
[info]: OmniSharp.Script.ScriptProjectSystem
        Could not find any CSX files
[info]: OmniSharp.WorkspaceInitializer
        Invoking Workspace Options Provider: OmniSharp.Roslyn.CSharp.Services.CSharpFormattingWorkspaceOptionsProvider, Order: 0
[info]: OmniSharp.MSBuild.ProjectManager
        Loading project: /workspaces/GitVersionTask/aspnetapp.csproj
[info]: OmniSharp.WorkspaceInitializer
        Invoking Workspace Options Provider: OmniSharp.Roslyn.CSharp.Services.RenameWorkspaceOptionsProvider, Order: 100
[info]: OmniSharp.WorkspaceInitializer
        Invoking Workspace Options Provider: OmniSharp.Roslyn.CSharp.Services.EditorConfigWorkspaceOptionsProvider, Order: 200
[info]: OmniSharp.WorkspaceInitializer
        Configuration finished.
[info]: OmniSharp.Stdio.Host
        Omnisharp server running using Stdio at location '/workspaces/GitVersionTask' on host 210.
[fail]: OmniSharp.MSBuild.ProjectLoader
        Object reference not set to an instance of an object
[warn]: OmniSharp.MSBuild.ProjectManager
        Failed to load project file '/workspaces/GitVersionTask/aspnetapp.csproj'.
/workspaces/GitVersionTask/aspnetapp.csproj
/home/vscode/.nuget/packages/gitversiontask/5.1.1/build/GitVersionTask.targets(16,9): Error: Object reference not set to an instance of an object

[fail]: OmniSharp.MSBuild.ProjectManager
        Attempted to update project that is not loaded: /workspaces/GitVersionTask/aspnetapp.csproj
[info]: OmniSharp.OmniSharpWorkspace
        Miscellaneous file: /workspaces/GitVersionTask/obj/Debug/netcoreapp3.0/AssemblyInfo_aspnetapp_rce4gt43.33z.g.cs added to workspace

```
