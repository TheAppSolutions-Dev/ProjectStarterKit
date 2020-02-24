## SwiftLint
https://github.com/realm/SwiftLint

`pod 'SwiftLint'`

Script Build Phase: `${PODS_ROOT}/SwiftLint/swiftlint`

## SwiftGen
https://github.com/SwiftGen/SwiftGen

`pod SwiftGen`

Script Build Phase: `$PODS_ROOT/SwiftGen/bin/swiftgen`

Don't forget to change *ProjectName* into the name of the project. Don't forget to create required folders beforehand.

## Main.swift

The file needs be to added to the project. `@UIApplicationMain` should be deleted from `AppDelegate` definition.


## File Templates

If it does not exist, copy "File Templates" folder in ~/Library/Developer/Xcode/Templates/
