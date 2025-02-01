# Simple Video App with ExoPlayer & Media3

## Overview
This project demonstrates the use of **ExoPlayer** for video playback and **Media3** for managing media sources, combined with **Dagger/Hilt** for Dependency Injection (DI). The app allows users to:
- Add a video to the app
- Play a single video
- Create and manage a playlist to add multiple videos and play them sequentially

## Technologies Used
- **Dagger/Hilt**: Dependency Injection (DI) framework for Android, making it easier to manage dependencies throughout the app.
- **ExoPlayer**: A powerful media player for Android that supports various formats, streaming, and video playback.
- **Media3**: Android’s new media framework that simplifies media playback, used in combination with ExoPlayer.
- **Kotlin**: The preferred language for Android development.
- **Jetpack Compose**: UI toolkit to create the user interface.

## Features
- **Video Playback**: Play video files from local storage or URLs using ExoPlayer.
- **Playlist Management**: Create and manage a playlist of videos and switch between them.
- **Dependency Injection**: Uses Dagger/Hilt for injecting dependencies like ExoPlayer instances and playlist manager.
- **UI with Jetpack Compose**: Clean, modern UI with Compose for showing video and playlist controls.
