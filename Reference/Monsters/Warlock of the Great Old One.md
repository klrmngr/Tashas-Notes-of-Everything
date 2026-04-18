---
type: pc
race: "Humanoid"
class:
 - "Warlock of the Great Old One"
subClass:
 - "CR 6"
cover: "Warlock of the Great Old One.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/mpmm
---
###### Warlock of the Great Old One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Warlock of the Great Old One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 15 | 12 | 12 | 18 |
| **Mod** | -1 | +3 | +2 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** any two languages, telepathy 30 ft.
**Saving Throws:** Wis +4, Cha +7
**Skills:** Arcana +4, History +4
**Damage Resistances:** psychic

---

### Traits

**Whispering Aura.** At the start of each of the warlock's turns, each creature of its choice within 10 feet of it must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage, provided that the warlock isn't incapacitated.


---

### Actions

**Multiattack.** The warlock makes two Dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 10 (3d6) psychic damage.

**Howling Void.** The warlock opens a momentary extraplanar rift within 60 feet of it. The rift is a scream-filled, 20-foot cube. Each creature in that area must make a DC 15 Wisdom saving throw. On a failed save, a creature takes 9 (2d8) psychic damage and is frightened of the warlock until the start of the warlock's next turn. On a successful save, a creature takes half as much damage and isn't frightened.


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