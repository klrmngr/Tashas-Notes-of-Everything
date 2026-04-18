---
type: pc
race: "Fiend"
class:
 - "Slayer"
subClass:
 - "CR 12"
cover: "Slayer.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/coa
---
###### Slayer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Slayer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 19 | 18 | 13 | 14 | 14 |
| **Mod** | +5 | +4 | +4 | +1 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Languages of the host
**Saving Throws:** Dex +8, Int +5
**Skills:** Acrobatics +8, Deception +6, Perception +6, Stealth +12
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison

---

### Traits

**Assassinate.** During its first turn, the Slayer has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the Slayer scores against a surprised creature is a critical hit.

**Devil's Sight.** Magical darkness doesn't impede the Slayer's darkvision.

**Magic Resistance.** The Slayer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The Slayer makes four Claw attacks.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 7 (2d6) poison damage. The Slayer deals an extra 14 (4d6) slashing damage when it has advantage on the attack roll and hits the target.


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