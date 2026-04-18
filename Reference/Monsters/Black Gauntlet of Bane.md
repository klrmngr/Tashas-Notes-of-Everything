---
type: pc
race: "Humanoid (human)"
class:
 - "Black Gauntlet of Bane"
subClass:
 - "CR 6"
cover: "Black Gauntlet of Bane.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/bgdia
---
###### Black Gauntlet of Bane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Black Gauntlet of Bane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 51 (6d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 18 | 12 | 15 | 18 |
| **Mod** | +4 | +0 | +4 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common
**Saving Throws:** Wis +5
**Skills:** Intimidation +7, Perception +5
**Condition Immunities:** frightened

---

### Traits

**Aura of Terror.** When a hostile creature within 5 feet of the black gauntlet makes an attack roll or a saving throw, it has disadvantage on the roll. Creatures that are immune to the frightened condition are immune to this trait.

**Tactical Discipline.** The black gauntlet has advantage on all ability checks and saving throws made during combat.


---

### Actions

**Multiattack.** The black gauntlet makes two attacks with its mace.

**Mace.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage plus 13 (3d8) necrotic damage.

**Guiding Bolt (1st-Level Spell; Requires a Spell Slot).** Ranged Spell Attack: +7 to hit, range 120 ft., one creature. *Hit:* 14 (4d6) radiant damage, and the next attack roll made against the target before the end of the black gauntlet's next turn has advantage. If the black gauntlet casts this spell using a spell slot of 2nd level or higher, the damage increases by 1d6 for each slot level above 1st.


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