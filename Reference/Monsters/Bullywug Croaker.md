---
type: pc
race: "Humanoid (bullywug)"
class:
 - "Bullywug Croaker"
subClass:
 - "CR 2"
cover: "Bullywug Croaker.png"
campaign:
locations:
tags:
  - race/bullywug
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/gos
---
###### Bullywug Croaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Bullywug Croaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bullywug) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (hide armor, shield) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (bullywug) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 12 | 7 | 15 | 10 |
| **Mod** | +2 | +1 | +1 | -2 | +2 | +0 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Bullywug
**Saving Throws:** Con +3
**Skills:** Perception +4, Stealth +3

---

### Traits

**Amphibious.** The croaker can breathe air and water.

**Speak with Frogs and Toads.** The croaker can communicate simple concepts to frogs and toads when it speaks in Bullywug.

**Standing Leap.** The croaker's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

**Swamp Camouflage.** The croaker has advantage on Dexterity (Stealth) checks made to hide in swampy terrain.


---

### Actions

**Spear.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Glaaar-pat (3/Day).** The croaker sings a song of marshy doom. Each chosen creature within 30 feet of the croaker that can hear the song must make a DC 12 Wisdom saving throw, taking 9 (2d8) psychic damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw also has disadvantage on Constitution saving throws until the end of its next turn.

**Rooooo-glog (1/Day).** The croaker sings an ode to an elder froghemoth. Each bullywug within 30 feet of the croaker that can hear the song gains 10 temporary hit points.


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