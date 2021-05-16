# NLua (Unity Package)

This repo contains [NLua](https://github.com/NLua/NLua) as a Unity package.
This repo is only for the convenience of using NLua within the [Unity game engine](https://unity.com/).

## Supported Unity Versions

**NOTE:** This package failed to compile in Unity 2018.4.35.f1, but **worked** in Unity 2019.4.26f1.

- :warning: Versions before Unity 2019.4.26f1 may not work,
- :heavy_check_mark: Versions after Unity 2019.4.26f1+ including Unity 2020.1+ should work.

## Usage

### Short Instructions

To use this project, you can download the latest tagged release OR clone locally as a Git submodule -- either way, into your Unity project _(2019.4.26+)_.

When cloning as a Git submodule, either clone from the `unity-package` branch or a tag like `v1.5.9`.

Once it's there, simply add the Unity package as a local package (from disk).

### More Detailed Instructions

To use this project, ensure you already have a version of Unity downloaded with a Unity project open.

Ensure your Unity project is using Unity 2019.4.26 or newer.

1. Download this project's tagged latest release, or clone this repo as a Git submodule.
  - If cloning as a Git submodule, use the `unity-package` branch or a tag such as `v1.5.9`.
2. Ensure the NLua (Unity package) files are within your Unity project folder structure (either _in_ or _alongside_ your `Assets/` folder)
3. In your Unity project, open the Unity Package Manager from the `Window > Package Manager` menu.
4. In the package manager, add the `+` button and choose "Add package from disk...".
5. Browse for the `package.json` file, and click Open on it.

After the above steps, Unity should now import your package.

Once Unity finishes compiling, you should be able to reference NLua code in your C# scripts, including both inside and outside of AssemblyDefinition-contained code!

## Contributing
Check out the [original NLua repo](https://github.com/NLua/NLua) if you wish to contribute!

## Suggestions & Feedback
If you have any suggestions or issues using the package in Unity, feel free to leave an issue.
