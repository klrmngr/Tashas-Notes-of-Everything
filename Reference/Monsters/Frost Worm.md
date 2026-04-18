---
type: pc
race: "Monstrosity"
class:
 - "Frost Worm"
subClass:
 - "CR 17"
cover: "Frost Worm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/17
  - source/egw
---
###### Frost Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Frost Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 264 (16d20 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 8 | 22 | 1 | 5 | 5 |
| **Mod** | +9 | -1 | +6 | -5 | -3 | -3 |

**Speed:** 40 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 7
**Languages:** —
**Saving Throws:** Con +12, Wis +3
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold

---

### Traits

**Freezing Body.** A creature that touches the worm or hits it with a melee attack while within 5 feet of it takes 10 (3d6) cold damage.

**Death Burst.** When the worm dies, it explodes in a burst of frigid energy. Each creature within 60 feet of it must make a DC 20 Dexterity saving throw, taking 28 (8d6) cold damage on a failed save, or half as much damage on a successful one. Creatures inside the worm when it dies automatically fail this saving throw.

**Tunneler.** The worm can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The worm makes two bite attacks, or uses its Trill and makes a bite attack.

**Bite.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) piercing damage plus 10 (3d6) cold damage. If the target is a Large or smaller creature, it must succeed on a DC 20 Dexterity saving throw or be swallowed by the worm. A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the worm, and takes 10 (3d6) acid damage and 10 (3d6) cold damage at the start of each of the worm's turns.
If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the worm.

**Trill.** The frost worm emits a haunting cry. Each creature within 60 feet of the worm that can hear it must succeed on a DC 20 Wisdom saving throw or be stunned for 1 minute. A creature can repeat the saving throw each time it takes damage and at the end of each of its turns, ending the effect on itself on a success. Once a creature successfully saves against this effect, or if this effect ends for it, that creature is immune to the Trill of all frost worms for the next 24 hours. Frost worms are immune to this effect.


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