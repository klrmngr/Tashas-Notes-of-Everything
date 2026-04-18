---
type: pc
race: "Undead"
class:
 - "Will-o'-Wisp"
subClass:
 - "CR 2"
cover: "Will-o'-Wisp.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/2
  - source/mm
---
###### Will-o'-Wisp
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Will-o'-Wisp.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 22 (9d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 28 | 10 | 13 | 14 | 11 |
| **Mod** | -5 | +9 | +0 | +1 | +2 | +0 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** the languages it knew in life
**Damage Resistances:** acid; cold; fire; necrotic; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; poisoned; prone; restrained; unconscious

---

### Traits

**Consume Life.** As a bonus action, the will-o'-wisp can target one creature it can see within 5 feet of it that has 0 hit points and is still alive. The target must succeed on a DC 10 Constitution saving throw against this magic or die. If the target dies, the will-o'-wisp regains 10 (3d6) hit points.

**Ephemeral.** The will-o'-wisp can't wear or carry anything.

**Incorporeal Movement.** The will-o'-wisp can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Variable Illumination.** The will-o'-wisp sheds bright light in a 5 to 20-foot radius and dim light for an additional number of ft. equal to the chosen radius. The will-o'-wisp can alter the radius as a bonus action.


---

### Actions

**Shock.** Melee Spell Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 9 (2d8) lightning damage.

**Invisibility.** The will-o'-wisp and its light magically become invisible until it attacks or uses its Consume Life, or until its concentration ends (as if concentrating on a spell).


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