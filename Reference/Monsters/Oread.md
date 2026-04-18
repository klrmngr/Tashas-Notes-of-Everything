---
type: pc
race: "Fey"
class:
 - "Oread"
subClass:
 - "CR 4"
cover: "Oread.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/4
  - source/mot
---
###### Oread
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Oread.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 12 | 11 | 13 | 18 |
| **Mod** | +2 | +2 | +1 | +0 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Sylvan
**Skills:** Acrobatics +4, Athletics +4, Performance +6
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Invisible in Fire.** The oread is invisible while fully immersed in fire.

**Magic Resistance.** The oread has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The oread attacks twice with its fiery touch or fire bolt.

**Fiery Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) fire damage.

**Fire Bolt (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 5 (1d10) fire damage.


---

### Reactions

**Hellish Rebuke (2nd-Level Spell; 1/Day).** When the oread is damaged by a creature within 60 feet of the oread that it can see, the creature that damaged the oread must make a DC 14 Dexterity saving throw, taking 16 (3d10) fire damage on a failed save, or half as much damage on a successful one.


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