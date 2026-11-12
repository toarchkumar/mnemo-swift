# MNemo for Swift

An encrypted, single-file agent memory for iOS and macOS apps: vectors,
text, metadata and conversation threads in one portable `.mnemo` file.

This repository is the Swift package's release mirror. The release
workflow of [toarchkumar/mnemo](https://github.com/toarchkumar/mnemo)
writes it on every tag; the source, issues and documentation live there.

## Install

In Xcode, **File > Add Package Dependencies...**, then enter
`https://github.com/toarchkumar/mnemo-swift`. Or, in `Package.swift`:

```swift
.package(url: "https://github.com/toarchkumar/mnemo-swift", from: "0.13.0"),
```

and add the `Mnemo` product to your target. It needs iOS 15 or macOS 12.
Add the optional `MnemoAppleEmbedder` product too for Apple's on-device
embedders (the sentence model, and on iOS 17 or macOS 14 the contextual
model).

## Documentation

See the package guide, in
[mnemo/bindings/swift/README.md](https://github.com/toarchkumar/mnemo/blob/v0.13.0/mnemo/bindings/swift/README.md):
it covers `MnemoStore`, keys and backups, and the background rules.
The changelog is
[CHANGELOG.md](https://github.com/toarchkumar/mnemo/blob/v0.13.0/CHANGELOG.md).

Apache-2.0.
