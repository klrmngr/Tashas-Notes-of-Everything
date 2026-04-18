---
type: pc
race: "Dragon"
class:
 - "Drake Companion"
subClass:
 - "CR —"
cover: "Drake Companion.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/small
  - cr/—
  - source/ftd
---
###### Drake Companion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Drake Companion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Dragon |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC |  |
> | :FasHeart: HP | 5 + five times your ranger level (the drake has a number of Hit Dice [d10s] equal to your ranger level) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 15 | 8 | 14 | 8 |
| **Mod** | +3 | +1 | +2 | -1 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Draconic
**Saving Throws:** Dex +1 + PB, Wis +2 + PB

---

### Traits

**Draconic Essence.** When you summon the drake, choose a damage type: acid, cold, fire, lightning, or poison. The chosen type determines the drake's damage immunity and the damage of its Infused Strikes trait.


---

### Actions

**Bite.** Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. *Hit:* 1d6 plus PB piercing damage.


---

### Reactions

**Infused Strikes.** When another creature within 30 feet of the drake that it can see hits a target with a weapon attack, the drake infuses the strike with its essence, causing the target to take an extra 1d6 damage of the type determined by its Draconic Essence.


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