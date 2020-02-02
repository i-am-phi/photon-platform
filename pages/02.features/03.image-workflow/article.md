---
title: Image Workflow
subtitle: end to end processing
author: null
content:
  items: '@self.children'
child_type: article
figure:
  image: null
  alt: null
  title: null
  caption: null
taxonomy:
  tag: null
  category: null
---

- Four stage process from camera to web

===

# Import with Rapid Photo Downloader

- inital naming and folder grouping
- initial meta data 
  - particularly creator
- job code

# Prepare with Darktable

- Prioritize
- Color Correct and Crop
- Title
- Description (for alt text)

# Export for Grav

- export presets - set to images folder of grav project
- saves to exports folder under images using title as filname along with exif date 

# Import into Grav

- move to images folder
- slugify filename - url ready
- extract metadata with exiftool to create meta.yaml sidecar
-


