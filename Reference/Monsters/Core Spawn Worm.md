---
type: pc
race: "Aberration"
class:
 - "Core Spawn Worm"
subClass:
 - "CR 15"
cover: "Core Spawn Worm.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/gargantuan
  - cr/15
  - source/egw
---
###### Core Spawn Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Core Spawn Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Gargantuan Aberration |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 279 (18d20 + 90) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 5 | 20 | 6 | 8 | 4 |
| **Mod** | +8 | -3 | +5 | -2 | -1 | -3 |

**Speed:** 60 ft., burrow 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 14
**Languages:** understands Deep Speech but can't speak
**Saving Throws:** Con +10, Wis +4
**Skills:** Perception +4
**Damage Vulnerabilities:** cold
**Damage Immunities:** fire; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Illumination.** The worm sheds dim light in a 20-foot radius.

**Radiant Mirror.** If the worm takes radiant damage, each creature within 20 feet of it takes that damage as well.

**Tunneler.** The worm can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The worm makes two attacks: one with its barbed tentacles and one with its bite.

**Barbed Tentacles.** Melee Weapon Attack: +13 to hit, reach 10 ft., one creature. *Hit:* 25 (5d6 + 8) piercing damage, and the target is grappled (escape DC 18). Until this grapple ends, the target is restrained. The tentacles can grapple only one creature at a time.

**Bite.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 30 (5d8 + 8) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Dexterity saving throw or be swallowed by the worm. A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the worm, and takes 21 (6d6) fire damage at the start of each of the worm's turns.
If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the worm. If the worm dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.


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