---
type: pc
race: "Monstrosity"
class:
 - "Shadow Mastiff Alpha"
subClass:
 - "CR 3"
cover: "Shadow Mastiff Alpha.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mpmm
---
###### Shadow Mastiff Alpha
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Shadow Mastiff Alpha.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 6 | 12 | 5 |
| **Mod** | +3 | +2 | +1 | -2 | +1 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +6
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks while in dim light or darkness

---

### Traits

**Ethereal Awareness.** The shadow mastiff can see ethereal creatures and objects.

**Sunlight Weakness.** While in bright light created by sunlight, the shadow mastiff has disadvantage on attack rolls, ability checks, and saving throws.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.

**Terrifying Howl (Recharge 6).** The shadow mastiff howls. Any Beast or Humanoid within 300 feet of it must succeed on a DC 11 Wisdom saving throw or be frightened of it for 1 minute. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's save is successful or the effect ends for it, the target is immune to any shadow mastiff's Terrifying Howl for the next 24 hours.


---

### Bonus Actions

**Shadow Blend.** While in dim light or darkness, the shadow mastiff becomes invisible, along with anything it is wearing or carrying. The invisibility lasts until the shadow mastiff uses a bonus action to end it or until the shadow mastiff attacks, is in bright light, or is incapacitated.


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