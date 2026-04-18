---
type: pc
race: "Humanoid"
class:
 - "Doomguard Rot Blade"
subClass:
 - "CR 6"
cover: "Doomguard Rot Blade.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/mpp
---
###### Doomguard Rot Blade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Doomguard Rot Blade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 97 (13d8 + 39) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 12 | 10 | 15 |
| **Mod** | +4 | +1 | +3 | +1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common plus two more languages
**Saving Throws:** Str +7, Con +6
**Skills:** Perception +3
**Damage Resistances:** necrotic

---

### Actions

**Multiattack.** The rot blade makes two Entropic Blade or Entropic Javelin attacks.

**Entropic Blade.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage plus 7 (2d6) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash. The rot blade can cause the blade to emit a burst of entropic magic in a 10-foot-radius sphere centered on the weapon. Each creature in that area other than the rot blade must succeed on a DC 13 Constitution saving throw or take 6 (1d12) necrotic damage. The blade can emit entropic magic in this way only once per turn.

**Entropic Javelin.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 13 (2d12) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash.


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