---
type: pc
race: "Ooze"
class:
 - "Dragonblood Ooze"
subClass:
 - "CR 5"
cover: "Dragonblood Ooze.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/large
  - cr/5
  - source/ftd
---
###### Dragonblood Ooze
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonblood Ooze.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Ooze |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 6 | 17 | 2 | 12 | 10 |
| **Mod** | +4 | -2 | +3 | -4 | +1 | +0 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 14
**Languages:** understands Draconic and the languages of its creator but can't speak
**Skills:** Perception +4, Stealth +4
**Damage Resistances:** acid; cold; fire; lightning; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; prone; restrained

---

### Traits

**Amorphous.** The ooze can move through a space as narrow as 1 inch wide without squeezing.

**Spider Climb.** The ooze can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The ooze makes two Pseudopod attacks. The ooze can replace one Pseudopod attack with its Slime Breath, if available.

**Pseudopod.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage plus 14 (4d6) acid damage. If the target is a Large or smaller creature, it is grappled (escape DC 15). Until this grapple ends, the target takes 7 (2d6) acid damage at the start of each of its turns.

**Slime Breath (Recharge 6).** The ooze expels a spray of its gelatinous mass in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw. On a failed save, the creature takes 22 (4d10) acid damage and is pulled up to 30 feet straight toward the ooze. On a successful save, the creature takes half as much damage and isn't pulled.


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