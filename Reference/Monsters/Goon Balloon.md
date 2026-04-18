---
type: pc
race: "Aberration"
class:
 - "Goon Balloon"
subClass:
 - "CR 1/8"
cover: "Goon Balloon.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1-8
  - source/mcv1sc
---
###### Goon Balloon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Goon Balloon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 6 (1d8 + 2) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 14 | 11 | 14 | 4 |
| **Mod** | +0 | +0 | +2 | +0 | +2 | -3 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Deep Speech
**Saving Throws:** Con +4, Wis +4
**Skills:** Perception +6
**Damage Vulnerabilities:** piercing

---

### Traits

**Burst.** The goon balloon bursts when it drops to 0 hit points, releasing noxious gas in a 10-foot-radius sphere centered on itself. Creatures in that area must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Unusual Nature.** The goon balloon doesn't require air, food, or drink.


---

### Actions

**Multiattack.** The goon balloon makes two Claw attacks.

**Claw.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) slashing damage.

**Scintillating Eye.** Magical, kaleidoscopic light emanates from one of the goon balloon's eyes as the goon balloon targets one creature it can see within 30 feet of itself. The target must make a DC 12 Wisdom saving throw, taking 6 (1d12) psychic damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Float.** The goon balloon moves up to 20 feet vertically in one direction without provoking opportunity attacks. If it ends this movement suspended in the air, it hovers in place. It can't be knocked prone while airborne.


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