1) Create 'Cartfile'.
```
touch Cartfile
```
2) Add Package repo and save file.
```
github "eKroman-dev/custom-sdk" ~> 1.0.0
```
3) Download package from the root repo.
```
carthage update
```
4) On your application targets’ General settings tab, in the Frameworks, Libraries, and Embedded Content section, drag and drop `SpikeSDK.xcframework` from the Carthage/Build folder on disk.
