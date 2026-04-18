---
type: pc
race: "Humanoid (human)"
class:
 - "Valygar"
subClass:
 - "CR 9"
cover: "Valygar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Valygar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Valygar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 187 (25d8 + 75) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 16 | 10 | 11 | 10 |
| **Mod** | +2 | +4 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Draconic, Primordial
**Saving Throws:** Str +6, Dex +8
**Skills:** Arcana +4, History +4, Perception +4

---

### Traits

**Magic Resistance.** Valygar has advantage on saving throws against spells and other magical effects.

**Mage Slaying.** When Valygar deals damage to a creature that is concentrating on a spell, that creature has disadvantage on the saving throw it makes to maintain its concentration.


---

### Actions

**Multiattack.** Valygar makes two Katana attacks and one Hand Crossbow attack or he makes two Hand Crossbow attacks.

**Katana.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands plus 13 (3d8) poison damage.

**Hand Crossbow.** Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, Valygar can take the Hide action as a bonus action.


---

### Reactions

**Disrupt Spell.** When a creature within 5 feet of Valygar casts a spell, he can use his reaction to make a melee weapon attack against that creature.


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