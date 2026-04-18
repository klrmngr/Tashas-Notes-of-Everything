---
type: pc
race: "Humanoid"
class:
 - "Warlock of the Fiend"
subClass:
 - "CR 7"
cover: "Warlock of the Fiend.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/mpmm
---
###### Warlock of the Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Warlock of the Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 15 | 12 | 12 | 18 |
| **Mod** | +0 | +3 | +2 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** any two languages (usually Abyssal or Infernal)
**Saving Throws:** Wis +4, Cha +7
**Skills:** Arcana +4, Deception +7, Persuasion +7, Religion +4

---

### Traits

**Dark One's Own Luck (Recharges after a Short or Long Rest).** When the warlock makes an ability check or saving throw, it can add a d10 to the roll. It can do this after the roll is made but before any of the roll's effects occur.


---

### Actions

**Multiattack.** The warlock makes three Scimitar attacks.

**Scimitar.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 14 (4d6) fire damage.

**Hellfire.** Green flame explodes in a 10-foot-radius sphere centered on a point within 120 feet of the warlock. Each creature in that area must make a DC 15 Dexterity saving throw, taking 16 (3d10) fire damage and 11 (2d10) necrotic damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Fiendish Rebuke (3/Day).** In response to being damaged by a visible creature within 60 feet of it, the warlock forces that creature to make a DC 15 Constitution saving throw, taking 22 (4d10) necrotic damage on a failed save, or half as much damage on a successful one.


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