# Bytespeicher_WorkAdventure_RC3
A WorkAdventure map to be used during the rc3 


## Usage
- Open in the [Tiled](https://thorbjorn.itch.io/tiled) editor 
- make modifications
  - you can use [Piskel](https://www.piskelapp.com/) for single tiles (online tool)
  - the howto mentiones [Krita](https://krita.org/en/), but it's very complex for such a simple task
- export to .json
- make sure all paths to the tilesets are relative in the .json
- push to github
- open https://play.wa-test.rc3.cccv.de/_/global/raw.githubusercontent.com/Bytespeicher/Bytespeicher_WorkAdventure_RC3/main/json/main.json

## Get started and try your map from localhost
- Get a local http server which allows cors for all requests
  - eg. https://gist.github.com/acdha/925e9ffc3d74ad59c3ea
- Get ngrok for your os
- Steps to run rc3 which your local map:
  - use this only for development!
  - put the http server into this folder
  - open new terminal
  - cd into this folder
  - Start http server `python server.py`
  - Start ngrok `ngrok http 8003`
  - Build the url to your local map:
    - Copy `https://play.wa-test.rc3.cccv.de/_/global/`
    - Copy from ngrok your private url without http something like `13371337.ngrok.io`
    - Copy `json/main.json` together
    - It should lock like `https://play.wa-test.rc3.cccv.de/_/global/13371337.ngrok.io/json/main.json`
    - Open your url with url browser
    
## Tilesets
- *housetileset.png* from https://btl-games.itch.io/topdown (License: free for private and commercial use, no restrictions given)
- *stuff.png* created by Chaos_99 under CC0
- *MSTischmKanal.png* created by fpf2000_R under CC0




