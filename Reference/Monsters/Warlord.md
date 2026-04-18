---
type: pc
race: "Humanoid"
class:
 - "Warlord"
subClass:
 - "CR 12"
cover: "Warlord.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/mpmm
---
###### Warlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Warlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 229 (27d8 + 108) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 12 | 12 | 18 |
| **Mod** | +5 | +3 | +4 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** any two languages
**Saving Throws:** Str +9, Dex +7, Con +8
**Skills:** Athletics +9, Intimidation +8, Perception +5, Persuasion +8

---

### Traits

**Indomitable (3/Day).** The warlord can reroll a saving throw it fails. It must use the new roll.

**Survivor.** The warlord regains 10 hit points at the start of its turn if it has fewer than half its hit points but at least 1 hit point.


---

### Actions

**Multiattack.** The warlord makes two Greatsword or Short bow attacks.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Shortbow.** Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


---

### Legendary Actions

### 

**Command Ally.** The warlord targets one ally it can see within 30 feet of it. If the target can see and hear the warlord, the target can make one weapon attack as a reaction and gains advantage on the attack roll.

**Weapon Attack.** The warlord makes one Greatsword or Shortbow attack.

**Frighten Foe (Costs 2 Actions).** The warlord targets one creature it can see within 30 feet of it. If the target can see and hear it, the target must succeed on a DC 16 Wisdom saving throw or be frightened until the end of warlord's next turn.


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