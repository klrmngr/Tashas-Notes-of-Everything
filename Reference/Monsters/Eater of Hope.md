---
type: pc
race: "Fiend"
class:
 - "Eater of Hope"
subClass:
 - "CR 6"
cover: "Eater of Hope.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/mot
---
###### Eater of Hope
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Eater of Hope.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 14 | 12 | 11 | 16 |
| **Mod** | +4 | +3 | +2 | +1 | +0 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +5, Cha +6
**Skills:** Deception +6, Intimidation +6, Persuasion +6
**Damage Resistances:** cold; necrotic
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Insatiable Greed.** The eater of hope can sense the presence of gold within 1,000 feet of itself. It can determine which location has the greatest amount of gold and can sense the direction to that site. If the gold is being moved, it knows the direction of the movement. It can't locate gold if any thickness of clay or lead, even a thin sheet, blocks a direct path between it and the gold.

**Magic Resistance.** The eater of hope has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eater of hope makes two attacks with its claws.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 7 (2d6) necrotic damage.

**Breath of Hopelessness (Recharge 5–6).** The eater of hope exhales a miasma of Underworld winds in a 30-foot cone. Each creature in that area must make a DC 14 Charisma saving throw. On a failed save, the target takes 26 (4d12) necrotic damage and is cursed for 1 minute. While cursed in this way, the target takes an extra 6 (1d12) necrotic damage whenever the eater of hope hits it with an attack. On a successful save, the target takes half as much damage and isn't cursed.


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