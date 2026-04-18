---
type: pc
race: "Elemental"
class:
 - "Murder Comet"
subClass:
 - "CR 5"
cover: "Murder Comet.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/5
  - source/bam
---
###### Murder Comet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Murder Comet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 66 (7d8 + 35) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 20 | 6 | 10 | 6 |
| **Mod** | +2 | +2 | +5 | -2 | +0 | -2 |

**Speed:** 0 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 10
**Languages:** Ignan, Terran
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; prone; unconscious

---

### Traits

**Explode.** When the comet drops to 0 hit points, it explodes in a 20-foot-radius sphere centered on itself. Each creature in the sphere must make a DC 16 Dexterity saving throw, taking 28 (8d6) fire damage on a failed save, or half as much damage on a successful one.

**Flyby.** The comet doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Illumination.** The comet sheds bright light in a 30-foot radius and dim light for an additional 30 feet.

**Siege Monster.** The comet deals double damage to objects and structures.

**Unusual Nature.** The comet doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The comet makes one Slam attack and one Spit Fire attack.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage plus 7 (2d6) fire damage.

**Spit Fire.** Ranged Weapon Attack: +5 to hit, range 60 ft., one target. *Hit:* 13 (2d10 + 2) fire damage.


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