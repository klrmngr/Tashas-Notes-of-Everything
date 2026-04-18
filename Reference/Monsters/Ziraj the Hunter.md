---
type: pc
race: "Humanoid (half-orc)"
class:
 - "Ziraj the Hunter"
subClass:
 - "CR 8"
cover: "Ziraj the Hunter.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/wdh
---
###### Ziraj the Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Ziraj the Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (+2 leather armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (half-orc) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 11 | 14 | 15 |
| **Mod** | +4 | +4 | +4 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Orc
**Saving Throws:** Wis +5, Cha +5
**Skills:** Athletics +7, Intimidation +5, Stealth +7, Survival +5

---

### Actions

**Multiattack.** Ziraj makes three attacks with his glaive or with his oversized longbow.

**Glaive.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage.

**Oversized Longbow.** Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Dreadful Aspect (Recharges after a Short or Long Rest).** Ziraj exudes magical menace. Each enemy within 30 feet of him must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute of Ziraj. If a frightened enemy ends its turn more than 30 feet away from Ziraj, the enemy can repeat the saving throw, ending the effect on itself on a success.


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