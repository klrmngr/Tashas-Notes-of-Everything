---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Ram Sugar"
subClass:
 - "CR 2"
cover: "Ram Sugar.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/cm
---
###### Ram Sugar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Ram Sugar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 10 | 13 | 14 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic
**Skills:** Deception +4, Persuasion +4, Religion +2
**Damage Resistances:** fire

---

### Traits

**Dark Devotion.** Ram Sugar has advantage on saving throws against being charmed or frightened.


---

### Actions

**Multiattack.** Ram Sugar makes two melee attacks.

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage.

**Breath Weapon (Recharges after a Short or Long Rest).** Ram Sugar exhales fire in a 30-foot-long line that is 5 feet wide. Any creature in the line must make a DC 11 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half as much damage on a successful one.


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