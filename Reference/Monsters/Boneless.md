---
type: pc
race: "Undead"
class:
 - "Boneless"
subClass:
 - "CR 1"
cover: "Boneless.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/vrgr
---
###### Boneless
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Boneless.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 1 | 10 | 1 |
| **Mod** | +3 | +2 | +2 | -5 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages it knew in life but can't speak
**Skills:** Stealth +4
**Damage Resistances:** bludgeoning; poison
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Compression.** The boneless can move through any opening at least 1 inch wide without squeezing. It can also squeeze to fit into a space that a Tiny creature could fit in.

**Unusual Nature.** The boneless doesn't require sleep.


---

### Actions

**Multiattack.** The boneless makes two Slam attacks. If both attacks hit a Large or smaller creature, the creature is grappled (escape DC 13), and the boneless can use Crushing Embrace.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.

**Crushing Embrace.** The boneless wraps its body around a Large or smaller creature grappled by it. While the boneless is attached, the target is blinded and is unable to breathe. The target must succeed on a DC 13 Strength saving throw at the start of each of the boneless' turns or take 5 (1d4 + 3) bludgeoning damage. If something moves the target, the boneless moves with it. The boneless can detach itself by spending 5 feet of its movement. A creature, including the target, can use its action to try to detach the boneless and force it to move into the nearest unoccupied space, doing so with a successful DC 13 Strength check. When the boneless dies, it detaches from any creature it is attached to.


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