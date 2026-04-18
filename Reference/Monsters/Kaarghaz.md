---
type: pc
race: "Humanoid (troglodyte)"
class:
 - "Kaarghaz"
subClass:
 - "CR 2"
cover: "Kaarghaz.png"
campaign:
locations:
tags:
  - race/troglodyte
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/tftyp
---
###### Kaarghaz
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Kaarghaz.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (troglodyte) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (troglodyte) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 6 | 10 | 15 |
| **Mod** | +2 | +0 | +2 | -2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Draconic, Troglodyte
**Skills:** Stealth +2

---

### Traits

**Chameleon Skin.** The troglodyte has advantage on Dexterity (Stealth) checks made to hide.

**Stench.** Any creature other than a troglodyte that starts its turn within 5 feet of the troglodyte must succeed on a DC 12 Constitution saving throw or be poisoned until the start of the creature's next turn. On a successful saving throw, the creature is immune to the stench of all troglodytes for 1 hour.

**Sunlight Sensitivity.** While in sunlight, the troglodyte has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The troglodyte makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.


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