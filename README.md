# Unity - Asset Dependency Graph 

New License and Contribution Guidelines: 28/10/2020

This project provides a basic Asset Dependency Graph for Unity using the new [GraphView](https://docs.unity3d.com/2019.2/Documentation/ScriptReference/Experimental.GraphView.GraphView.html) API.

![](Images~/Example.png?raw=true)

## Install instructions
### Method 1
1. Open the Unity project you want to install this package in.
2. Open the Package Manager window.
3. Click on the `+` button and select `Add package from git URL...`.
4. Paste the URL of this repo into the text field and press `Add`.

### Method 2
1. Close Unity and open the `Packages/manifest.json` file
2. Add `"com.harryrose.assetdependencygraph": "https://github.com/Unity-Harry/Unity-AssetDependencyGraph.git",` to the `dependencies` section

## Usage

The Asset Dependency Graph Window can be opened via the `SOSXR > Analysis >Asset Dependency Graph` file menu

![](Images~/Usage.png?raw=true)

Once the window is open:
1. Select the root asset you want to inspect in the Project window
2. Click the `Explore Asset` button in the graph window

Any questions? Ask [@peanutbuffer](https://twitter.com/PeanutBuffer)

## Tested against
2022.3, 2019.2, 2019.1, 2018.4, 2018.3
