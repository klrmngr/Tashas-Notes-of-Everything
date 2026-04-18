---
type: pc
race: "Humanoid"
class:
 - "Tortle Druid"
subClass:
 - "CR 2"
cover: "Tortle Druid.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mpmm
---
###### Tortle Druid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Tortle Druid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 12 | 11 | 15 | 12 |
| **Mod** | +2 | +0 | +1 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Aquan, Common
**Skills:** Animal Handling +4, Nature +2, Survival +4

---

### Traits

**Hold Breath.** The tortle can hold its breath for 1 hour.


---

### Actions

**Multiattack.** The tortle makes four Claw attacks or two Nature's Wrath attacks.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Nature's Wrath.** Ranged Spell Attack: +4 to hit, range 90 ft., one target. *Hit:* 9 (2d6 + 2) damage of a type chosen by the tortle: cold, fire, lightning, or thunder.

**Shell Defense.** The tortle withdraws into its shell. Until it emerges, it gains a +4 bonus to AC and has advantage on Strength and Constitution saving throws. While in its shell, the tortle is prone, its speed is 0 and can't increase, it has disadvantage on Dexterity saving throws, it can't take reactions, and the only action it can take is a bonus action to emerge.


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