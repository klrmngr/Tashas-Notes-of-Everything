---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Donaar Blit'zen"
subClass:
 - "CR 3"
cover: "Donaar Blit'zen.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/ai
---
###### Donaar Blit'zen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Donaar Blit'zen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 8 | 14 | 10 | 10 | 16 |
| **Mod** | +3 | -1 | +2 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic, Orc
**Saving Throws:** Wis +2, Cha +5
**Skills:** History +2, Insight +2, Intimidation +5, Persuasion +5
**Damage Resistances:** acid

---

### Traits

**Champion Challenge (Recharges after a Short or Long Rest).** As a bonus action, Donaar causes each creature of his choice that he can see within 30 feet of him to make a DC 13 Wisdom saving throw. On a failure, a creature can't willingly move more than 30 feet away from Donaar. This effect ends on the creature if Donaar is incapacitated or dies, or if the creature is moved more than 30 feet away from him.


---

### Actions

**Multiattack.** Donaar makes two attacks with his greatsword or his whip.

**Greatsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage. Whenever Donaar rolls a 1 or 2 on a damage die, he can reroll the die and must use the new roll.

**Whip.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 5 (1d4 + 3) slashing damage.

**Acid Vomit.** Donaar regurgitates acid in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 12 Dexterity saving throw, taking 7 (2d6) acid damage on a failed save, or half as much damage on a successful one.


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