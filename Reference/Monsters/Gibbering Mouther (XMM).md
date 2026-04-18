---
type: pc
race: "Aberration"
class:
 - "Gibbering Mouther"
subClass:
 - "CR 2"
cover: "Gibbering Mouther.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/xmm
---
###### Gibbering Mouther
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gibbering Mouther.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 8 | 16 | 3 | 10 | 6 |
| **Mod** | +0 | -1 | +3 | -4 | +0 | -2 |

**Speed:** 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** —
**Condition Immunities:** prone

---

### Traits

**Aberrant Ground.** The ground in a 10-foot Emanation originating from the mouther is Difficult Terrain.

**Gibbering.** The mouther babbles incoherently while it doesn't have the Incapacitated condition. wis DC 10, any creature that starts its turn within 20 feet of the mouther while it is babbling.  The target rolls 1d8 to determine what it does during the current turn:
- **1-4.** The target does nothing.
- **5-6.** The target takes no action or Bonus Action and uses all its movement to move in a random direction.
- **7-8.** The target makes a melee attack against a randomly determined creature within its reach or does nothing if it can't make such an attack.


---

### Actions

**Bite.** m +2, reach 5 ft. *Hit:* 7 (2d6) Piercing damage. If the target is a Medium or smaller creature, it has the Prone condition. The target dies if it is reduced to 0 Hit Points by this attack. Its body is then absorbed into the mouther, leaving only equipment behind.

**Blinding Spittle (Recharge 5–6).** dex DC 10, each creature in a 10-foot-radius Sphere centered on a point within 30 feet.  7 (2d6) Radiant damage, and the target has the Blinded condition until the end of the mouther's next turn.


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