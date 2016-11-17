fork of dune legacy on sourceforge: https://sourceforge.net/p/dunelegacy/code/

# How to build+run on OSX

This is tested with XCode 8.1 on Sierra.

```
git clone https://github.com/philippkeller/dunelegacy.git 
cd dunelegacy/IDE/xCode
mkdir -p ~/Library/Frameworks/
cp -rp SDL2.framework ~/Library/Frameworks/
cp -rp SDL2_mixer.framework ~/Library/Frameworks/
open Dune\ Legacy.xcodeproj
```

Building (Shift-⌘-R) should work out of the box, the application is put into ~/Library/Developer/Xcode/DerivedData/Dune_Legacy-..../Build/Products/Debug/Dune Legacy.app, the exact path you see in the right column when you click on "Dune Legacy.app" bottom left

You can also clone from the original git repo. Chances are that I cannot keep up with this repo -> you're better served by cloning from the [original sourceforge repo](git://git.code.sf.net/p/dunelegacy/code dunelegacy-code). The howto above should work as well.
