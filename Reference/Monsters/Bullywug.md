---
type: pc
race: "Humanoid (bullywug)"
class:
 - "Bullywug"
subClass:
 - "CR 1/4"
cover: "Bullywug.png"
campaign:
locations:
tags:
  - race/bullywug
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/mm
---
###### Bullywug
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Bullywug.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bullywug) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (hide armor, shield) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (bullywug) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 12 | 13 | 7 | 10 | 7 |
| **Mod** | +1 | +1 | +1 | -2 | +0 | -2 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Bullywug
**Skills:** Stealth +3

---

### Traits

**Amphibious.** The bullywug can breathe air and water.

**Speak with Frogs and Toads.** The bullywug can communicate simple concepts to frogs and toads when it speaks in Bullywug.

**Swamp Camouflage.** The bullywug has advantage on Dexterity (Stealth) checks made to hide in swampy terrain.

**Standing Leap.** The bullywug's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Multiattack.** The bullywug makes two melee attacks: one with its bite and one with its spear.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) bludgeoning damage.

**Spear.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing damage if used with two hands to make a melee attack.


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