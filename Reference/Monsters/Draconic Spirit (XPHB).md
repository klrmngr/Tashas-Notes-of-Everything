---
type: pc
race: "Dragon"
class:
 - "Draconic Spirit"
subClass:
 - "CR —"
cover: "Draconic Spirit.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/—
  - source/xphb
---
###### Draconic Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Draconic Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 50 + 10 for each spell level above 5 |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 17 | 10 | 14 | 14 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +2 |

**Speed:** 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 60 ft., passive Perception 12
**Languages:** Draconic, understands the languages you know
**Damage Resistances:** acid; cold; fire; lightning; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Shared Resistances.** When you summon the spirit, choose one of its Resistances. You have Resistance to the chosen damage type until the spell ends.


---

### Actions

**Multiattack.** The spirit makes a number of Rend attacks equal to half the spell's level (round down), and it uses Breath Weapon.

**Rend.** m attack: Bonus equals your spell attack modifier, reach 10 feet. *Hit:* 1d6 + 4 + summonSpellLevel Piercing damage.

**Breath Weapon.** dex DC equals your spell save DC, each creature in a 30-foot Cone.  2d6 damage of a type this spirit has Resistance to (your choice when you cast the spell).  Half damage.


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