---
type: pc
race: "Celestial"
class:
 - "Living Portent"
subClass:
 - "CR 3"
cover: "Living Portent.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/3
  - source/bmt
---
###### Living Portent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Living Portent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 14 | 16 | 15 |
| **Mod** | +2 | +3 | +2 | +2 | +3 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** all
**Saving Throws:** Dex +5, Wis +5
**Skills:** Arcana +6, History +6, Insight +5, Perception +5
**Damage Immunities:** radiant
**Condition Immunities:** exhaustion

---

### Traits

**Brilliance (True Form Only).** The living portent sheds bright light for 30 feet and dim light for an additional 30 feet.


---

### Actions

**Multiattack.** The living portent makes two Radiant Strike attacks.

**Radiant Strike.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 9 (1d12 + 3) radiant damage.

**Prophetic Blessing.** The living portent magically infuses the power of its prophecy into another willing creature the living portent can see within 30 feet of itself. The target's hit point maximum and current hit points increase by 7 (1d8 + 3), and it gains a prophecy die, a d8. Once during each of the creature's turns, when it fails an ability check or saving throw or misses an attack roll, it can roll the prophecy die and add the number rolled to the total, potentially changing the outcome. The blessing ends after 1 hour or when the living portent ends the blessing (no action required) or uses this action again.


---

### Bonus Actions

**Change Shape.** The living portent magically transforms into a Humanoid while retaining its game statistics (other than its size and Brilliance trait). The transformation ends if the living portent is reduced to 0 hit points or uses a bonus action to end it.


---

### Reactions

**Price of Defiance.** When the living portent is damaged by a creature that it can see within 120 feet of itself, radiant power sears the creature. The creature must make a DC 13 Constitution saving throw, taking 10 (3d6) radiant damage on a failed save, or half as much damage on a successful one.


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