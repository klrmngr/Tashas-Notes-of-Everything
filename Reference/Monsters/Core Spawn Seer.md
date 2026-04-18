---
type: pc
race: "Aberration"
class:
 - "Core Spawn Seer"
subClass:
 - "CR 13"
cover: "Core Spawn Seer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/13
  - source/egw
---
###### Core Spawn Seer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Core Spawn Seer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 18 | 22 | 19 | 16 |
| **Mod** | +2 | +1 | +4 | +6 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., tremorsense 60 ft., passive Perception 19
**Languages:** Common, Deep Speech, telepathy 120 ft., Undercommon
**Saving Throws:** Dex +6, Int +11, Wis +9, Cha +8
**Skills:** Perception +9
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Earth Glide.** The seer can traverse through nonmagical, unworked earth and stone. While doing so, the seer doesn't disturb the material it moves through.

**Magic Resistance.** The seer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The seer uses Fission Staff twice, Psychedelic Orb twice, or each one once.

**Fission Staff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 9 (1d6 + 6) bludgeoning damage plus 18 (4d8) radiant damage, and the target is knocked prone.

**Psychedelic Orb.** The seer hurls a glimmering orb at one creature it can see within 120 of it. The target must succeed on a DC 19 Wisdom saving throw or take 27 (5d10) psychic damage and suffer a random condition until the start of the seer's next turn. Roll a d6 for the condition: (1-2) blinded, (3-4) frightened, or (5-6) stunned.


---

### Reactions

**Fuse Damage.** When the seer is hit by an attack, it takes only half of the triggering damage. The first time the seer hits with a melee attack on its next turn, the target takes an extra 1d6 radiant damage.


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