---
type: pc
race: "Humanoid (goliath)"
class:
 - "Goliath Warrior"
subClass:
 - "CR 3"
cover: "Goliath Warrior.png"
campaign:
locations:
tags:
  - race/goliath
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/idrotf
---
###### Goliath Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Goliath Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goliath) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 (hide armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (goliath) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 10 | 15 | 10 |
| **Mod** | +4 | +0 | +3 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Giant
**Skills:** Athletics +6, Perception +4, Survival +4
**Damage Resistances:** cold

---

### Traits

**Mountain Born.** The goliath is acclimated to high altitude, including elevations above 20,000 feet.

**Powerful Build.** The goliath counts as one size larger when determining its carrying capacity and the weight it can push, drag, or lift.


---

### Actions

**Multiattack.** The goliath makes two attacks with its greataxe or hurls two javelins.

**Greataxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


---

### Reactions

**Stone's Endurance (Recharges after a Short or Long Rest).** When the goliath takes damage, it reduces the damage taken by 9 (1d12 + 3).


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