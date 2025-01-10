# Ghost-Watcher-Fixes
This repo hosts fixes directly from the Ghost Watchers developers.
(I am *not* a developer for the game, only someone who got help.)

## Ghost Watchers "Cannot make it past connecting issue" Resolution
*Please make sure the game is not open during these fixes.*

### Fix 1:
1. Open `regedit`.
2. Navigate to `HKEY_CURRENT_USER\Software\LLC Renderise\Ghost Watchers`.
3. Find the key `region_h2124512157`.
4. Change its value to `4`.

Reload the game. This will change the region from EU to US.

### Fix 2:
If the issue persists:
1. In the same directory in `regedit` (`HKEY_CURRENT_USER\Software\LLC Renderise\Ghost Watchers`).
2. Delete the registry key `lobby_h173251839`.

This will delete your current lobby, (not progress as far as I know)

Reload the game.