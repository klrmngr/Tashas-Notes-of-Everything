---
type: pc
race: "Humanoid (human)"
class:
 - "Dragonfang"
subClass:
 - "CR 5"
cover: "Dragonfang.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/rot
---
###### Dragonfang
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Dragonfang.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 12 | 12 | 14 |
| **Mod** | +0 | +3 | +2 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Wis +4
**Skills:** Deception +5, Stealth +6
**Damage Resistances:** one of the following: acid, cold, fire, lightning, poison

---

### Traits

**Dragon Fanatic.** The dragonfang has advantage on saving throws against being charmed or frightened. While the dragonfang can see a dragon or higher-ranking Cult of the Dragon cultist friendly to it, the dragonfang ignores the effects of being charmed or frightened.

**Fanatic Advantage.** Once per turn, if the dragonfang makes a weapon attack with advantage on the attack roll and hits, the target takes an extra 10 (3d6) damage.

**Limited Flight.** The dragonfang can use a bonus action to gain a flying speed of 30 feet until the end of its turn.

**Pack Tactics.** The dragonfang has advantage on an attack roll against a creature if at least one of the dragonfang's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The Dragonfang attacks twice with its shortsword.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 7 (2d6) damage of the type to which the dragonfang has resistance.

**Orb of Dragon's Breath (2/Day).** Ranged Spell Attack: +5 to hit, range 50 ft., one target. *Hit:* 22 (5d8) damage of the type to which the dragonfang has damage resistance.


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