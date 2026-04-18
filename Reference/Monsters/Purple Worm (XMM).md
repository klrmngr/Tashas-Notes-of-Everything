---
type: pc
race: "Monstrosity"
class:
 - "Purple Worm"
subClass:
 - "CR 15"
cover: "Purple Worm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/15
  - source/xmm
---
###### Purple Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Purple Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 247 (15d20 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 7 | 22 | 1 | 8 | 4 |
| **Mod** | +9 | -2 | +6 | -5 | -1 | -3 |

**Speed:** 50 ft., burrow 50 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Tremorsense 60 ft., passive Perception 9
**Languages:** —
**Saving Throws:** Con +11, Wis +4

---

### Traits

**Tunneler.** The worm can burrow through solid rock at half its Burrow Speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The worm makes one Bite attack and one Tail Stinger attack.

**Bite.** m +14, reach 10 ft. *Hit:* 22 (3d8 + 9) Piercing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 19), and it has the Restrained condition until the grapple ends.

**Tail Stinger.** m +14, reach 10 ft. *Hit:* 16 (2d6 + 9) Piercing damage plus 35 (10d6) Poison damage.


---

### Bonus Actions

**Swallow.** str DC 19, one Large or smaller creature Grappled by the worm (it can have up to three creatures swallowed at a time).  The target is swallowed by the worm, and the Grappled condition ends. A swallowed creature has the Blinded and Restrained conditions, has Total Cover against attacks and other effects outside the worm, and takes 17 (5d6) Acid damage at the start of each of the worm's turns.
If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 5 feet of the worm and has the Prone condition. If the worm dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 20 feet of movement, exiting Prone.


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