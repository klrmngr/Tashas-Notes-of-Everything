---
type: pc
race: "Humanoid (goliath)"
class:
 - "Sken Zabriss"
subClass:
 - "CR 1"
cover: "Sken Zabriss.png"
campaign:
locations:
tags:
  - race/goliath
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/egw
---
###### Sken Zabriss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Sken Zabriss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goliath) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (breastplate, shield) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (goliath) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 15 | 13 | 10 | 12 |
| **Mod** | +3 | +0 | +2 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic, Giant

---

### Traits

**Powerful Build.** Sken counts as one size larger when determining her carrying capacity and the weight she can push, drag, or lift.

**Special Equipment.** Sken wears a ring of obscuring. With it, she can cast the fog cloud spell centered on herself three times per day. The cloud lasts for 1 minute (no concentration required).


---

### Actions

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage when used with two hands.


---

### Reactions

**Stone's Endurance (Recharges after a Short or Long Rest).** When Sken takes damage, she can use her reaction to reduce the damage taken by 8 (1d12 + 2).


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