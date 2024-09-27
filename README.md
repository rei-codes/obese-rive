# sizey

> android > app > build.gradle
```gradle
    ndkVersion = flutter.ndkVersion // or latest version "27.1.12297006"
    // ndkVersion = "25.1.8937393" // uncomment this line to fix the problem
```

### Before
no rive -> (18.2MB)
rive -> (70.0MB)

### After
ndkVersion "25.1.8937393"

no rive -> (18.2MB)
rive -> (25.4MB)


`flutter build apk --release`

`flutter build apk --target-platform android-arm64 --analyze-size`
