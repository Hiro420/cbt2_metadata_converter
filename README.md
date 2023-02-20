# MetadataConverter

modified version of metadata converter for cbt2

# HOW TO BUILD:
- Add `C++ CMake tools for windows` in your Visual Studio installation
- Open the folder in Visual Studio
- Click on `Build` and then `Build All` on the top bar
- The built .exe and all it's dependencies will be in `\out\build\x64-Debug` folder
- Paste there your CBT2 or CB2 Devkit `global-metadata.dat` to the folder
- Open there a cmd window and enter `metadata tounitymeta global-metadata.dat global-metadata-unity.dat`
- The ready-to-go converted metadata will be saved as `global-metadata-unity.dat` in same folder, ready to use in any il2cpp dumper/inspector
