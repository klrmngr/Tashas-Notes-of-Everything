---
type: pc
race: "Celestial"
class:
 - "Anagwendol"
subClass:
 - "CR 16"
cover: "Anagwendol.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/16
  - source/coa
---
###### Anagwendol
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Anagwendol.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 190 (20d8 + 100) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 18 | 20 | 18 | 20 | 22 |
| **Mod** | +5 | +4 | +5 | +4 | +5 | +6 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +9, Wis +10, Cha +11
**Skills:** Perception +10
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Magic Resistance.** Anagwendol has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Anagwendol makes two attacks using her Defending Greatsword, Longbow, or a combination of the two.

**Defending Greatsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 19 (4d6 + 5) slashing damage plus 22 (5d8) radiant damage.

**Longbow.** Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage damage plus 22 (5d8) radiant damage.

**Healing Touch (2/Day).** Anagwendol touches another creature. The target magically regains 30 (6d8 + 3) hit points and is freed from any curse, disease, poison, blindness, or deafness.


---

### Bonus Actions

**Defensive Sword-work.** Anagwendol can forgo attacking with her Defending Greatsword on this turn and gain a +3 to her armor class. She can still attack with her Longbow.


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