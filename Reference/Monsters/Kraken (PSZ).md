---
type: pc
race: "Monstrosity"
class:
 - "Kraken"
subClass:
 - "CR 13"
cover: "Kraken.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/13
  - source/psz
---
###### Kraken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSZ
___

> [!infobox|no-t right]
> ![[Kraken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSZ |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 16 | 18 | 18 |
| **Mod** | +9 | +2 | +5 | +3 | +4 | +4 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** Common
**Skills:** Athletics +14, Perception +9
**Damage Resistances:** cold
**Damage Immunities:** lightning; thunder

---

### Traits

**Amphibious.** The kraken can breathe air and water.


---

### Actions

**Multiattack.** The kraken makes two attacks: one with its claw and one with its tentacles.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 30 (6d6 + 9) slashing damage.

**Tentacles.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 30 (6d6 + 9) bludgeoning damage, and the target is grappled (escape DC 17). Until this grapple ends, the target is restrained.

**Lightning Strike (Recharge 5–6).** The kraken hurls a magical lightning bolt at a point it can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed save, or half as much damage on a successful one.


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