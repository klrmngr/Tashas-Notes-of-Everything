---
type: pc
race: "Aberration"
class:
 - "Otyugh Mutate"
subClass:
 - "CR 6"
cover: "Otyugh Mutate.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/6
  - source/pabtso
---
###### Otyugh Mutate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Otyugh Mutate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 76 (8d10 + 32) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 18 | 10 | 15 | 6 |
| **Mod** | +4 | +0 | +4 | +0 | +2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Otyugh, telepathy 120 ft.
**Saving Throws:** Str +7, Con +7
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Virulent Breath.** Noxious gas from the mutate's digestion of previous meals spews from its mouth. At the start of the mutate's turn, each creature within 5 feet of it must succeed on a DC 15 Constitution saving throw or take 3 (1d6) poison damage.


---

### Actions

**Multiattack.** The mutate makes two Bite or Tentacle attacks. It can replace one of these attacks with Chitin Slam.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or have the poisoned condition. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 (1d10) on a failure. On a successful save, the target is no longer poisoned. The target dies if its hit point maximum is reduced to 0. This reduction to the target's hit point maximum lasts until it no longer has the poisoned condition.

**Tentacle.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 15) and the restrained condition until this grapple ends. The mutate has two tentacles that can grapple one target each.

**Chitin Slam.** The mutate targets one creature it is grappling, slamming the creature against its chitinous plating. The creature must succeed on a DC 15 Constitution saving throw or take 16 (3d10) bludgeoning damage and have the stunned condition until the end of the mutate's next turn.


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