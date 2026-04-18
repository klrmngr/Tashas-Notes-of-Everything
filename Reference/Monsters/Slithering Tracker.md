---
type: pc
race: "Ooze"
class:
 - "Slithering Tracker"
subClass:
 - "CR 3"
cover: "Slithering Tracker.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/3
  - source/mpmm
---
###### Slithering Tracker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Slithering Tracker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 15 | 10 | 14 | 11 |
| **Mod** | +3 | +4 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 12
**Languages:** understands languages it knew in its previous form but can't speak
**Skills:** Stealth +8, Survival +6
**Damage Vulnerabilities:** cold; fire
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; deafened; exhaustion; grappled; paralyzed; petrified; prone; restrained; unconscious

---

### Traits

**False Appearance.** If the slithering tracker is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the slithering tracker move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the slithering tracker isn't a puddle.

**Liquid Form.** The slithering tracker can enter an enemy's space and stop there. It can also move through a space as narrow as 1 inch wide without squeezing.

**Spider Climb.** The slithering tracker can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) bludgeoning damage.

**Life Leech.** One Large or smaller creature that the slithering tracker can see within 5 feet of it must succeed on a DC 13 Dexterity saving throw or be grappled (escape DC 13). Until this grapple ends, the target is restrained and unable to breathe unless it can breathe water. In addition, the grappled target takes 16 (3d10) necrotic damage at the start of each of its turns. The slithering tracker can grapple only one target at a time.
While grappling the target, the slithering tracker takes only half any damage dealt to it (rounded down), and the target takes the other half.


---

### Bonus Actions

**Watery Stealth.** If underwater, the slithering tracker takes the Hide action, and it makes the Dexterity (Stealth) check with advantage.


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