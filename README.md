# iOS Widget for Dating App(Warm Tribe)

This repository contains a WidgetKit extension for an iOS dating app.  
The widget displays featured streamers, a quick access to search, and recharge options.

## ✨ Features

- Show 3 featured streamers with profile images and names  
- Tap to open streamer profile  
- Provide quick access to search  
- Shortcut to the recharge feature  

## 📱 Requirements

- iOS 14 or later  
- Built using **Swift** and **WidgetKit**  
- Supports multiple widget sizes: `systemSmall`, `systemMedium`

## 📂 Project Structure

```
Widgets/
├── WidgetsExtension/
│   ├── Widgets.swift
│   ├── Provider.swift
│   ├── WidgetEntry.swift
│   ├── WidgetView.swift
│   └── Assets.xcassets
├── App/
├── Shared/
└── README.md
```

## Project Context

This widget was originally built as part of a commercial iOS app
and later extracted as a standalone WidgetKit example for reference.
It reflects how I approach lightweight, production-oriented iOS components.

## Design Notes

The widget intentionally keeps its UI and feature scope lightweight,
which aligns with typical WidgetKit usage and system constraints,
such as limited refresh control and performance considerations.

## Testing Notes

This project does not include automated tests, mainly due to its lightweight
WidgetKit scope and UI-driven nature.

In production, I usually focus automated testing on business logic and data
handling using XCTest, rather than UI-heavy widget components.

## Note on Comments

Some inline comments are written in Chinese, reflecting the original development context of the project.

## ⚠️ Note

This is a **Widget Extension only** and cannot run independently.  
To test or run the widget, integrate it into the main iOS app and launch from the main target.

![54d1a69019418a8f4bae9931ea3f6424](https://github.com/user-attachments/assets/3da98be5-35c2-4aff-8b2a-4037b14c7031)






