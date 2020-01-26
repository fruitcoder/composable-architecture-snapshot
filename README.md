# composable-architecture-snapshot

Swift Package of [pointfree.co's](https://pointfree.co) most recent version of the composable architecture. Until there is a stable release of the code, this repository will be updated after every episode and the commit will be tagged with the episode number. All credits to Stephen and Brandon.

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. It is in early development, but Alamofire does support its use on supported platforms.

Once you have your Swift package set up, adding Alamofire as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
.package(url: "https://github.com/fruitcoder/composable-architecture-snapshot.git", .branch("master"))
]
```
