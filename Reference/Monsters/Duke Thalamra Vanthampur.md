---
type: pc
race: "Humanoid (human)"
class:
 - "Duke Thalamra Vanthampur"
subClass:
 - "CR 4"
cover: "Duke Thalamra Vanthampur.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/bgdia
---
###### Duke Thalamra Vanthampur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Duke Thalamra Vanthampur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 13 | 16 | 18 |
| **Mod** | +3 | +0 | +2 | +1 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft. (see devil's sight below), passive Perception 13
**Languages:** Common, Infernal
**Skills:** Deception +6, Insight +5, Intimidation +6, Religion +3

---

### Traits

**Dark Devotion.** Thalamra has advantage on saving throws against being charmed or frightened.

**Devil's Sight.** Thalamra can see normally in darkness, both magical and nonmagical, out to a distance of 120 feet.


---

### Actions

**Multiattack.** Thalamra uses eldritch blast twice or makes two unarmed strikes.

**Eldritch Blast (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 9 (1d10 + 4) force damage.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 bludgeoning damage.


---

### Reactions

**Hellish Rebuke (1st-Level Spell; 2/Day).** When Thalamra is damaged by a creature within 60 feet of her that she can see, the creature that damaged her is engulfed in hellish flames and must make a DC 14 Dexterity saving throw, taking 16 (3d10) fire damage on a failed save, or half as much damage on a successful one.


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