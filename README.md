# Build Commands

## For new release (APK)

```bash
./gradlew assembleRelease
```

## For new release (AAB - Android App Bundle)

```bash
./gradlew bundleRelease
```

## Clean before release (APK)

```bash
./gradlew clean assembleRelease
```

## Clean before release (AAB)

```bash
./gradlew clean bundleRelease
```

## Test command for APK

```bash
echo "🎉 PRODUCTION APK READY! 🎉" && echo "" && echo "📱 APK Details:" && echo "File: app-release.apk" && echo "Size: $(ls -lh app/build/outputs/apk/release/app-release.apk | awk '{print $5}')" && echo "Location: $(pwd)/app/build/outputs/apk/release/app-release.apk" && echo "Generated: $(date)"
```

## Test command for AAB

```bash
echo "🎉 PRODUCTION AAB READY! 🎉" && echo "" && echo "📱 AAB Details:" && echo "File: app-release.aab" && echo "Size: $(ls -lh app/build/outputs/bundle/release/app-release.aab | awk '{print $5}')" && echo "Location: $(pwd)/app/build/outputs/bundle/release/app-release.aab" && echo "Generated: $(date)"
```
