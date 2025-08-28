## Submission Rules

### Video Evidence

> Hud elements & visual guide need updating

- Single segment video evidence is required.
- Videos should be uploaded to a permanent host site.
  - Twitch VODs and Highlights are not accepted, as Twitch limits your highlight storage. You can migrate runs to Youtube from the Video Producer.
  - Acceptable hosts include Youtube and Bilibili.
  - The video must remain accessible; runs with videos removed or privated after verification may be removed from the boards.
- Video evidence must show the Title Screen either at the start of the run, or at a timestamp given in the run description.
  - The Title Screen must be clearly visible, with a legible version number.
  - IL runs may omit the timestamp, but must still show the Title Screen.
- Video evidence is expected to be of a watchable quality, without frequent or extensive frame drops.
- Game audio must be present (sound necessary, music optional) and game sounds should be audible over any background noise (voice, music etc.) at all times.
  - Runs will be rejected at the verifier's discretion if listening clearly to the game sounds requires uncomfortable levels of background noise.
- HUD elements must be clearly visible at all times. This includes the soul meter, masks, and geo and essence counts. Where required for verification, there must be at least one clear frame of the Title Screen where the patch number and modding API text would be seen ([visual guide](https://github.com/hk-speedrunning/HK-Rules/blob/main/video-guidelines.md)). Runs will be rejected at the verifier's discretion if significant amounts of the active portion of the game window are covered.

### Breaks

> NB - includes clauses based on the Load Time Remover which may behave significantly differently for Silksong

- Breaks can be a maximum of 10 minutes long: any time over this threshold will be added to your final time.
- Breaks must be taken on the File Select screen on the menu:
    - Pause the timer after you have hit the button to open the file select menu.
    - To end the break, select a file then hit unpause.
- You may take multiple breaks at once - eg. a 20 minute break will use 2 of your allotted breaks.
- Verifiers may reject your run if they determine it to be abusing the pause system.
- The recording must be left on the file select screen - switching to a different scene will result in a rejection.
- To compensate for timesave in menuing, a 0.1s time penalty will be added to your final time.
- Pausing the timer incorrectly will not result in a rejection, but a penalty of 0.3s or more will be applied to compensate for time saved.

The following categories are eligible for breaks (all thresholds given are Loadless time):

> TODO: identify suitable categories for breaks. As a reminder, All Achievements gets 4 breaks in first 7 hours, and 1xx, AB, GE, P5BO get 2 in first 3 with restrictions on long sections like colo, White Palace or P1.

### Special Cases

> This is an edge case ruling from the original game, we could omit it. Also note the input division needs rewriting for suitability to Silksong.

- 2 player 1 controller (2p1c) speedruns may be submitted to any of the leaderboards under the following guidelines:
  - The run must be submitted under a joint speedrun.com account. The run description must identify the individual runners.
  - The submission must include video evidence of the shared use of the input device. The input device need not be any specific type of controller, provided inputs are shared according to guidelines.
  - The inputs must be shared as follows: one player has use of the 4 directional inputs and no more than two additional action buttons, which are not to include jump or nail swing. The other player has use of all other actions. The use of inventory or pause may be shared.

## Settings Rules

### Game modifications

> Verify whether we need any more modifications - we should have CameraShakeModifier by default. Minisavestates may be added once it exists - it _may_ make sense to distribute as a BepInEx plugin not dependent on the Silksong coremod once that modding framework exists.

- Game modifications, including BepInEx, are banned.

### Game Settings

> Verify these rules are necessary

- The following values in _[game location]/[hollow_knight_Data]/Config.ini_ may be edited:
  - **FrameRateCap**: May be set to any value of at least 50.
  - **CameraShakeMultiplier**: May be set to any value. Note: Gameplay must still be of watchable quality so putting the multiplier above 1 or below -1 may result in a rejection.
- Using in-game Vsync to limit framerate is allowed so long as the target monitor's refresh rate remains consistent during the run.
- If either either Vsync or FrameRateCap are toggled during the run, you must have a clearly visible FPS display in your recording.

### Third-party programs

> Verify these rules are necessary

- Using a third-party program to limit framerate is allowed so long as the target framerate is 50fps or above and the cap is not modified or disabled during the run.
- Macros and turbo functions are not allowed, with the below exceptions:
  - "SOCD cleaners", used to adjust the behaviour of overlapping left+right inputs (see [socd_cleaner.exe](https://github.com/valignatev/socd/releases/download/0.0.8/socd_cleaner.exe))
  - Macros used to map mouse inputs 1-to-1 to keyboard inputs (see [blue.exe](https://github.com/hk-speedrunning/HK-Resources/raw/main/External%20Tools/Blue/blue.exe)) and vice versa (see [KeyboardToClick.ahk](https://github.com/hk-speedrunning/HK-Resources/raw/main/External%20Tools/KeyboardToClick/KeyboardToClick.ahk))
  - Analog remappers used to bind keyboard keys to a virtual joystick.
- Each player input can be mapped to a maximum of one game input. Multiple player inputs can all be mapped to the same game input.
  - Binding an action to the scroll wheel or to the analog stick to allow turbo-like functionality is banned.

## Gameplay Rules

> What is needed here?

- Entering menus for the sole purpose of pausing the timer is not allowed.
- Force exiting the game (Alt-F4) is only allowed when game menus are permanently inaccessible.
- Inducing lag with Print Screen, moving the game window or any other method is not allowed.
- Individual level runs may not make use of any advantage from setting up on a different patch from the run itself.
  - For example, a pantheon IL (on 1.4+) may not set up on 1.0.x.x to obtain 2 notch Quick Slash and Flukenest.
- The game patch may not be changed at any point during a run.

## Retiming

> Copied in but maybe not necessary? do inf loads still happen on 1.5, and if not then can we assume Silksong will match this behaviour?

- Infinite Loads into The Hollow Knight will have any time between force quitting the game and re-entering the load removed provided the following conditions hold:
  - Health on re-entry is unchanged from the original value.
  - Soul on re-entry is unchanged or less than the original value.
  - No other objective is completed or benefit is gained, up to the verifier’s discretion. In particular, any difference from initial geo values must also not provide any benefit gained.
  - The fight is re-entered quickly. Excessive breaks before returning to the fight risk invalidation.
