---
type: pc
race: "Undead"
class:
 - "Alhoon"
subClass:
 - "CR 10"
cover: "Alhoon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/vgm
---
###### Alhoon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Alhoon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 16 | 19 | 17 | 17 |
| **Mod** | +0 | +1 | +3 | +4 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Deep Speech, Undercommon, telepathy 120 ft.
**Saving Throws:** Con +7, Int +8, Wis +7, Cha +7
**Skills:** Arcana +8, Deception +7, History +8, Insight +7, Perception +7, Stealth +5
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Magic Resistance.** The alhoon has advantage on saving throws against spells and other magical effects.

**Turn Resistance.** The alhoon has advantage on saving throws against any effect that turns undead.


---

### Actions

**Chilling Grasp.** Melee Spell Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (3d6) cold damage.

**Mind Blast (Recharge 5–6).** The alhoon magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take 22 (4d8 + 4) psychic damage and be stunned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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