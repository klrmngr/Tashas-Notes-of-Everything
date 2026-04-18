---
type: pc
race: "Aberration"
class:
 - "Neo-Otyugh"
subClass:
 - "CR 7"
cover: "Neo-Otyugh.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/7
  - source/imr
---
###### Neo-Otyugh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Neo-Otyugh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 150 (12d12 + 72) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 22 | 12 | 13 | 6 |
| **Mod** | +5 | +0 | +6 | +1 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Otyugh
**Saving Throws:** Con +9
**Condition Immunities:** poisoned

---

### Traits

**Limited Telepathy.** The otyugh can magically transmit simple messages and images to any creature within 120 feet of it that can understand a language. This form of telepathy doesn't allow the receiving creature to telepathically respond.


---

### Actions

**Multiattack.** The neo-otyugh makes three attacks: one with its bite and two with its tentacles.

**Bite.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw against disease or become poisoned until the disease is cured. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 (1d10) on a failure. The disease is cured on a success. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 15 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage. If the target is Large or smaller, it is grappled (escape DC 16) and restrained until the grapple ends. The neo-otyugh has two tentacles, each of which can grapple one target.

**Tentacle Slam.** The neo-otyugh slams creatures grappled by it into each other or a solid surface. Each creature must succeed on a DC 16 Constitution saving throw or take 15 (3d6 + 5) bludgeoning damage and be stunned until the end of the neo-otyugh's next turn. On a successful save, the target takes half the bludgeoning damage and isn't stunned.


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