---
type: pc
race: "Humanoid (cleric)"
class:
 - "War Priest"
subClass:
 - "CR 9"
cover: "War Priest.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mpmm
---
###### War Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[War Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 11 | 17 | 13 |
| **Mod** | +3 | +0 | +2 | +0 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any two languages
**Saving Throws:** Con +6, Wis +7
**Skills:** Intimidation +5, Religion +4

---

### Actions

**Multiattack.** The war priest makes two Maul attacks, and it uses Holy Fire.

**Maul.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage  plus *Hit:* 10 (3d6) radiant damage.

**Holy Fire.** The war priest targets one creature it can see within 60 feet of it. The target must make a DC 15 Wisdom saving throw. On a failed save, the target takes 12 (2d8 + 3) radiant damage, and it is blinded until the start of the war priest's next turn. On a successful save, the target takes half as much damage and isn't blinded.


---

### Bonus Actions

**Healing Light (Recharge 4–6).** The war priest or one creature of its choice within 60 feet of it regains 12 (2d8 + 3) hit points.


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