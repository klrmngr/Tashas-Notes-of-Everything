---
type: pc
race: "Humanoid (human)"
class:
 - "Dragonwing"
subClass:
 - "CR 2"
cover: "Dragonwing.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/hotdq
---
###### Dragonwing
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Dragonwing.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 13 | 11 | 11 | 13 |
| **Mod** | +0 | +3 | +1 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Wis +2
**Skills:** Deception +3, Stealth +5
**Damage Resistances:** one of the following: acid, cold, fire, lightning, poison

---

### Traits

**Dragon Fanatic.** The dragonwing has advantage on saving throws against being charmed or frightened. While the dragonwing can see a dragon or higher-ranking Cult of the Dragon cultist friendly to it, the dragonwing ignores the effects of being charmed or frightened.

**Fanatic Advantage.** Once per turn, if the dragonwing makes a weapon attack with advantage on the attack roll and hits, the target takes an extra 7 (2d6) damage.

**Limited Flight.** The dragonwing can use a bonus action to gain a flying speed of 30 feet until the end of its turn.

**Pack Tactics.** The dragonwing has advantage on an attack roll against a creature if at least one of the dragonwing's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The dragonwing attacks twice with its scimitar.

**Scimitar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 3 (1d6) damage of the type to which the cultist has resistance.


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