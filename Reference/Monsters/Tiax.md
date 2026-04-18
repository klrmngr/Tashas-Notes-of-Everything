---
type: pc
race: "Humanoid"
class:
 - "Tiax"
subClass:
 - "CR 9"
cover: "Tiax.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/9
  - source/coa
---
###### Tiax
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Tiax.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 110 (20d6 + 40) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 15 | 19 | 18 |
| **Mod** | +0 | +3 | +2 | +2 | +4 | +4 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Celestial, Common, Gnomish
**Saving Throws:** Wis +8, Cha +8
**Skills:** Deception +8, Insight +8, Performance +8, Persuasion +8

---

### Traits

**Gnome Cunning.** Tiax has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.

**Special Equipment.** Tiax wears a Ring of Resistance that grants him resistance to radiant damage.


---

### Actions

**Touch of Decay.** Melee Spell Attack: +8 to hit, reach 5 ft., one target. *Hit:* 37 (6d10 + 4) necrotic damage.

**Unholy Firebolt.** Tiax causes unholy fire to flare up in a creature's space within 60 feet of him. The target must succeed on a DC 16 Dexterity saving throw or take 18 (4d8) necrotic damage plus 18 (4d8) poison damage.


---

### Bonus Actions

**Heal (2/Day).** Tiax heals 70 hit points.


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