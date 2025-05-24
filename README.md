![Demo Screenshot](resources/demo.gif)

[🇰🇷 한국어로 보기](README.ko.md)

# OpenInCursor

> This project is inspired by [OpenInCode](https://github.com/sozercan/OpenInCode) and the [iTerm2 Finder Integration Guide](https://schlining.medium.com/integrate-iterm2-v-3-with-your-macs-finder-f3825acd3e0b).

OpenInCursor is a tool that allows you to instantly open the current path in Cursor editor directly from macOS Finder.

## How to Build

1. **Open Script Editor**
2. Open the script file from the `src/` folder in Script Editor
3. Select **File > Export**
4. Set **File Format** to **Application**
5. Save to your desired location to create an executable binary (.app)

You can drag the built app to the Finder toolbar for easy access.

## How to Install

1. Move the built binary file (.app) to the **Applications** folder
2. Open a Finder window and **right-click** on the toolbar area
3. Select **Customize Toolbar**
4. **Drag** OpenInCursor.app from the Applications folder to the Finder toolbar
5. Click **Done**

Now you can click the OpenInCursor icon in the toolbar from any folder in Finder to open that path in Cursor.
