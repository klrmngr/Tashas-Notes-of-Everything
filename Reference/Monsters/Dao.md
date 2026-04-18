---
type: pc
race: "Elemental"
class:
 - "Dao"
subClass:
 - "CR 11"
cover: "Dao.png"
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
###### Dao
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Dao.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 187 (15d10 + 105) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 24 | 12 | 13 | 14 |
| **Mod** | +6 | +1 | +7 | +1 | +1 | +2 |

**Speed:** 30 ft., burrow 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Terran
**Saving Throws:** Int +5, Wis +5, Cha +6
**Condition Immunities:** petrified

---

### Traits

**Earth Glide.** The dao can burrow through nonmagical, unworked earth and stone. While doing so, the dao doesn't disturb the material it moves through.

**Elemental Demise.** If the dao dies, its body disintegrates into crystalline powder, leaving behind only equipment the dao was wearing or carrying.

**Sure-Footed.** The dao has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Multiattack.** The Dao makes two fist attacks or two maul attacks.

**Fist.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage.

**Maul.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 20 (4d6 + 6) bludgeoning damage. If the target is a Huge or smaller creature, it must succeed on a DC 18 Strength check or be knocked prone.


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