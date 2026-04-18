---
type: pc
race: "Monstrosity"
class:
 - "Storm Crab"
subClass:
 - "CR 11"
cover: "Storm Crab.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/11
  - source/bgg
---
###### Storm Crab
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Storm Crab.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 155 (10d20 + 50) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 5 | 14 | 9 |
| **Mod** | +6 | +0 | +5 | -3 | +2 | -1 |

**Speed:** 40 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 16
**Languages:** understands Giant but can't speak
**Saving Throws:** Str +10, Con +9
**Skills:** Perception +6
**Damage Resistances:** cold; fire; lightning

---

### Traits

**Amphibious.** The crab can breathe air and water.


---

### Actions

**Multiattack.** The crab makes two Claw attacks and one Stinger attack.

**Claw.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage. If the target is a Huge or smaller creature, it has the grappled condition (escape DC 16). The crab has four claws, each of which can grapple one target.

**Stinger.** Melee Weapon Attack: +10 to hit, reach 10 ft., one creature. *Hit:* 22 (3d10 + 6) piercing damage, and the target must succeed on a DC 17 Constitution saving throw or have the poisoned and paralyzed conditions for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending both the poisoned and paralyzed conditions on itself on a success.

**Water Jet (Recharge 5–6).** The crab exhales water in a 150-foot line that is 10 feet wide. Each creature in that area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes 27 (6d8) bludgeoning damage, is pushed up to 30 feet from the crab, and has the prone condition. On a successful save, a creature takes half as much damage only.


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