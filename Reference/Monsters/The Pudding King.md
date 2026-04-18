---
type: pc
race: "Humanoid (gnome, shapechanger)"
class:
 - "The Pudding King"
subClass:
 - "CR 4"
cover: "The Pudding King.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/oota
---
###### The Pudding King
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[The Pudding King.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome, shapechanger) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 49 (9d6 + 18) |
> | :FasUserGroup: Race | Humanoid (gnome, shapechanger) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 12 | 8 | 17 |
| **Mod** | +0 | +3 | +2 | +1 | -1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Gnomish, Terran, Undercommon
**Saving Throws:** Con +6, Cha +7
**Skills:** Arcana +4, Perception +2, Stealth +6, Survival +2
**Damage Resistances:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Stone Camouflage.** The Pudding King has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.

**Gnome Cunning.** The Pudding King has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.

**Insanity.** The Pudding King has advantage on saving throws against being charmed or frightened.


---

### Actions

**War Pick.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) piercing damage.

**Change Shape.** The Pudding King magically transforms into an type=ooze, or back into his true form. He reverts to his true form if he dies. Any equipment he is wearing or carrying is absorbed by the new form. In ooze form, the Pudding King retains his alignment, hit points, Hit Dice, and Intelligence, Wisdom, and Charisma scores, as well as this action. His statistics and capabilities are otherwise replaced by those of the new form.

**Create Green Slime (Recharges after a Long Rest).** The Pudding King creates a patch of green slime (see "Dungeon Hazards" in chapter 5 of the Dungeon Master's Guide). The slime appears on a section of wall, ceiling, or floor within 30 feet of the Pudding King.


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