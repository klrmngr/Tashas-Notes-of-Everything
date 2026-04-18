---
type: pc
race: "Humanoid (druid)"
class:
 - "Archdruid"
subClass:
 - "CR 12"
cover: "Archdruid.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/mpmm
---
###### Archdruid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Archdruid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (druid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 154 (28d8 + 28) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 12 | 12 | 20 | 11 |
| **Mod** | +2 | +2 | +1 | +1 | +5 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Druidic plus any two languages
**Saving Throws:** Int +5, Wis +9
**Skills:** Medicine +9, Nature +5, Perception +9

---

### Actions

**Multiattack.** The archdruid makes three Staff or Wildfire attacks. It can replace one attack with a use of Spellcasting.

**Staff.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage plus 21 (6d6) poison damage.

**Wildfire.** Ranged Spell Attack: +9 to hit, range 120 ft., one target. *Hit:* 26 (6d6 + 5) fire damage, and the target is blinded until the start of the druid's next turn.


---

### Bonus Actions

**Change Shape (2/Day).** The archdruid magically transforms into a Beast or an Elemental with a challenge rating of 6 or less and can remain in that form for up to 9 hours. The archdruid can choose whether its equipment falls to the ground, melds with its new form, or is worn by the new form. The archdruid reverts to its true form if it dies or falls unconscious. The archdruid can revert to its true form using a bonus action.
While in a new form, the archdruid's stat block is replaced by the stat block of that form, except the archdruid keeps its current hit points, its hit point maximum, this bonus action, its languages and ability to speak, and its Spellcasting action.
The new form's attacks count as magical for the purpose of overcoming resistances and immunity to nonmagical attacks.


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