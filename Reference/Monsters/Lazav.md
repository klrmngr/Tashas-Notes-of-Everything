---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Lazav"
subClass:
 - "CR 17"
cover: "Lazav.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/17
  - source/ggr
---
###### Lazav
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Lazav.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 204 (24d8 + 96) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 24 | 18 | 22 | 20 | 22 |
| **Mod** | +3 | +7 | +4 | +6 | +5 | +6 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +13, Int +12, Wis +11, Cha +12
**Skills:** Deception +18, Insight +11, Perception +11, Stealth +19
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Elusive.** No attack roll has advantage against Lazav unless he is incapacitated.

**Legendary Resistance (3/Day).** If Lazav fails a saving throw, he can choose to succeed instead.

**Shapechanger Savant.** Lazav can use a bonus action to polymorph into a Small or Medium humanoid he has seen. His statistics, other than his size, are the same in each form. Any equipment he is wearing or carrying isn't transformed.

**Psychic Defenses.** Unless Lazav is incapacitated, he is immune to magic that allows other creatures to read his thoughts, determine whether he is lying, know his alignment, or know his creature type. Creatures can telepathically communicate with Lazav only if he allows it.


---

### Actions

**Multiattack.** Lazav makes three shortsword attacks.

**Shortsword.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 10 (1d6 + 7) piercing damage plus 10 (3d6) psychic damage, and the target has disadvantage on the next attack roll it makes before Lazav's next turn.


---

### Legendary Actions

### 

**Attack.** Lazav makes a weapon attack.

**Cast a Spell (Costs 2 Actions).** Lazav casts one of his innate spells.

**Shifting Nightmare (Costs 3 Actions).** Lazav rapidly takes the form of several nightmarish creatures, lashing out at all nearby. Each creature within 10 feet of Lazav must succeed on a DC 21 Dexterity saving throw or take 18 (4d8) damage of a type chosen by Lazav: acid, cold, fire, lightning, or necrotic.


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