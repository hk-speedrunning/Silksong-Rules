# Verifier Guide

This document is intended for Hollow Knight: Silksong verifiers only; it is not relevant to runners.

---

- [Verifier Guide](#verifier-guide)
  - [Quick Rejection Reasons](#quick-rejection-reasons)
  - [Timing](#timing)
    - [Any Category Ending w/ GMS](#any-category-ending-w-gms)
    - [Judgement](#judgement)
    - [5 Tools](#5-tools)
    - [4 Mask Shards](#4-mask-shards)
  - [Formatting](#formatting)
  - [Glitches to look out for](#glitches-to-look-out-for)
    - [Damage counting](#damage-counting)
  - [Per-Category](#per-category)
  - [Special Cases](#special-cases)

---

## Quick Rejection Reasons

- Incorrect patch; the Patch variable on SRC lists every non-beta patch, as well as the [Manifests doc](<https://github.com/hk-speedrunning/Silksong-Resources/blob/main/manifests.md>).
- Modlist active: _Please note an absence of Modlist **does not imply** unmodded by default!_

## Timing

- The old autosplitter removes much more time than the new one - an imperfect indicator is LRT being more than 2 minutes off RTA per hour.
  - The new autosplitter pauses when the screen is almost completely faded to black - the old one pauses while Hornet is still on screen.

### Any Category Ending w/ GMS

Ends on the audio cue of the cutscene starting. If not audible, final spool expansion +1s is acceptable.

### Judgement

Ends after the quest icon appears after the Act 2 cutscene. _**Last Judge Autosplit is wrong!**_

### 5 Tools

Requires manual retiming!

Ends the frame the rosary deduction appears / first fully black frame of the shop confirm dialog (note tool icon is still visible).

### 4 Mask Shards

End on Big sound + Main Particle effects as mask enters HUD. For each mask missing before picking up the 4th mask shard, +0.16s.

## Formatting

To Check:

- Correct Patch selected
- Correct Platform selected (where it is possible to tell)
- RTA exists

Hornet does most of the below for you, but please make sure if you edit a run to continue following the formatting guidelines, as Hornet will not re-check runs she has already formatted:

- If a run is over 10 minutes, it should not have milliseconds.
- RTA should never contain milliseconds.
- If a run is timed RTA, enter the RTA into _**Both the LRT and RTA fields**_.
  - You can add the note `Real Time taken as Loadless Time for leaderboard formatting.` if you like.

## Glitches to look out for

As always, glitches that are performed accidentally & do not save time are permitted at verifier discretion.

- Invisible control (much less common than hk)
- [Triple Jump] : Penalty if saved time 2s
- [Fourth Chorus Skip Skip] : If a run gets cloak make sure they don't rapidly quitout after the obtain to warp elsewhere; this is a major glitch currently.

### Damage counting

Unfortunately this game Sucks for damage counting - every enemy has specific resistances to each nail/tool level & some tools don't conform to this scaling by adding flat damage.

You are not expected to damage count anything - only resort to it if you think something is clearly wrong. The Wiki has resistance values per-enemy you can use, but generally if you're unsure post it to the channel to be looked over & move onto another run.

## Per-Category



## Special Cases

This is where special case rulings that do not fit in the game ruleset belong.

> i can't be bothered to add these rn they aren't relevant yet sorry
