---
type: pc
race: "Elemental"
class:
 - "Efreeti"
subClass:
 - "CR 11"
cover: "Efreeti.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/mm
---
###### Efreeti
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Efreeti.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 200 (16d10 + 112) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 24 | 16 | 15 | 16 |
| **Mod** | +6 | +1 | +7 | +3 | +2 | +3 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Ignan
**Saving Throws:** Int +7, Wis +6, Cha +7
**Damage Immunities:** fire

---

### Traits

**Elemental Demise.** If the efreeti dies, its body disintegrates in a flash of fire and puff of smoke, leaving behind only equipment the efreeti was wearing or carrying.


---

### Actions

**Multiattack.** The efreeti makes two scimitar attacks or uses its Hurl Flame twice.

**Scimitar.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 7 (2d6) fire damage.

**Hurl Flame.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 17 (5d6) fire damage.


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