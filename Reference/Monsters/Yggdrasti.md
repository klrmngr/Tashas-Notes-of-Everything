---
type: pc
race: "Plant"
class:
 - "Yggdrasti"
subClass:
 - "CR 7"
cover: "Yggdrasti.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/gargantuan
  - cr/7
  - source/mcv1sc
---
###### Yggdrasti
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Yggdrasti.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Gargantuan Plant |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 112 (9d20 + 18) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 15 | 3 | 10 | 3 |
| **Mod** | +5 | +0 | +2 | -4 | +0 | -4 |

**Speed:** 30 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing
**Damage Immunities:** lightning
**Condition Immunities:** blinded; deafened; exhaustion

---

### Traits

**Cavities.** The yggdrasti has 1d4 + 2 cavities in its trunk. Each cavity is big enough to hold one Medium creature, two Small creatures, or eight Tiny creatures. A creature inside a cavity has 3 against attacks and other effects that originate outside the cavity. The yggdrasti's cavities aren't connected to one another.

**False Appearance.** If the yggdrasti is motionless and rooted in the ground at the start of combat, it looks just like a dead tree and has advantage on its initiative roll. Moreover, if a creature hasn't observed the rooted yggdrasti move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the yggdrasti is animate.

**Lightning Conduit.** If the yggdrasti is subjected to lightning damage, it is unhurt, and the lightning damage is instead divided evenly among all creatures it is grappling. In addition, the yggdrasti regains one use of Lightning Discharge.

**Unusual Nature.** The yggdrasti doesn't require air or sleep.


---

### Actions

**Multiattack.** The yggdrasti makes two Root attacks and uses Lightning Discharge (if available).

**Root.** Melee Weapon Attack: +8 to hit, reach 20 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage, and if the target is a creature, it is grappled (escape DC 15). The yggdrasti has four roots, each of which can grapple one target.

**Lightning Discharge (3/Day).** The yggdrasti shoots lightning at one creature within 120 feet of itself. The target must make a DC 13 Dexterity saving throw, taking 31 (7d8) lightning damage on a failed save, or half as much damage on a successful one.


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