---
type: pc
race: "Humanoid (any race)"
class:
 - "Blood Witch"
subClass:
 - "CR 7"
cover: "Blood Witch.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/ggr
---
###### Blood Witch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Blood Witch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 13 | 9 | 19 |
| **Mod** | +3 | +2 | +2 | +1 | -1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal plus any one language (usually Common)
**Saving Throws:** Wis +2, Cha +7
**Skills:** Arcana +4, Intimidation +7, Perception +2, Stealth +5
**Damage Resistances:** psychic

---

### Traits

**Blood Witch Dance.** The witch can use a bonus action to control the movement of one creature cursed by its hex spell that it can see within 30 feet of it. The creature must succeed on a DC 15 Charisma saving throw or use its reaction to move up to 30 feet in a direction of the witch's choice.

**Devil's Sight.** Magical darkness doesn't impede the witch's darkvision.


---

### Actions

**Multiattack.** The witch makes two attacks: one with its longsword and one with its shortsword.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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