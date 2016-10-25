# Glob
Glob for Swift 3

Adapted from https://gist.github.com/efirestone/ce01ae109e08772647eb061b3bb387c3

# install
`git clone https://github.com/axgle/Glob`
`cd Glob`
`swift package  generate-xcodeproj`
drop `Glob.xcodeproj` into your xcode project

    import Glob
    for file in Glob(pattern: "/tmp/*"){

        print(file)

    }
