---
type: pc
race: "Construct"
class:
 - "Combat Robot"
subClass:
 - "CR 6"
cover: "Combat Robot.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/6
  - source/qftis
---
###### Combat Robot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Combat Robot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 17 | 10 | 15 | 10 |
| **Mod** | +5 | +2 | +3 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Common plus the languages spoken by its creator
**Saving Throws:** Con +6, Cha +3
**Skills:** Athletics +8, Intimidation +6, Perception +5
**Damage Resistances:** acid; fire
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Lightning Overload.** When the robot takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the stunned condition until the start of its next turn.


---

### Actions

**Multiattack.** The robot makes two Tentacle attacks or three Laser Beam attacks.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 16). While grappled, the target also has the restrained condition. The robot has two tentacles, each of which can grapple one target.

**Laser Beam.** Ranged Weapon Attack: +5 to hit, range 120 ft., one target. *Hit:* 16 (4d6 + 2) radiant damage.

**Grenade Launcher (Recharge 5–6).** The robot fires a grenade at a point it can see within 120 feet of itself. The grenade explodes in a 20-foot-radius sphere centered on that point, creating one of the following effects (robot's choice):
- **Concussion Grenade.** Each creature in the sphere must make a DC 15 Dexterity saving throw, taking 21 (6d6) force damage on a failed save or half as much damage on a successful one.
- **Sleep Grenade.** Each creature in the sphere must succeed on a DC 15 Constitution saving throw or have the unconscious condition for 1 hour. The condition ends on a creature early if the creature takes damage or if another creature uses an action to shake it awake.


---

### Bonus Actions

**Emergency Speed (2/Day).** The robot takes the Dash or Disengage action.


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