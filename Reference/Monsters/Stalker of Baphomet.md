---
type: pc
race: "Fiend (demon)"
class:
 - "Stalker of Baphomet"
subClass:
 - "CR 12"
cover: "Stalker of Baphomet.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/12
  - source/bgg
---
###### Stalker of Baphomet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Stalker of Baphomet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 17 | 22 | 13 | 16 | 12 |
| **Mod** | +7 | +3 | +6 | +1 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Abyssal, Giant
**Saving Throws:** Dex +7, Wis +7
**Skills:** Athletics +15, Perception +7, Stealth +11
**Condition Immunities:** charmed; frightened

---

### Traits

**Labyrinthine Recall.** The stalker can perfectly recall any path it has traveled.

**Magic Resistance.** The stalker has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The stalker makes two Glaive attacks or two Rock attacks.

**Glaive.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 18 (2d10 + 7) slashing damage plus 9 (2d8) force damage.

**Rock.** Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. *Hit:* 23 (3d10 + 7) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Strength saving throw or have the prone condition. After the stalker throws the rock, roll a d6; on a roll of 3 or lower, the stalker has no more rocks to throw.

**Erupting Horns (Recharge 5–6).** The stalker causes the earth to churn at a point on the ground it can see within 60 feet of itself. Six horn-shaped stones erupt in a 30-foot-radius, 30-foot-high cylinder centered on that point and then crumble to dust.
Each creature in that area must make a DC 15 Dexterity saving throw. On a failed save, a creature takes 33 (6d10) piercing damage and is pushed up to 30 feet upward and then falls. On a successful save, a creature takes half as much damage only.


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