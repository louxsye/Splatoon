# P2 Forsaken - Drippy Relative

Import URL for Splatoon:

```text
https://raw.githubusercontent.com/louxsye/Splatoon/main/SplatoonScripts/Duties/Dawntrail/Dancing%20Mad/P2_Forsaken_DrippyRelative.cs
```

Because this is hosted on the `louxsye` fork instead of the default Splatoon trusted repos, add this prefix to Splatoon's extra trusted sources before installing from a URL:

```text
https://raw.githubusercontent.com/louxsye/
```

Preset target script name:

```text
SplaSim.SplatoonScripts.Duties.Dawntrail.DancingMadUltimate@P2_Forsaken_DrippyRelative
```

Recommended settings for a Phase 2.md preset block:

```text
UseRelativePositionForSameMarker = true
SameMarkerRankMode = FartherFromBossAdjusts
InvertRelativeSameMarkerSide = false
```

`SameMarkerRankMode = FartherFromBossAdjusts` assigns Rank 1 to the same-marker player closer to the arena center/boss and Rank 2 to the player farther away.

`InvertRelativeSameMarkerSide` is only for reversing the local left/right result when `SameMarkerRankMode = TowerRelativeLeftRight`.
