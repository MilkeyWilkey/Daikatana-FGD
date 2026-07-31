# Updated Daikatana FGD for Trenchbroom

For use with latest Daikatana 1.3 patch and Trenchbroom 2026.1 and newer. 

## New features
- full support for default deco and deco_custom models along with their scale and frame keys
- new default key value pairs for entities that frequently requre them (e.g. _color for light etc)
- updated default key values to reflect internal game and Trenchbroom changes
- optional Global entity list that shows all in-game entities
- map soft bounds

## Notes
This update was created to improve my personal mapping workflow. It may or may not include some features so feel free to contact me with any suggestions at official [Daikatana 1.3](https://discord.gg/Uw65xwVQhY) or [Trenchbroom](https://discord.com/invite/XaAuJVz) Discord servers. 

## Installation
In Trenchbroom go to View -> Preferences... -> Games and hit the folder icon in the left bottom corner of the window. 

On **Windows** it will open `%AppData%\Roaming\TrenchBroom\games`

On **Linux** it'll be  `~/.TrenchBroom/games/`

Just place the Daikatana folder from this repo there and restart Trenchbroom.

## Known limitations
- Trenchbroom does not yet support SP2 sprites so they are not implemented in the FGD. However it does support common format sprites (PNG, JPEG), so feel free to add them if you desire.
- Some models (main characters, health fountain) may look weird in the editor with wrong or stretched skin. Trenchbroom has limited dkm model support and will only draw 1 skin over the whole model even if it has multiple. 
- Although each deco is drawn with the exact same bounding box, each one of them has a custom size in the actual game. Keep that in mind while placing objects that can potentially overlap.

## Need help?
If you need any help with Daikatana mapping feel free to contact me on Daikatana 1.3 discord. 
Also, check out Trenchbroom official manual, TB guides for Quake 1 and 2, [dumptruck_ds TB series](https://www.youtube.com/watch?v=gONePWocbqA&list=PLgDKRPte5Y0AZ_K_PZbWbgBAEt5xf74aE) and even Quake 2 mapping tutorials from the 90's - core principles are the same