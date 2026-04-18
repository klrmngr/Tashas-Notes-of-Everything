---
type: pc
race: "Aberration"
class:
 - "Star Spawn Seer"
subClass:
 - "CR 13"
cover: "Star Spawn Seer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/13
  - source/mpmm
---
###### Star Spawn Seer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Star Spawn Seer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 18 | 22 | 19 | 16 |
| **Mod** | +2 | +1 | +4 | +6 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** Common, Deep Speech, Undercommon
**Saving Throws:** Dex +6, Int +11, Wis +9, Cha +8
**Skills:** Perception +9
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Out-Of-Phase Movement.** The seer can move through other creatures and objects as if they were 3, and its movement doesn't provoke opportunity attacks.
Each creature it moves through takes 5 (1d10) psychic damage; no creature can take this damage more than once per turn.
The seer takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The seer makes two Comet Staff or Psychic Orb attacks.

**Comet Staff.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage plus 18 (4d8) psychic damage, and if the target is a creature, it must succeed on a DC 19 Constitution saving throw or be incapacitated until the end of its next turn.

**Psychic Orb.** Ranged Spell Attack: +11 to hit, range 120 feet, one creature. *Hit:* 27 (5d10) psychic damage.

**Collapse Distance (Recharge 6).** The seer warps space around one creature it can see within 30 feet of it. That creature must make a DC 19 Wisdom saving throw. On a failed save, the target, along with any equipment it is wearing or carrying, is teleported up to 60 feet to an unoccupied space the seer can see, and then each creature within 10 feet of the target's original space takes 39 (6d12) psychic damage. On a successful save, the target takes 19 (3d12) psychic damage and isn't teleported.


---

### Reactions

**Bend Space.** When the seer would be hit by an attack roll, it teleports, along with any equipment it is wearing or carrying, exchanging positions with another star spawn it can see within 60 feet of it. The other star spawn is hit by the attack instead.


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