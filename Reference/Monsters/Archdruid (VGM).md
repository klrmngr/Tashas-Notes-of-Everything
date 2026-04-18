---
type: pc
race: "Humanoid (any race)"
class:
 - "Archdruid"
subClass:
 - "CR 12"
cover: "Archdruid.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/vgm
---
###### Archdruid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Archdruid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (hide armor, shield) |
> | :FasHeart: HP | 132 (24d8 + 24) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 12 | 20 | 11 |
| **Mod** | +0 | +2 | +1 | +1 | +5 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Druidic plus any two languages
**Saving Throws:** Int +5, Wis +9
**Skills:** Medicine +9, Nature +5, Perception +9

---

### Actions

**Scimitar.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Change Shape (2/Day).** The archdruid magically polymorphs into a beast or elemental with a challenge rating of 6 or less, and can remain in this form for up to 9 hours. The archdruid can choose whether its equipment falls to the ground, melds with its new form, or is worn by the new form. The archdruid reverts to its true form if it dies or falls unconscious. The archdruid can revert to its true form using a bonus action on its turn.
While in a new form, the archdruid retains its game statistics and ability to speak, but its AC, movement modes, Strength, and Dexterity are replaced by those of the new form, and it gains any special senses, proficiencies, traits, actions, and reactions (except class features, legendary actions, and lair actions) that the new form has but that it lacks. It can cast its spells with verbal or somatic components in its new form.
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