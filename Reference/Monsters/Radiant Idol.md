---
type: pc
race: "Celestial"
class:
 - "Radiant Idol"
subClass:
 - "CR 11"
cover: "Radiant Idol.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/11
  - source/erlw
---
###### Radiant Idol
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Radiant Idol.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 18 | 19 | 17 | 20 | 21 |
| **Mod** | +6 | +4 | +4 | +3 | +5 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Wis +9, Cha +9
**Skills:** Deception +9, Insight +9, Perception +9, Persuasion +9
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Aura of False Divinity.** A creature that starts its turn within 30 feet of the radiant idol must make a DC 17 Wisdom saving throw, provided the radiant idol isn't incapacitated. On a failed save, the creature is charmed by the radiant idol. A creature charmed in this way can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Once it succeeds on the saving throw, a creature is immune to this radiant idol's Aura of False Divinity for 24 hours.

**Magic Resistance.** The radiant idol has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The radiant idol makes two melee attacks.

**Flail.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage plus 18 (4d8) radiant damage.

**Radiant Strike (1/Day).** The radiant idol chooses a point on the ground it can see within 60 feet of it. A 30-foot-radius, 40-foot-high cylinder of bright light appears there until the start of the radiant idol's next turn. Each creature in the cylinder when it appears or that ends its turn there must make a DC 17 Constitution saving throw, taking 36 (8d8) radiant damage on a failed save, or half as much damage on a successful one.


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