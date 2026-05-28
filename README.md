# Magisk Next Module Hub

This repository hosts the centralized module index for Magisk Next.

## How to Submit a Module

To add your module to the hub, open a Pull Request modifying `modules.json`. Ensure your entry follows this exact schema:

```json
{
  "id": "your_module_id",
  "name": "Your Module Name",
  "version": "v1.0",
  "versionCode": 1,
  "author": "Your Name",
  "description": "A short description of what your module does.",
  "zipUrl": "https://direct-link-to-your-module.zip",
  "changelog": "https://direct-link-to-your-changelog.md"
}
```
