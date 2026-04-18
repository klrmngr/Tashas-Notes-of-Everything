---
type: pc
race: "Humanoid (troglodyte)"
class:
 - "Troglodyte Champion of Laogzed"
subClass:
 - "CR 3"
cover: "Troglodyte Champion of Laogzed.png"
campaign:
locations:
tags:
  - race/troglodyte
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/oota
---
###### Troglodyte Champion of Laogzed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Troglodyte Champion of Laogzed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (troglodyte) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 59 (7d8 + 28) |
> | :FasUserGroup: Race | Humanoid (troglodyte) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 18 | 8 | 12 | 12 |
| **Mod** | +4 | +1 | +4 | -1 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Troglodyte
**Skills:** Athletics +6, Intimidation +3, Stealth +3

---

### Traits

**Chameleon Skin.** The troglodyte has advantage on Dexterity (Stealth) checks made to hide.

**Stench.** Any creature other than a troglodyte that starts its turn within 5 feet of the troglodyte must succeed on a DC 14 Constitution saving throw or be poisoned until the start of the creature's next turn. On a successful saving throw, the creature is immune to the stench of all troglodytes for 1 hour.

**Sunlight Sensitivity.** While in sunlight, the troglodyte has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The troglodyte makes three attacks: one with its bite and two with either its claws or its greatclub.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage.

**Greatclub.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage.

**Acid Spray (Recharge 6).** The troglodyte spits acid in a line 15 feet long and 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw, taking 10 (3d6) acid damage on a failed save, or half as much damage on a successful one.


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