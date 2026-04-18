---
type: pc
race: "Humanoid (human)"
class:
 - "Dragonclaw"
subClass:
 - "CR 1"
cover: "Dragonclaw.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/hotdq
---
###### Dragonclaw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Dragonclaw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 13 | 11 | 10 | 12 |
| **Mod** | -1 | +3 | +1 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Wis +2
**Skills:** Deception +3, Stealth +5

---

### Traits

**Dragon Fanatic.** The dragonclaw has advantage on saving throws against being charmed or frightened. While the dragonclaw can see a dragon or higher-ranking Cult of the Dragon cultist friendly to it, the dragonclaw ignores the effects of being charmed or frightened.

**Fanatic Advantage.** Once per turn, if the dragonclaw makes a weapon attack with advantage on the attack roll and hits, it deals an extra 7 (2d6) damage.

**Pack Tactics.** The dragonclaw has advantage on an attack roll against a creature if at least one of the dragonclaw's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The dragonclaw attacks twice with its scimitar.

**Scimitar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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