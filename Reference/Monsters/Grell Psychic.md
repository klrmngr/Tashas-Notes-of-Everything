---
type: pc
race: "Aberration"
class:
 - "Grell Psychic"
subClass:
 - "CR 4"
cover: "Grell Psychic.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/4
  - source/pabtso
---
###### Grell Psychic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Grell Psychic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 13 | 12 | 11 | 14 |
| **Mod** | +3 | +2 | +1 | +1 | +0 | +2 |

**Speed:** 10 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 14
**Languages:** Deep Speech, Grell
**Skills:** Perception +4, Stealth +6
**Damage Immunities:** lightning
**Condition Immunities:** blinded; prone

---

### Actions

**Multiattack.** The grell psychic makes one Tentacle attack and one Beak attack.

**Beak.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (3d4 + 3) piercing damage.

**Tentacle.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or have the poisoned condition for 1 minute. While the target is poisoned, it also has the paralyzed condition. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The target also has the grappled condition (escape DC 16). While grappling the target, the grell can't make Tentacle attacks against other targets. When the grell moves, any Medium or smaller target it is grappling moves with it.


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