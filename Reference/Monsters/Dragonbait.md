---
type: pc
race: "Humanoid (saurial)"
class:
 - "Dragonbait"
subClass:
 - "CR 5"
cover: "Dragonbait.png"
campaign:
locations:
tags:
  - race/saurial
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/toa
---
###### Dragonbait
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Dragonbait.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (saurial) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (breastplate, shield) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Humanoid (saurial) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 17 | 14 | 16 | 18 |
| **Mod** | +2 | +1 | +3 | +2 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** understands Common but can't speak
**Saving Throws:** Wis +6, Cha +7
**Skills:** Athletics +5, Medicine +6
**Condition Immunities:** disease

---

### Traits

**Divine Health.** Dragonbait is immune to disease.

**Magic Resistance.** While holding his holy avenger longsword, Dragonbait creates an aura in a 10-foot radius around him. While this aura is active, Dragonbait and all creatures friendly to him in the aura have advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Dragonbait makes two melee weapon attacks.

**Holy Avenger (+3 Longsword).** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage when used with two hands. If the target is a fiend or an undead it takes an extra 11 (2d10) radiant damage.

**Sense Alignment.** Dragonbait chooses one creature he can see within 60 feet of him and determines its alignment, as long as the creature isn't hidden from divination magic by a spell or other magical effect.


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