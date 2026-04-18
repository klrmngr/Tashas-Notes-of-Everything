---
type: pc
race: "Undead"
class:
 - "Gloamwing"
subClass:
 - "CR 8"
cover: "Gloamwing.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/8
  - source/ggr
---
###### Gloamwing
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Gloamwing.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 17 | 2 | 11 | 6 |
| **Mod** | +5 | +3 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** understands Common
**Saving Throws:** Str +8, Dex +6
**Skills:** Perception +3, Stealth +6
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Death Link.** If its specter rider is reduced to 0 hit points, the gloamwing is destroyed.

**Flyby.** The gloamwing doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Sunlight Sensitivity.** While in sunlight, the gloamwing has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The gloamwing makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 18 (3d8 + 5) piercing damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage.


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