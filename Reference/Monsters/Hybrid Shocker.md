---
type: pc
race: "Humanoid (simic hybrid)"
class:
 - "Hybrid Shocker"
subClass:
 - "CR 1"
cover: "Hybrid Shocker.png"
campaign:
locations:
tags:
  - race/simic hybrid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/ggr
---
###### Hybrid Shocker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Hybrid Shocker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (simic hybrid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (simic hybrid) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 14 | 10 | 12 | 9 |
| **Mod** | +1 | +2 | +2 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any one language
**Damage Immunities:** lightning

---

### Traits

**Electrified Body.** Any creature that touches the hybrid or hits it with a melee attack while within 5 feet of it takes 5 (1d10) lightning damage.

**Illumination.** The hybrid sheds bright light in a 10-foot radius and dim light for an additional 10 feet.


---

### Actions

**Multiattack.** The hybrid makes two attacks: one with its shocking touch and one with its tentacles.

**Shocking Touch.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d8) lightning damage.

**Tentacles.** Melee Weapon Attack: +4 to hit, reach 15 ft., one creature. *Hit:* The target is grappled (escape DC 11), and the hybrid pulls the target up to 15 feet straight toward it. Until this grapple ends, the target takes 5 (1d10) lightning damage at the start of each of its turns, and the hybrid shocker can't use its tentacles on another creature.


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