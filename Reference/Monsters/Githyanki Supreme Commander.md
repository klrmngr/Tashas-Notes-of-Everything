---
type: pc
race: "Humanoid (gith)"
class:
 - "Githyanki Supreme Commander"
subClass:
 - "CR 14"
cover: "Githyanki Supreme Commander.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/14
  - source/mpmm
---
###### Githyanki Supreme Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Githyanki Supreme Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 18 | 16 | 16 | 18 |
| **Mod** | +4 | +3 | +4 | +3 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Gith
**Saving Throws:** Con +9, Int +8, Wis +8
**Skills:** Intimidation +9, Perception +8

---

### Traits

**Legendary Resistance (3/Day).** If the githyanki fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The githyanki makes two Silver Greatsword attacks.

**Silver Greatsword.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage plus 17 (5d6) psychic damage. On a critical hit against a target in an astral body (as with the astral projection spell), the githyanki can cut the silvery cord that tethers the target to its material body, instead of dealing damage.


---

### Bonus Actions

**Astral Step.** The githyanki teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


---

### Reactions

**Parry.** The githyanki adds 5 to its AC against one melee attack that would hit it. To do so, the githyanki must see the attacker and be wielding a melee weapon.


---

### Legendary Actions

### 

**Command Ally.** The githyanki targets one ally it can see within 30 feet of it. If the target can see or hear the githyanki, the target can make one melee weapon attack using its reaction, if available, and has advantage on the attack roll.

**Attack (2 Actions).** The githyanki makes one Silver Greatsword attack.


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