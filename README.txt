PIXEL KEEP — FREE BROWSER ARCADE

FILES
- index.html: the game library website
- games/realmguard.html: medieval fantasy tower defense
- games/stardrifter.html: asteroid dodging arcade game
- games/runeclicker.html: mana clicker game

TEST LOCALLY
Open index.html in a browser. The games load from the games folder, so keep the folder structure intact.

PUBLISH FOR FREE WITH GITHUB PAGES
1. Create or sign in to a free GitHub account.
2. Create a new public repository, e.g. pixel-keep.
3. Upload index.html, README.txt, and the games folder with all three HTML files.
4. Open repository Settings > Pages.
5. Under Build and deployment, select Deploy from a branch, choose main and /(root), then Save.
6. Wait for GitHub Pages to publish the site; the URL appears in the Pages settings.

ADD ANOTHER HTML GAME
1. Put the new file in games/, e.g. games/mygame.html.
2. In index.html, add its ID and path to gameFiles and its display name to gameTitles.
3. Copy one card in the Game Library section and update its title, description, and onclick="playGame('mygame')".
4. Upload the changed files to GitHub.

This is a static website. No paid server, database, or account is needed for these games.
