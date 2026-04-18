---
type: pc
race: "Construct"
class:
 - "Steel Predator"
subClass:
 - "CR 16"
cover: "Steel Predator.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/16
  - source/mpmm
---
###### Steel Predator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Steel Predator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 207 (18d10 + 108) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 17 | 22 | 4 | 14 | 6 |
| **Mod** | +7 | +3 | +6 | -3 | +2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 17
**Languages:** understands Modron and the language of its owner but can't speak
**Skills:** Perception +7, Stealth +8, Survival +7
**Damage Resistances:** cold; lightning; necrotic; thunder
**Damage Immunities:** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Magic Resistance.** The steel predator has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The steel predator doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The steel predator makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 18 (2d10 + 7) lightning damage.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) force damage.

**Stunning Roar (Recharge 5–6).** The steel predator emits a roar in a 60-foot cone. Each creature in that area must make a DC 19 Constitution saving throw. On a failed save, a creature takes 33 (6d10) thunder damage, drops everything it's holding, and is stunned for 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage and isn't stunned.


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