---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Arcanaloth"
subClass:
 - "CR 12"
cover: "Arcanaloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/mm
---
###### Arcanaloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Arcanaloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 14 | 20 | 16 | 17 |
| **Mod** | +3 | +1 | +2 | +5 | +3 | +3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +5, Int +9, Wis +7, Cha +7
**Skills:** Arcana +13, Deception +11, Insight +11, Perception +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Magic Resistance.** The arcanaloth has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The arcanaloth's weapon attacks are magical.


---

### Actions

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) slashing damage. The target must make a DC 14 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.

**Teleport.** The arcanaloth magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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