---
type: pc
race: "Humanoid"
class:
 - "Diviner Wizard"
subClass:
 - "CR 8"
cover: "Diviner Wizard.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mpmm
---
###### Diviner Wizard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Diviner Wizard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 90 (20d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 18 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +4 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any four languages
**Saving Throws:** Int +7, Wis +4
**Skills:** Arcana +7, History +7

---

### Actions

**Multiattack.** The diviner makes three Arcane Burst attacks.

**Arcane Burst.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 20 (3d10 + 4) radiant damage.

**Overwhelming Revelation (Recharge 5–6).** The diviner magically creates a burst of illumination in a 10-foot-radius sphere centered on a point within 120 feet of it. Each creature in that area must make a DC 15 Wisdom saving throw. On a failed save, a creature takes 45 (10d8) psychic damage and is stunned until the end of the diviner's next turn. On a successful save, the creature takes half as much damage and isn't stunned.


---

### Reactions

**Portent (3/Day).** When the diviner or a creature it can see makes an attack roll, a saving throw, or an ability check, the diviner rolls a d20 and chooses whether to use that roll in place of the d20 rolled for the attack roll, saving throw, or ability check. 


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