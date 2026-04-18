---
type: pc
race: "Monstrosity"
class:
 - "Torogar Steelfist"
subClass:
 - "CR 11"
cover: "Torogar Steelfist.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/11
  - source/bgdia
---
###### Torogar Steelfist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Torogar Steelfist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 168 (16d10 + 80) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 17 | 20 | 8 | 9 | 16 |
| **Mod** | +7 | +3 | +5 | -1 | -1 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Abyssal, Common
**Saving Throws:** Str +11, Con +9

---

### Traits

**Goring Rush.** Immediately after using the Dash action, Torogar can make one melee attack with his horns.

**Labyrinthine Recall.** Torogar can perfectly recall any path he has traveled.

**Rage (Recharges after a Short or Long Rest).** As a bonus action, Torogar can enter a rage that lasts for 1 minute. The rage ends early if Torogar is knocked unconscious or if his turn ends and he hasn't attacked a hostile creature or taken damage since his last turn. While raging, Torogar gains the following benefits:
He has advantage on Strength checks and Strength saving throws.
He deals an extra 3 damage when he hits a target with a melee weapon attack.
He has resistance to bludgeoning, piercing, and slashing damage.

**Special Equipment.** Torogar wears gauntlets of flaming fury and a belt of fire giant strength. Without the belt, his Strength is 21. He also carries a soul coin.


---

### Actions

**Multiattack.** Torogar makes three attacks: two with his scimitars and one with his horns.

**Scimitar.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage, or 17 (2d6 + 10) slashing damage while raging, plus 3 (1d6) fire damage from the gauntlets of flaming fury.

**Horns.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) piercing damage, or 19 (2d8 + 10) piercing damage while raging.


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