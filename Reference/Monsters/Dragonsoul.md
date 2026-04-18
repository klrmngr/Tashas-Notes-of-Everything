---
type: pc
race: "Humanoid (human)"
class:
 - "Dragonsoul"
subClass:
 - "CR 7"
cover: "Dragonsoul.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/rot
---
###### Dragonsoul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Dragonsoul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 13 | 12 | 16 |
| **Mod** | +0 | +4 | +2 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Wis +4
**Skills:** Deception +6, Stealth +7
**Damage Resistances:** one of the following: acid, cold, fire, lightning, poison

---

### Traits

**Dragon Fanatic.** The dragonsoul has advantage on saving throws against being charmed or frightened. While the dragonsoul can see a dragon or higher-ranking Cult of the Dragon cultist friendly to it, the dragonsoul ignores the effects of being charmed or frightened.

**Fanatic Advantage.** Once per turn, if the dragonsoul makes a weapon attack with advantage on the attack roll and hits, the target takes an extra 10 (3d6) damage.

**Limited Flight.** The dragonsoul can use a bonus action to gain a flying speed of 30 feet until the end of its turn.

**Pack Tactics.** The dragonsoul has advantage on an attack roll against a creature if at least one of the dragonsoul's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The Dragonsoul attacks twice with its shortsword.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 10 (3d6) damage of the type to which the dragonsoul has resistance.

**Orb of Dragon's Breath (3/Day).** Ranged Spell Attack: +7 to hit, range 90 ft., one target. *Hit:* 27 (6d8) damage of the type to which the dragonsoul has damage resistance.


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