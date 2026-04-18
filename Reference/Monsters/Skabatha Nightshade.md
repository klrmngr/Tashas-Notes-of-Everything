---
type: pc
race: "Fey (hag)"
class:
 - "Skabatha Nightshade"
subClass:
 - "CR 8"
cover: "Skabatha Nightshade.png"
campaign:
locations:
tags:
  - race/hag
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/8
  - source/wbtw
---
###### Skabatha Nightshade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Skabatha Nightshade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Fey (hag) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Fey (hag) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 9 | 16 | 12 | 16 | 15 |
| **Mod** | +4 | -1 | +3 | +1 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 16
**Languages:** Common, Elvish, Infernal, Sylvan
**Saving Throws:** Con +6, Int +4, Wis +6, Cha +5
**Skills:** Arcana +7, Deception +5, Perception +6, Stealth +2

---

### Traits

**Boon of Immortality.** Skabatha is immune to any effect that would age her, and she can't die from old age.

**Forgetfulness.** The first creature that Skabatha sees after she finishes a long rest is invisible to her. She can't remember seeing the creature or perceive it using her truesight until the end of her next long rest.


---

### Actions

**Multiattack.** Skabatha makes two Claw attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 25 (6d6 + 4) poison damage.


---

### Bonus Actions

**Alter Size.** Skabatha magically shrinks herself to Tiny size (between 4 and 8 inches tall) or returns to her normal size. If Skabatha lacks the room to return to her normal size, she attains the maximum size possible in the space available. Anything she is wearing or carrying changes size along with her.
As a Tiny creature, Skabatha deals 2 (1d4) poison damage when she hits with a Claw attack. She has advantage on Dexterity (Stealth) checks, and disadvantage on Strength checks and Strength saving throws. Her statistics otherwise remain unchanged.


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