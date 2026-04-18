---
type: pc
race: "Monstrosity"
class:
 - "Giant Ice Toad"
subClass:
 - "CR 3"
cover: "Giant Ice Toad.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/tftyp
---
###### Giant Ice Toad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Giant Ice Toad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 8 | 10 | 6 |
| **Mod** | +3 | +1 | +2 | -1 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Ice Toad
**Damage Immunities:** cold

---

### Traits

**Amphibious.** The toad can breathe air and water.

**Cold Aura.** Any creature that starts its turn within 10 feet of the toad takes 5 (1d10) cold damage.

**Standing Leap.** The toad's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, and the target is grappled (escape DC 13). Until this grapple ends, the target is restrained, and the toad can't bite another target.

**Swallow.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller creature the toad is grappling. *Hit:* 10 (2d6 + 3) piercing damage, the target is swallowed, and the grapple ends. The swallowed target is blinded and restrained, it has 3 against attacks and other effects outside the toad, and it takes 10 (3d6) acid damage and 11 (2d10) cold damage at the start of each of the toad's turns. The toad can have only one target swallowed at a time.
If the toad dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 5 feet of movement, exiting prone.


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