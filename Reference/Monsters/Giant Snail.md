---
type: pc
race: "Beast"
class:
 - "Giant Snail"
subClass:
 - "CR 1/4"
cover: "Giant Snail.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-4
  - source/wbtw
---
###### Giant Snail
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Giant Snail.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 22 (4d10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 3 | 11 | 3 | 10 | 3 |
| **Mod** | +2 | -4 | +0 | -4 | +0 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —

---

### Traits

**Salt Osmosis.** Whenever the snail starts its turn in contact with a pound or more of salt, it takes 1d4 necrotic damage. Using an action to sprinkle a pound of salt on the snail deals 1d4 necrotic damage to it immediately and another 1d4 necrotic damage to it at the start of its next turn (after which the salt rubs off), provided the snail has not withdrawn into its shell.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Shell Defense.** The snail withdraws into its shell, gaining a +4 bonus to its AC until it emerges. It can emerge from its shell as a bonus action on its turn.


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