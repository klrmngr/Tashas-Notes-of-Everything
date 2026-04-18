---
type: pc
race: "Monstrosity"
class:
 - "Draconian Mage"
subClass:
 - "CR 2"
cover: "Draconian Mage.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/ftd
---
###### Draconian Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconian Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 11 | 11 | 10 | 14 |
| **Mod** | +2 | +0 | +0 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Int +2, Wis +2, Cha +4

---

### Traits

**Death Throes.** When the draconian is reduced to 0 hit points, its scales and flesh immediately shrivel away and its bones explode. Each creature within 10 feet of it must succeed on a DC 10 Dexterity saving throw or take 9 (2d8) force damage.

**Glide.** When the draconian falls and isn't incapacitated, it subtracts up to 100 feet from the fall when calculating the fall's damage, and it can move up to 2 feet horizontally for every 1 foot it descends.


---

### Actions

**Multiattack.** The draconian makes two Trident or Necrotic Ray attacks.

**Trident.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.

**Necrotic Ray.** Ranged Spell Attack: +4 to hit, range 60 ft., one target. *Hit:* 10 (3d6) necrotic damage.


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