---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Drannin Splithelm"
subClass:
 - "CR 7"
cover: "Drannin Splithelm.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/pota
---
###### Drannin Splithelm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Drannin Splithelm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 18 | 11 | 8 | 12 |
| **Mod** | +4 | +0 | +4 | +0 | -1 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Dwarvish
**Skills:** Athletics +7, Intimidation +4
**Damage Resistances:** cold; poison

---

### Traits

**Action Surge (Recharges after a Short or Long Rest).** Drannin takes an additional action on his turn.

**Brute.** A melee weapon deals one extra die of its damage when Drannin hits with it (included in the attack).

**Dwarven Resilience.** Drannin has advantage on saving throws against poison.

**Indomitable (Recharges after a Short or Long Rest).** Drannin can reroll a saving throw that he fails. He must use the new roll.

**Second Wind (Recharges after a Short or Long Rest).** Drannin can use a bonus action to regain 16 (1d10 + 11) hit points.

**Special Equipment.** Drannin wears a control amulet for his [[Shield Guardian]] (see the Monster Manual) and a ring of cold resistance. He also carries a potion of frost giant strength.


---

### Actions

**Multiattack.** Drannin makes three attacks with his greataxe.

**Greataxe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 17 (2d12 + 4) slashing damage.


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