---
type: pc
race: "Humanoid"
class:
 - "Tarkanan Marauder"
subClass:
 - "CR 11"
cover: "Tarkanan Marauder.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/11
  - source/efa
---
###### Tarkanan Marauder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Tarkanan Marauder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 247 (26d8 + 130) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 17 | 20 | 16 | 15 | 13 |
| **Mod** | +2 | +3 | +5 | +3 | +2 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +7, Con +9, Wis +6
**Skills:** Deception +5, Perception +6, Stealth +7

---

### Traits

**Evasion.** If the marauder is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the marauder instead takes no damage if it succeeds on the save and only half as much damage if it fails. It can't use this trait if it has the Incapacitated condition.


---

### Actions

**Multiattack.** The marauder makes three Aberrant Strike attacks.

**Aberrant Strike.** m +7, reach 5 ft. *Hit:* 13 (3d6 + 3) Piercing damage, plus 21 (6d6) Force damage if the marauder had Advantage on the attack roll.


---

### Bonus Actions

**Tear Through Space.** The marauder teleports to a space it can see within 30 feet, appearing in a dazzling flash. con DC 17, each creature in a 5-foot Emanation originating from the marauder when it appears.  The target has the Blinded condition until the end of the marauder's next turn.


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