---
type: pc
race: "Monstrosity"
class:
 - "Star Angler"
subClass:
 - "CR 8"
cover: "Star Angler.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/8
  - source/veor
---
###### Star Angler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Star Angler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 15 | 17 | 3 | 14 | 6 |
| **Mod** | +5 | +2 | +3 | -4 | +2 | -2 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (can't see beyond this radius), passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +8

---

### Traits

**Avoidance.** If the star angler is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw and only half damage if it fails.

**Illumination.** The star angler's lure sheds bright light in a 30-foot radius and dim light for an additional 30 feet.


---

### Actions

**Multiattack.** The star angler makes three Bite attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage.


---

### Bonus Actions

**Lure Charm.** The star angler's lure flares with enchanting starlight, targeting one creature the star angler can see within 120 feet of itself. The target must succeed on a DC 13 Wisdom saving throw or have the charmed condition until the start of the star angler's next turn. While charmed in this way, the target has the incapacitated condition and must use its movement on its turn to move directly toward the star angler; a charmed target doesn't avoid opportunity attacks, but it does avoid damaging terrain. A target can be charmed by only one star angler at a time.


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