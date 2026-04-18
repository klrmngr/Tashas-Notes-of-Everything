---
type: pc
race: "Monstrosity"
class:
 - "Kruthik Hive Lord"
subClass:
 - "CR 5"
cover: "Kruthik Hive Lord.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/mpmm
---
###### Kruthik Hive Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Kruthik Hive Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 102 (12d10 + 36) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 10 | 14 | 10 |
| **Mod** | +4 | +3 | +3 | +0 | +2 | +0 |

**Speed:** 40 ft., burrow 20 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 18
**Languages:** Kruthik
**Skills:** Perception +8

---

### Traits

**Pack Tactics.** The kruthik has advantage on an attack roll against a creature if at least one of the kruthik's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Tunneler.** The kruthik can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The kruthik makes two Stab or Spike attacks.

**Stab.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage.

**Spike.** Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Acid Spray (Recharge 5–6).** The kruthik sprays acid in a 15-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw, taking 22 (4d10) acid damage on a failed save, or half as much damage on a successful one.


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