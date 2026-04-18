---
type: pc
race: "Construct"
class:
 - "Gold-Forged Sentinel"
subClass:
 - "CR 5"
cover: "Gold-Forged Sentinel.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/5
  - source/mot
---
###### Gold-Forged Sentinel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Gold-Forged Sentinel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 76 (8d10 + 32) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 19 | 3 | 16 | 10 |
| **Mod** | +4 | +1 | +4 | -4 | +3 | +0 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** understands one language of its creator but can't speak
**Skills:** Perception +6
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Charge.** If the sentinel moves at least 20 feet straight toward a target and then hits it with a ram attack on the same turn, the target takes an extra 10 (3d6) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Spell Turning.** The sentinel has advantage on saving throws against any spell that targets only the sentinel (not an area). If the sentinel's saving throw succeeds and the spell is of 4th level or lower, the spell has no effect on the sentinel and instead targets the caster.


---

### Actions

**Multiattack.** The sentinel makes two ram attacks.

**Ram.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.

**Fire Breath (Recharge 5–6).** The sentinel exhales fire in a 15-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 27 (6d8) fire damage on a failed save, or half as much damage on a successful one.


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