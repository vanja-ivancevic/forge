# Dungeons and Caves with Starting Cards

This list contains all dungeons and caves where enemies start the game with specific cards in effect.

## TMX Map Files with dungeonEffect Property

### Mage Tower (various floors)
- **magetower_1_djinn.tmx**: `Staff of the Mind Magus` -> Crystal Rod
- **magetower_2_blackwiz.tmx**: `Staff of the Death Magus` (appears twice in file) -> Throne of Bone
- **magetower_3_redwiz.tmx**: `Staff of the Flame Magus` -> Iron Star
- **magetower_4_monastery.tmx**: `Staff of the Sun Magus` -> Ivory Cup
- **magetower_5_greenhouse.tmx**: `Staff of the Wild Magus` -> Wooden Sphere
- **magetower_6_infernalgenesis.tmx**: `Infernal Genesis` (main floor) and `Desecrated Tomb` (secondary area) -> change for both to Infernal Genesis
- **magetower_7_church.tmx**: `White Shield Crusader` ⚠️ **NOT AVAILABLE IN OLD BORDER** -> Capashen Templar
- **magetower_9_ninjarats.tmx**: `Gnat Miser` -> Muck Rats
- **magetower_10_crawlspace.tmx**: `Crawlspace` (already old border compatible)
- **magetower_11_dreamhalls.tmx**: `Dream Halls` (already old border compatible)
- **magetower_12_lichsmirror.tmx**: `Mirror of Life Trapping` -> Portcullis
- **magetower_13_doppelganger.tmx**: `As Foretold` -> Mana Flare
- **magetower_14_horrors.tmx**: `Abyssal Gatekeeper`

### Vampire Castle
- **vampirecastle_grave_1.tmx**: `Stensia Masquerade` -> Orcish Oriflamme
- **vampirecastle_grave_2.tmx**: `Legion's Landing` -> Mind Slash
- **vampirecastle_grave_3.tmx**: `Canonized in Blood` -> Phyrexian Arena

### Caves
- **cave_devil.tmx**: `Circle of Flame` -> Furnace of Rath

### Mini-bosses
- **xira.tmx**: `Hornet Nest` -> Saber Ants

### Main Story Castles (using startBattleWithCardInCommandZone)
- **white_castle.tmx** and **white_castle_f1.tmx**: `Akroma's Presence` 
- **black_castle.tmx** and **black_castle_f1.tmx**: `Griselbrand's Presence`
- **red_castle.tmx** and **red_castle_f1.tmx**: `Lathliss' Presence`
- **blue_castle.tmx** and **blue_castle_f1.tmx**: `Lorthos' Presence`
- **green_castle.tmx** and **green_castle_f1.tmx**: `Ghalta's Presence`
- **wastetown.tmx**: `Ghalta's Presence`

## Equipment Items (from items.json files)

### Shandalar Old Border Equipment
Equipment items that provide starting cards via `startBattleWithCard` effect:

1. **Jayemdae Tome** (Left slot): `Jayemdae Tome`
2. **Ring of Renewal** (Neck slot): `Ring of Renewal`
3. **Mogg Fanatic**: `Mogg Fanatic`
4. **Lightning Bolt**: `Lightning Bolt`
5. **Dark Ritual**: `Dark Ritual`
6. **Healing Salve**: `Healing Salve`
7. **Giant Growth**: `Giant Growth`
8. **Ancestral Recall**: `Ancestral Recall`
9. **Time Walk**: `Time Walk`
10. **Black Lotus**: `Black Lotus`
11. **Mox Pearl**: `Mox Pearl`
12. **Mox Sapphire**: `Mox Sapphire`
13. **Mox Jet**: `Mox Jet`
14. **Mox Ruby**: `Mox Ruby`
15. **Mox Emerald**: `Mox Emerald`
16. **Serra Angel**: `Serra Angel`
17. **Shivan Dragon**: `Shivan Dragon`
18. **Lord of Atlantis**: `Lord of Atlantis`
19. **Hypnotic Specter**: `Hypnotic Specter`
20. **Llanowar Elves**: `Llanowar Elves`
21. **Lightning Bolt (M10)**: `Lightning Bolt`
22. **Lava Axe**: `Lava Axe`
23. **Swords to Plowshares**: `Swords to Plowshares`
24. **Shock**: `Shock`
25. **Terror**: `Terror`
26. **Disenchant**: `Disenchant`
27. **Counterspell**: `Counterspell`
28. **Fireball**: `Fireball`
29. **Earthquake**: `Earthquake`
30. **Lightning Bolt (2E)**: `Lightning Bolt`
31. **Fyndhorn Bow**: `Fyndhorn Bow`
32. **Control Magic**: `Control Magic`
33. **Demonic Tutor**: `Demonic Tutor`
34. **Wrath of God**: `Wrath of God`
35. **Dingus Egg**: `Dingus Egg`
36. **Birds of Paradise**: `Birds of Paradise`
37. **Armageddon**: `Armageddon`
38. **Balance**: `Balance`
39. **Brainstorm**: `Brainstorm`
40. **Necropotence**: `Necropotence`
41. **Channel**: `Channel`
42. **Timetwister**: `Timetwister`
43. **Wheel of Fortune**: `Wheel of Fortune`
44. **Regrowth**: `Regrowth`
45. **Berserk**: `Berserk`
46. **Stone Rain**: `Stone Rain`
47. **Sinkhole**: `Sinkhole`
48. **Strip Mine**: `Strip Mine`
49. **Sol Ring**: `Sol Ring`
50. **Mana Vault**: `Mana Vault`
51. **Fork**: `Fork`
52. **Red Elemental Blast**: `Red Elemental Blast`
53. **Blue Elemental Blast**: `Blue Elemental Blast`
54. **Disintegrate**: `Disintegrate`
55. **Chaos Orb**: `Chaos Orb`
56. **Manabarbs**: `Manabarbs`
57. **Juggernaut**: `Juggernaut`
58. **Icy Manipulator**: `Icy Manipulator`
59. **Howling Mine**: `Howling Mine`

### Crystal Kingdoms Equipment
Similar equipment items available in Crystal Kingdoms adventure mode with `startBattleWithCard` effects.

## Notes

- ⚠️ **White Shield Crusader** in magetower_7_church.tmx is flagged as NOT AVAILABLE IN OLD BORDER ADVENTURE MODE
- Some locations use `startBattleWithCardInCommandZone` instead of `startBattleWithCard` (mainly the main story castles)
- Equipment items provide starting cards when equipped by the player
- There are over 140+ different items with starting card effects across both adventure modes

## Recommendation for Old Border Adventure Mode

The following cards that start in dungeons/caves should be reviewed for old border compatibility:
1. **White Shield Crusader** (magetower_7_church.tmx) - confirmed problematic
2. **Stensia Masquerade** (vampirecastle_grave_1.tmx)
3. **Legion's Landing** (vampirecastle_grave_2.tmx)
4. **Canonized in Blood** (vampirecastle_grave_3.tmx)

All other cards appear to be from older sets and should be compatible with old border mode.