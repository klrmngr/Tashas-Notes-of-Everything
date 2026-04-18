---
type: pc
race: "Aberration"
class:
 - "Aberrant Zealot"
subClass:
 - "CR 8"
cover: "Aberrant Zealot.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/8
  - source/pabtso
---
###### Aberrant Zealot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Aberrant Zealot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (studded leather armor) |
> | :FasHeart: HP | 93 (17d8 + 17) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 18 | 12 | 13 | 8 | 19 |
| **Mod** | +2 | +4 | +1 | +1 | -1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., truesight 10 ft., passive Perception 15
**Languages:** Common, Deep Speech
**Saving Throws:** Dex +7, Cha +7
**Skills:** Perception +5
**Damage Resistances:** psychic
**Condition Immunities:** blinded; charmed; frightened; grappled; restrained

---

### Traits

**Aberrant Form.** The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom saving throw or take 7 (2d6) psychic damage.

**Weirdly Pliable.** The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing.


---

### Actions

**Multiattack.** The zealot makes one Psychic Rend attack and two Shortsword attacks.

**Psychic Rend.** Melee or Ranged Spell Attack: +7 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or have the stunned condition until the start of the zealot's next turn.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) psychic damage.


---

### Bonus Actions

**Void Warp (Recharge 5–6).** The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength saving throw. On a failed save, a creature takes 18 (4d8) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```