# Pocket Launcher

**A small, searchable home for the things I actually open on Windows.**

## The problem

My shortcuts were already on the laptop. Finding the right one was the part that needed a better interface.

The original request was simple: collect them in one small app, let me search, and make adding another shortcut as easy as choosing a file or pasting its path.

## The solution

A Windows launcher for apps, files, folders, websites, and existing shortcuts, with a light card-based interface and a locally stored library.

## What it does

- Search across shortcut names and paths.
- Categories, favorites, and real application icons.
- Add by typed path, Browse, and supported import routes.
- Edit names/targets and reveal an item in its folder.
- Duplicate handling, library validation, and backup-aware saving.
- Windows Send to -> Add to Pocket integration.

## Engineering highlights

The details matter for a launcher: preserving shortcut arguments, keeping originals intact, caching icons so startup does not wait for every tile, and restoring one existing window instead of starting competing library writers.

## Technology

PowerShell, C#, WPF, Windows shortcut/icon APIs, local JSON library.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
