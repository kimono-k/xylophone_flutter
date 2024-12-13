# Xylophone App

https://github.com/user-attachments/assets/d6404627-0402-4469-9432-b88c4a4260e5


A simple Flutter application that plays musical notes like a xylophone when you tap on colored keys. This app demonstrates the use of Flutter's widget system and the `audioplayers` package to create an interactive and engaging user interface.

## Features

- **Interactive Keys**: A vertical stack of colored keys, each corresponding to a musical note.
- **Sound Playback**: Plays a unique sound for each key press using the `audioplayers` package.
- **Simple UI**: Clean and minimalistic design with a black background and vibrant keys.

## How It Works

- Each key is represented by a `TextButton` widget, styled with a specific color and linked to a sound file.
- The `playSound` function is used to play audio when a key is tapped. It utilizes the `AudioPlayer` class from the `audioplayers` package.
- The `buildKey` method dynamically creates keys with the required color and sound mapping, making the code reusable and scalable.
