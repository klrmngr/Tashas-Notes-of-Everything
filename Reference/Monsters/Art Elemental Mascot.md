---
type: pc
race: "Elemental"
class:
 - "Art Elemental Mascot"
subClass:
 - "CR 1/4"
cover: "Art Elemental Mascot.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-4
  - source/scc
---
###### Art Elemental Mascot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Art Elemental Mascot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 13 | 12 | 8 | 11 | 15 |
| **Mod** | -2 | +1 | +1 | -1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Skills:** Performance +4
**Damage Resistances:** cold; fire
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Death Burst.** When the elemental dies, it explodes in a burst of colored light. Each creature within 5 feet of the elemental must succeed on a DC 11 Constitution saving throw or be blinded for 1 minute. A blinded creature can repeat the save at the end of each of its turns, ending the effect on itself on a success.


---

### Actions

**Joyful Flare.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) fire damage.

**Melancholic Bolt.** Ranged Weapon Attack: +3 to hit, range 30 ft., one target. *Hit:* 6 (2d4 + 1) cold damage.

**Captivating Artistry (1/Day).** The elemental targets one creature it can see within 30 feet of itself. The target must succeed on a DC 12 Charisma saving throw or be charmed for 1 minute. The charmed target can repeat the save at the end of each of its turns, ending the effect on itself on a success.


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