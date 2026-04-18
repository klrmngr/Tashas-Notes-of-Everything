---
type: pc
race: "Fey"
class:
 - "Darkling Elder"
subClass:
 - "CR 2"
cover: "Darkling Elder.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/vgm
---
###### Darkling Elder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Darkling Elder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 17 | 12 | 10 | 14 | 13 |
| **Mod** | +1 | +3 | +1 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 16
**Languages:** Elvish, Sylvan
**Skills:** Acrobatics +5, Deception +3, Perception +6, Stealth +7

---

### Traits

**Death Burn.** When the darkling elder dies, magical light flashes out from it in a 10-foot radius as its body and possessions, other than metal or magic objects, burn to ash. Any creature in that area must make a DC 11 Constitution saving throw. On a failure, the creature takes 7 (2d6) radiant damage and, if the creature can see the light, is blinded until the end of its next turn. If the saving throw is successful, the creature takes half the damage and isn't blinded.


---

### Actions

**Multiattack.** The darkling elder makes two melee attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage. If the darkling elder had advantage on the attack roll, the attack deals as: extra 10 (3d6) piercing damage.

**Darkness (Recharges after a Short or Long Rest).** The darkling elder casts darkness without any components. Wisdom is its spellcasting ability.


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