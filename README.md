for new release 
```
./gradlew assembleRelease
```
clean before release
```
./gradlew clean assembleRelease
```
test command 
```
echo "🎉 PRODUCTION APK READY! 🎉" && echo "" && echo "📱 APK Details:" && echo "File: app-release.apk" && echo "Size: $(ls -lh app/build/outputs/apk/release/app-release.apk | awk '{print $5}')" && echo "Location: $(pwd)/app/build/outputs/apk/release/app-release.apk" && echo "Generated: $(date)"
```
