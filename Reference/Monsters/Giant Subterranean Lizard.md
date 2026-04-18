---
type: pc
race: "Beast"
class:
 - "Giant Subterranean Lizard"
subClass:
 - "CR 4"
cover: "Giant Subterranean Lizard.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/4
  - source/tftyp
---
###### Giant Subterranean Lizard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Giant Subterranean Lizard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 66 (7d12 + 21) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 17 | 2 | 10 | 7 |
| **Mod** | +5 | -1 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Skills:** Stealth +3

---

### Actions

**Multiattack.** The lizard makes two attacks: one with its bite and one with its tail. One attack can be replaced by Swallow.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage and the target is grappled (escape DC 15). Until this grapple ends, the target is restrained, and the lizard can't bite another target.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target not grappled by the lizard. *Hit:* 12 (2d6 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Swallow.** Melee Weapon Attack: +7 to hit, reach 5 ft., one Medium or smaller creature the lizard is grappling. *Hit:* 16 (2d10 + 5) piercing damage. The target is swallowed, and the grapple ends. The swallowed target is blinded and restrained, it has 3 against attacks and other effects outside the lizard, and it takes 10 (3d6) acid damage at the start of each of the lizard's turns. The lizard can have only one target swallowed at a time.
If the lizard dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 10 feet of movement, exiting prone.


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