## Submission Rules

### Video Evidence

- Single segment video evidence is required.
- Videos should be uploaded to a permanent host site & may not be deleted after verification.
  - Twitch VODs and Highlights are not accepted, as Twitch limits your highlight storage. You can migrate runs to Youtube from the Video Producer.
  - Acceptable hosts include Youtube and Bilibili.
- Game audio must be present (music is optional) and game sounds should be audible over any background noise (voice, music etc.) at all times.
  - Runs will be rejected at the verifier's discretion if listening clearly to the game sounds requires uncomfortable levels of background noise.
- Video evidence must show the Title Screen either at the start of the run, or at a timestamp given in the run description.
  - The Title Screen must be clearly visible, with a legible version number.
  - Individual Level runs may omit the timestamp, but must still show the Title Screen.
- Video evidence must be of a watchable quality, without frequent or extensive frame drops.
- The following are summarized in the [visual guide](/video_guidelines.md):
  - HUD elements must be clearly visible at all times. This includes the silk spool, masks, and rosary & beast shard counts (when present).
  - There must be at least one clear frame of the Title Screen where the patch number is clearly readable.
  - If using the Load Remover, Livesplit must be clearly visible at all times.
  - Runs will be rejected at the verifier's discretion if significant amounts of the active portion of the game window are covered.

### Breaks

<!-- TODO: may choose to circle back to this based on future runs. -->
- You may take short (<5min) breaks on the File Select screen, at any point.
- You may take a 10 minute break per hour of runtime - you must timestamp these in your run description.
- These breaks can be combined & taken at any time as long as the final time exceeds the requirement. The “final time" refers to RTA Gameplay time, i.e. not including your breaks already taken.
- Breaks are UNLIMITED (within reason) for runs reaching 3 hours.
- Long breaks (5mins or greater) must be timestamped in the run description.

Breaks must be taken as follows:

- Breaks must be taken on the File Select screen on the menu:
  - For NMG runs the timer should pause automatically for you on all main menu screens, including on the file select screen.
  - Glitched runs should not have any pausing in the main menu screens, apart from specifically manually pausing the timer, to take a break on the file select screen.
- Verifiers may reject your run if they determine it to be abusing the break system.
- The recording must be left on the file select screen - switching to a different scene will result in a rejection.
<!-- TODO: move to Verifier Guide
- To compensate for timesave in menuing, a 0.1s time penalty will be added to your final time.
- Pausing the timer incorrectly will not result in a rejection, but a penalty of 0.3s or more will be applied to compensate for time saved.
-->

### Special Cases

- 2 player 1 controller (2p1c) speedruns may be submitted to any of the leaderboards under the following guidelines:
  - The run must be submitted under a joint speedrun.com account. The run description must identify the individual runners.
  - The submission must include video evidence of the shared use of the input device. The input device need not be any specific type of controller, provided inputs are shared according to guidelines.
  - The inputs must be shared as follows: one player has use of the 4 directional inputs and no more than two additional action buttons, which are not to include jump or nail swing. The other player has use of all other actions. The use of inventory or pause may be shared.

## Gameplay Rules

- Entering submenus for the sole purpose of pausing the timer is not allowed.
- Force exiting the game (Alt-F4) is only allowed when game menus are permanently inaccessible.
- Additionally glitched runs are allowed to quitout on failed cutscene skip attempts, during Main Menu Storage setup.
- Verifiers may reject your run if they determine it to be abusing the gameplay rules by **purposefully** hardlocking.
- Inducing lag with Print Screen, moving the game window or any other method is not allowed.
<!-- TODO: IL rule once relevant -->

## Settings Rules

### Game modifications

- Game modifications **except the HKSRC Speed Patch**, including BepInEx & all plugins from Nexus & Thunderstore, are banned. See [this guide](https://github.com/hk-speedrunning/Silksong-Resources/blob/main/setup.md#launching-unmodded-for-runs-steam) on how to disable BepInEx.
- Runs may be done using the [HKSRC Speed Patch](https://github.com/hk-speedrunning/Silksong.SpeedPatch), which can be configured for different runs.
  - NMG runs may enable **CourierRNGFix (CRNG)**.
  - Glitched runs may enable the above & **DowndashTransitionFix (DDTF)**.
  <!-- 
  - Cycle Normaliser
  - Text Masher
  When released -->

### Game Settings

- Resolutions with an aspect ratio wider than 2:1 are not allowed. You should capture the entire game window to make verification easier.
- The HUD must not be disabled.
- Using in-game Vsync to limit framerate is allowed so long as the target monitor's refresh rate remains consistent during the run.
- If you change the VSync setting either during or before your run, you must have a clearly visible FPS display in your recording.
- You may not switch game versions during the run.
- Using the in-game 30fps cap is not allowed. Your fps cap should not be set below 50fps in any way.

<!-- TODO: Circle back on framerate shenanigans -->

### Third-party programs

- Using a third-party program to limit framerate is allowed so long as the target framerate is 50fps or above and the cap is not modified or disabled during the run.
- Macros and turbo functions are not allowed, with the below exceptions:
  - "SOCD cleaners", used to adjust the behaviour of overlapping left+right inputs (see [Overbind](https://github.com/cjonas1999/OverBind) or [Hitboxer](https://github.com/valignatev/hitboxer))
  - Analog remappers used to bind keyboard keys to a virtual joystick (see [Overbind](https://github.com/cjonas1999/OverBind))
- Each player input can be mapped to a maximum of one game input. Multiple player inputs can all be mapped to the same game input.
  - Binding an action to the scroll wheel or to the analog stick to allow turbo-like functionality is banned.
