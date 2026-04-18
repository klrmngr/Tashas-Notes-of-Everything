---
type: pc
race: "Undead"
class:
 - "Nafik"
subClass:
 - "CR 6"
cover: "Nafik.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/qftis
---
###### Nafik
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Nafik.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 16 | 10 | 16 | 14 |
| **Mod** | +4 | +0 | +3 | +0 | +3 | +2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Saving Throws:** Int +3, Wis +6
**Skills:** History +3, Religion +3
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (2/Day).** If Nafik fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Nafik has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** When he is destroyed, Nafik gains a new body in 24 hours if his heart is intact, regaining all his hit points. The new body appears in an unoccupied space within 5 feet of Nafik's heart.


---

### Actions

**Multiattack.** Nafik can use his Dreadful Glare and makes one Rotting Fist or Unholy Beam attack.

**Rotting Fist.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies and its body turns to dust. The curse lasts until removed by the Remove Curse spell or other magic.

**Unholy Beam.** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 28 (8d6) necrotic damage, and the next attack roll made against this target before the end of Nafik's next turn has advantage.

**Dreadful Glare.** Nafik targets one creature he can see within 60 feet of himself. The target must succeed on a DC 14 Wisdom saving throw or have the frightened condition until the end of Nafik's next turn. A target that succeeds on the saving throw is immune to Nafik's Dreadful Glare for the next 24 hours.


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