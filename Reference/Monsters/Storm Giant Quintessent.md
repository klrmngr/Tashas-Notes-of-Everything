---
type: pc
race: "Giant"
class:
 - "Storm Giant Quintessent"
subClass:
 - "CR 16"
cover: "Storm Giant Quintessent.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/16
  - source/mpmm
---
###### Storm Giant Quintessent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Storm Giant Quintessent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 17 | 20 | 19 |
| **Mod** | +9 | +2 | +5 | +3 | +5 | +4 |

**Speed:** 50 ft., fly 50 ft. ((hover)), swim 50 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 20
**Languages:** Common, Giant
**Saving Throws:** Str +14, Con +10, Wis +10, Cha +9
**Skills:** Arcana +8, History +8, Perception +10
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; thunder

---

### Traits

**Amphibious.** The giant can breathe air and water.

**Legendary Resistance (1/Day).** If the giant fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The giant makes two Lightning Sword attacks, or it uses Wind Javelin twice.

**Lightning Sword.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 40 (9d6 + 9) lightning damage.

**Wind Javelin.** The giant coalesces wind into a javelin-like form and hurls it at a creature it can see within 600 feet of it. The javelin deals 19 (3d6 + 9) force damage to the target, striking unerringly. The javelin disappears after it hits.


---

### Legendary Actions

### 

**Gust.** The giant targets a creature it can see within 60 feet of it and creates a magical gust of wind around the target, who must succeed on a DC 18 Strength saving throw or be moved up to 20 feet in any horizontal direction the giant chooses.

**Thunderbolt (Costs 2 Actions).** The giant hurls a thunderbolt at a creature it can see within 600 feet of it. The target must make a DC 18 Dexterity saving throw, taking 22 (4d10) thunder damage on a failed save, or half as much damage on a successful one.

**One with the Storm (Costs 3 Actions).** The giant vanishes, dispersing itself into the storm surrounding its lair. The giant can end this effect at the start of any of its turns, becoming a giant once more and appearing in any location it chooses within its lair. While dispersed, the giant can't take any actions other than lair actions, and it can't be targeted by attacks, spells, or other effects. The giant can't use this ability outside its lair, nor can it use this ability if another creature is using a control weather spell or similar magic to quell the storm.


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