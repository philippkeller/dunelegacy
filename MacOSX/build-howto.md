1. build a 'release type' app with xcode -> Dune Legacy.app
2. test Dune Legacy.app
3. `open dunelegacy.dmg`
4. `open /Volumes/Dune\ Legacy/`
5. remove Dune Legacy.app in the window, replace it with the new Dune Legacy.app
6. close window, eject volume
7. hdiutil convert -format UDZO -o Dune\ Legacy.dmg dunelegacy.dmg