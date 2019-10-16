An archery tactics style game with a [sourceforts](https://en.wikipedia.org/wiki/SourceForts)-esque twist.

Issues:

- [x] Two players can grab the same Manipulatable
- [x] You can bring the flag past a close-radius wall
- [x] F3 hero is selectable - bug - still a bug?
- [x] Visibility is frustrating
- [x] There is no ability to perfm a "drop" during Manipulate
- [x] Opponents should be unselectable/reselect main hero periodically
- [x] Terrain manipulator hero
- [ ] Caster hero
- [x] Manipulating own flag should just send it back
- [x] After dying you can simply F2, lol
- [x] Unsummon can double-tap - needs nonce
- [x] Lava missile goes thru mountains
- [x] Mountain has no maximum size
- [x] Lava missile does not respect target terrainz
- [ ] No way to make a valley or otherwise reverse a mountain
- [ ] no way to repair
- [ ] rework cooldown system using pools
- [ ] Skeleton arrow too
- [x] desync from mountain manipulator
    * [x] Knockback3::tickAboveGround x 2
    * [x] vec2::withRealZ
    * [x] vec2::withTerrainZ
    * [x] new BoolRef
    * [x] ID_MOUNTAIN -> z = pos.getTerrainZ
    * [ ] publish Knockback3 configurable
