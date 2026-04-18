---
type: pc
race: "Humanoid (changeling, shapechanger)"
class:
 - "Changeling"
subClass:
 - "CR 1/2"
cover: "Changeling.png"
campaign:
locations:
tags:
  - race/changeling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/erlw
---
###### Changeling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Changeling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (changeling, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (changeling, shapechanger) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 15 | 12 | 14 | 10 | 16 |
| **Mod** | -1 | +2 | +1 | +2 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish, Elvish, Halfling, Thieves' cant
**Skills:** Acrobatics +4, Deception +5, Insight +2, Perception +2, Persuasion +5

---

### Traits

**Change Appearance.** The changeling can use its action to polymorph into a Medium humanoid it has seen, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


---

### Actions

**Multiattack.** The changeling makes two attacks with its dagger.

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Unsettling Visage (Recharges after a Short or Long Rest).** Each creature within 30 feet of the changeling must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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