---
type: pc
race: "Aberration"
class:
 - "Breath Drinker"
subClass:
 - "CR 14"
cover: "Breath Drinker.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/14
  - source/bmt
---
###### Breath Drinker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Breath Drinker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 157 (21d8 + 63) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 18 | 16 | 11 | 15 | 20 |
| **Mod** | -3 | +4 | +3 | +0 | +2 | +5 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 17
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +5, Wis +7
**Skills:** Perception +7, Stealth +9, Survival +7
**Damage Vulnerabilities:** necrotic
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; radiant
**Condition Immunities:** grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The breath drinker can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Radiant Absorption.** When the breath drinker is subjected to radiant damage, it takes no damage and instead regains a number of hit points equal to the radiant damage dealt.


---

### Actions

**Multiattack.** The breath drinker makes two Enervating Claw attacks. It can also use Drink Breath.

**Enervating Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. *Hit:* 12 (2d6 + 5) necrotic damage, and if the target is Large or smaller, it has the grappled condition (escape DC 18). The target must succeed on a DC 18 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Drink Breath.** The breath drinker targets a creature that has the incapacitated condition or that the breath drinker is grappling and that isn't a Construct or an Undead. The target must make a DC 18 Charisma saving throw. On a failed save, the target takes 36 (8d8) necrotic damage, and its Charisma score is reduced by 1d6. This reduction lasts until the target finishes a short or long rest. If this reduces the target's Charisma to 0, the target dies. Until the breath drinker dies, the dead target can't be returned to life by any means short of divine intervention. On a successful save, the target takes half as much necrotic damage only. On a successful or failed save, the breath drinker regains a number of hit points equal to the necrotic damage dealt.

**Invisibility.** The breath drinker has the invisible condition. This invisibility ends immediately after the breath drinker hits or misses with an attack roll or uses Drink Breath.


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