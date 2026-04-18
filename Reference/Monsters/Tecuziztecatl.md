---
type: pc
race: "Monstrosity"
class:
 - "Tecuziztecatl"
subClass:
 - "CR 4"
cover: "Tecuziztecatl.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/tftyp
---
###### Tecuziztecatl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Tecuziztecatl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 102 (12d10 + 36) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 16 | 15 | 16 | 13 |
| **Mod** | +3 | +0 | +3 | +2 | +3 | +1 |

**Speed:** 30 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 13
**Languages:** Olman, Primordial
**Skills:** Deception +3, Stealth +2
**Damage Resistances:** bludgeoning from nonmagical attacks
**Damage Immunities:** acid

---

### Traits

**Amphibious.** Tecuziztecatl can breathe air and water.

**Glowing.** Tecuziztecatl sheds dim light within 20 feet of itself.

**Flexible.** Tecuziztecatl can enter a space large enough for a Medium creature without squeezing.

**Spider Climb.** Tecuziztecatl can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** Tecuziztecatl makes two pseudopod attacks.

**Pseudopod.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage.

**Spit Acid (Recharge 4–6).** Tecuziztecatl exhales acid in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 13 Dexterity saving throw, taking 18 (4d8) acid damage on a failed save, or half as much damage on a successful one.


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