---
type: pc
race: "Humanoid (half-orc, shapechanger)"
class:
 - "Anchorite of Talos"
subClass:
 - "CR 3"
cover: "Anchorite of Talos.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/dip
---
###### Anchorite of Talos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DIP
___

> [!infobox|no-t right]
> ![[Anchorite of Talos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (half-orc, shapechanger) |
> | :FasBook: Source | DIP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 9 | 15 | 12 |
| **Mod** | +3 | +1 | +2 | -1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Orc
**Skills:** Nature +1, Stealth +3, Survival +4

---

### Traits

**Shapechanger.** The anchorite can use its action to polymorph into a boar or back into its true form, which is humanoid. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


---

### Actions

**Clawed Gauntlet (Humanoid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) slashing damage.

**Tusk (Boar Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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