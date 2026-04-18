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
  - source/vgm
---
###### Slithering Tracker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
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
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 15 | 10 | 14 | 11 |
| **Mod** | +3 | +4 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 12
**Languages:** understands languages it knew in its previous form but can't speak
**Skills:** Stealth +8
**Damage Vulnerabilities:** cold; fire
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; deafened; exhaustion; grappled; paralyzed; petrified; prone; restrained; unconscious

---

### Traits

**Ambusher.** In the first round of a combat, the slithering tracker has advantage on attack rolls against any creature it surprised.

**Damage Transfer.** While grappling a creature, the slithering tracker takes only haIf the damage dealt to it, and the creature it is grappling takes the other half.

**False Appearance.** While the slithering tracker remains motionless, it is indistinguishable from a puddle, unless an observer succeeds on a DC 18 Intelligence (Investigation) check.

**Keen Tracker.** The slithering tracker has advantage on Wisdom checks to track prey.

**Liquid Form.** The slithering tracker can enter an enemy's space and stop there. It can also move through a space as narrow as 1 inch wide without squeezing.

**Spider Climb.** The slithering tracker can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Watery Stealth.** While underwater, the slithering tracker has advantage on Dexterity (Stealth) checks made to hide, and it can take the Hide action as a bonus action.


---

### Actions

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) bludgeoning damage.

**Life Leech.** One Large or smaller creature that the slithering tracker can see within 5 feet of it must succeed on a DC 13 Dexterity saving throw or be grappled (escape DC 13). Until this grapple ends, the target is restrained and unable to breathe unless it can breathe water. In addition, the grappled target takes 16 (3d10) necrotic damage at the start of each of its turns. The slithering tracker can grapple only one target at a time.


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