# P2 Missing 1238/4567 KT Boss Distance Adjust

Import URL:

```text
https://raw.githubusercontent.com/louxsye/Splatoon/main/SplatoonScripts/Duties/Dawntrail/Dancing%20Mad/P2_Forsaken_Pattern/P2_Missing_1238_4567_KTBased_BossDistanceAdjust.cs
```

Extra trusted source:

```text
https://raw.githubusercontent.com/louxsye/
```

This is based on upstream `P2_Missing_1238_4567_KTBased_RelativePairPosition.cs`.

Behavior difference:

- Uses upstream KT 1238/4567 tower positions.
- When exactly two active tower players have the same tower debuff, the player closer to the arena center/boss becomes Priority1.
- The player farther from the arena center/boss becomes Priority2, so the farther player takes the adjustment slot.
- If the distance check cannot be resolved, it falls back to the configured global priority.
- The guide marker shows only the selected destination, not both candidate destinations.

Debug tab shows `Same-debuff rank` with the boss-distance result or fallback reason.
