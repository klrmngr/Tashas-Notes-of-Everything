---
type: pc
race: "Undead"
class:
 - "Eidolon"
subClass:
 - "CR 12"
cover: "Eidolon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/12
  - source/mtf
---
###### Eidolon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Eidolon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 63 (18d8 - 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 8 | 9 | 14 | 19 | 16 |
| **Mod** | -2 | -1 | -1 | +2 | +4 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** the languages it knew in life
**Saving Throws:** Wis +8
**Skills:** Perception +8
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The eidolon can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object other than a sacred statue.

**Sacred Animation (Recharge 5–6).** When the eidolon moves into a space occupied by a sacred statue, the eidolon can disappear, causing the statue to become a creature under the eidolon's control. The eidolon uses the [[Sacred Statue]]'s statistics in place of its own.

**Turn Resistance.** The eidolon has advantage on saving throws against any effect that turns undead.


---

### Actions

**Divine Dread.** Each creature within 60 feet of the eidolon that can see it must succeed on a DC 15 Wisdom saving throw or be frightened for 1 minute. While frightened in this way, the creature must take the Dash action and move away from the eidolon by the safest available route at the start of each of its turns, unless there is nowhere for it to move, in which case the creature also becomes stunned until it can move again. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to any eidolon's Divine Dread for the next 24 hours.


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