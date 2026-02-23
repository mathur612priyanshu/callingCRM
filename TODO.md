# TODO: Change Package Name from capital_care to callingcrm

## Package Name Change:
- **From**: com.example.capital_care
- **To**: com.trustingbrains.callingcrm

## Files to Edit:

### 1. Flutter Configuration
- [ ] frontend/pubspec.yaml - name: capital_care → calling_crm

### 2. Android
- [ ] frontend/android/app/build.gradle.kts - namespace & applicationId
- [ ] frontend/android/app/src/main/kotlin/com/example/capital_care/MainActivity.kt - package & CHANNEL (need to rename folder too)
- [ ] frontend/android/app/src/main/AndroidManifest.xml - android:label

### 3. iOS
- [ ] frontend/ios/Runner.xcodeproj/project.pbxproj - PRODUCT_BUNDLE_IDENTIFIER
- [ ] frontend/ios/Runner/Info.plist - CFBundleName

### 4. macOS
- [ ] frontend/macos/Runner/Configs/AppInfo.xcconfig - PRODUCT_NAME & PRODUCT_BUNDLE_IDENTIFIER
- [ ] frontend/macos/Runner.xcodeproj/project.pbxproj - Multiple bundle identifier changes
- [ ] frontend/macos/Runner.xcodeproj/xcshareddata/xcschemes/Runner.xcscheme - BuildableName

### 5. Windows
- [ ] frontend/windows/CMakeLists.txt - project name & BINARY_NAME
- [ ] frontend/windows/runner/Runner.rc - FileDescription, InternalName, OriginalFilename, ProductName
- [ ] frontend/windows/runner/main.cpp - window title

### 6. Linux
- [ ] frontend/linux/CMakeLists.txt - BINARY_NAME & APPLICATION_ID
- [ ] frontend/linux/runner/my_application.cc - window title

### 7. Web
- [ ] frontend/web/index.html - title & meta content
- [ ] frontend/web/manifest.json - name & short_name

### 8. Dart/Flutter Source Files (~30+ files)
- [ ] All files importing `package:capital_care/` need to change to `package:calling_crm/`

### 9. Other
- [ ] frontend/test/widget_test.dart - import statement
- [ ] frontend/README.md - project name
