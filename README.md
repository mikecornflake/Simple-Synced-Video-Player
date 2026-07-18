# IM_Video

**Inspector Mike Video Player** is a single and multi-channel video
player designed for offshore inspection and ROV operations.

Originally developed to provide synchronised playback of multiple DVR
recordings, IM_Video has evolved into a general-purpose inspection video
player built around the excellent **mpv** media engine.

## Features

-   Single or multi-channel video playback
-   Synchronous playback of multiple video streams
-   Mouse wheel seeking with configurable fast and slow scrolling
-   Frame capture directly to the clipboard
-   Save individual frames to image files
-   Most Recently Used (MRU) file list
-   Remembers the last opened folder
-   Clean, lightweight interface
-   Playback powered by **mpv**

## Requirements

### Runtime

IM_Video requires the **mpv** runtime libraries to be installed or
distributed alongside the application.

### Build Requirements

The project is developed using **Lazarus / Free Pascal** and depends on
the following packages from the **IM_Common** repository:

-   `IM_Units.lpk`
-   `IM_Forms.lpk`
-   `IM_Forms.Media.lpk`
-   `IM_Forms.Media.mpv.lpk`

These packages provide the common framework, reusable controls and media
playback components shared across the Inspector Mike application suite.

## Playback

Media playback is provided by the excellent **mpv** project, allowing
IM_Video to support the wide range of formats handled by mpv.

## Mouse Controls

-   Mouse wheel seeking
-   Slow and fast seek modes
-   Precise frame navigation for inspection work

## Frame Capture

Individual frames may be:

-   Copied directly to the clipboard
-   Saved as image files

This makes it quick to capture evidence for reports and inspections.

## Project Status

IM_Video began life as a simple demonstration application hosting the
reusable video playback frame from the IM_Common library.

Over time it has grown into a fully featured standalone inspection video
player while continuing to showcase the reusable media framework.

## Third Party Components

### mpv

Playback is provided by the mpv media player project.

### FatCow Hosting Icons

The application uses icons from the excellent **FatCow Hosting Icons**
collection.

https://www.softicons.com/toolbar-icons/fatcow-hosting-icons-by-fatcow

Many thanks to FatCow for making these icons freely available.

## License

IM_Video is released under the **GNU General Public License (GPL)**.

See the accompanying `LICENSE` file for details.