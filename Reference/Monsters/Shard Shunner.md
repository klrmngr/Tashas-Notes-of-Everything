---
type: pc
race: "Humanoid (halfling, shapechanger)"
class:
 - "Shard Shunner"
subClass:
 - "CR 2"
cover: "Shard Shunner.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/wdh
---
###### Shard Shunner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Shard Shunner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling, shapechanger) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Humanoid (halfling, shapechanger) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 11 | 10 | 8 |
| **Mod** | +0 | +2 | +1 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft. (rat form only), passive Perception 12
**Languages:** Common, Halfling, Thieves' cant
**Skills:** Perception +2, Stealth +4
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered

---

### Traits

**Shapechanger.** The Shard Shunner can use their action to polymorph into a rat-humanoid hybrid or into a giant rat, or back into their true form, which is humanoid. Their statistics, other than their size, are the same in each form. Any equipment they are wearing or carrying isn't transformed. They revert to their true form if they die.

**Keen Smell.** The Shard Shunner has advantage on Wisdom (Perception) checks that rely on smell.

**Halfling Nimbleness.** The Shard Shunner can move through the space of creatures that is of a size larger than them.

**Brave.** The Shard Shunner has advantage on saving throws against being frightened.


---

### Actions

**Multiattack (Humanoid or Hybrid Form Only).** The Shard Shunner makes two attacks, only one of which can be a bite.

**Bite (Rat or Hybrid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy.

**Shortsword (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Hand Crossbow (Humanoid or Hybrid Form Only).** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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