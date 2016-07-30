# x64dbg plugin template for Visual Studio

A C++ template for creating x64dbg plugins (x86 or x64) via Visual Studio

The template was created and tested with Visual Studio 2013, but may work with other versions.

## How to install and use

* Download the latest release of the x64dbg plugin template for Visual Studio, found [here](https://github.com/mrfearless/x64dbg-plugin-template-for-visual-studio/releases)
* Copy `x64dbg_plugin.zip` to the `My Documents\Visual Studio 2013\Templates\ProjectTemplates` folder
* Create a new project in Visual Studio 2013
* Select x64bg plugin as the template
* Specify name for your project and optionally location or accept defaults.
* Copy the contents of the `pluginsdk` folder from the latest snapshot of x64dbg into the project's `pluginsdk` folder that has been generated, see below for an example of where this folder is located in relation to your main projects folder.

## Example

Assuming the default projects location is `My Documents\Visual Studio 2013\Projects`, if you created a `testplugin` project it should have created a structure like so:

Root Projects Folder: `My Documents\Visual Studio 2013\Projects`

```
testplugin
  -- testplugin
     -- pluginsdk
```

Copy the contents of the `pluginsdk` folder from the latest snapshot of x64dbg into the project's `pluginsdk` folder. 
In this example: `My Documents\Visual Studio 2013\Projects\testplugin\testplugin\pluginsdk`

After compiling you may have a folder structure like so:

Root Projects Folder: `My Documents\Visual Studio 2013\Projects`

```
testplugin
  -- Bin
     -- x32
	 -- x64
  -- testplugin
     -- Debug
	 -- pluginsdk
	 -- Release
```

## x64dbg Plugin SDK For Assembler

If you prefer to use assembly language to create your x64dbg plugin, you may be interested in these, both of which come with RadASM x64dbg plugin templates:

* [x64dbg Plugin SDK for x86 Assembler](https://github.com/mrfearless/x64dbg-Plugin-SDK-For-x86-Assembler)
* [x64dbg Plugin SDK for x64 Assembler](https://github.com/mrfearless/x64dbg-Plugin-SDK-For-x64-Assembler)


## x64dbg
* [x64dbg website](http://x64dbg.com)
* [x64dbg github](https://github.com/x64dbg/x64dbg)
* [x64dbg latest release](https://github.com/x64dbg/x64dbg/releases/latest)
