---
type: pc
race: "Elemental"
class:
 - "Lightning Hulk"
subClass:
 - "CR 9"
cover: "Lightning Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/9
  - source/bgg
---
###### Lightning Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Lightning Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 102 (12d10 + 36) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 21 | 16 | 14 | 14 | 15 |
| **Mod** | +4 | +5 | +3 | +2 | +2 | +2 |

**Speed:** 0 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Auran, Giant
**Saving Throws:** Dex +9, Con +7, Wis +6, Cha +6
**Skills:** Perception +6
**Damage Resistances:** cold; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Illumination.** The lightning hulk sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

**Lightning Form.** The lightning hulk can enter a hostile creature's space and stop there. The first time the lightning hulk enters a creature's space on a turn, or if it begins its turn in a creature's space, that creature takes 7 (2d6) lightning damage. The hulk can also move through a space as narrow as 1 inch without squeezing. A creature that touches the lightning hulk or hits it with a melee attack while within 5 feet of it takes 7 (2d6) lightning damage.


---

### Actions

**Arc Lightning.** Melee or Ranged Weapon Attack: +9 to hit, reach 10 ft. or range 60 ft., one target. *Hit:* 18 (4d8) lightning damage. If the target is a creature, it can't take reactions until the start of its next turn, and lightning jumps from the target to another creature of the lightning hulk's choice that it can see within 30 feet of the target. The second creature must succeed on a DC 18 Dexterity saving throw or take 18 (4d8) lightning damage.


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