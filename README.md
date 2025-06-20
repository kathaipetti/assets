# 📦 KathaiPetti Local Assets Repository

This repository is used to serve **publicly accessible URLs** for **local assets** (images and audio) required by the **KathaiPetti** application when running in **local mode**.

## 🚀 Purpose

The main goal of this repository is to offload local static assets such as images and audio files to a centralized, lightweight public location. This approach:

- ✅ Reduces the overall weight of the application bundle
- ✅ Simplifies asset management and updates
- ✅ Allows seamless access to resources in development and testing environments

## 📂 Structure

Assets in this repository are organized by type:
```
/images/
└── story1.png
└── story2.jpg

/audio/
└── intro.mp3
└── story-audio-1.mp3
```



You can reference any of these files via raw GitHub URLs or CDN services like jsDelivr or GitHub's own raw content delivery.

### Example usage in code:

```dart
final imageUrl = "https://raw.githubusercontent.com/your-username/your-repo/main/images/story1.png";
final audioUrl = "https://raw.githubusercontent.com/your-username/your-repo/main/audio/story-audio-1.mp3";
```
