---
type: pc
race: "Humanoid (elf)"
class:
 - "Soul Monger"
subClass:
 - "CR 11"
cover: "Soul Monger.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mtf
---
###### Soul Monger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Soul Monger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 14 | 19 | 15 | 13 |
| **Mod** | -1 | +3 | +2 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Elvish
**Saving Throws:** Dex +7, Wis +6, Cha +5
**Skills:** Perception +6
**Damage Immunities:** necrotic; psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Fey Ancestry.** The soul monger has advantage on saving throws against being charmed, and magic can't put it to sleep.

**Magic Resistance.** The soul monger has advantage on saving throws against spells and other magical effects.

**Soul Thirst.** When the soul monger reduces a creature to 0 hit points, the soul monger can gain temporary hit points equal to half the creature's hit point maximum. While the soul monger has temporary hit points from this ability, it has advantage on attack rolls.

**Weight of Ages.** Any beast or humanoid, other than a shadar-kai, that starts its turn within 5 feet of the soul monger has its speed reduced by 20 feet until the start of that creature's next turn.


---

### Actions

**Multiattack.** The soul monger makes two phantasmal dagger attacks.

**Phantasmal Dagger.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (4d4 + 3) piercing damage plus 19 (3d12) necrotic damage, and the target has disadvantage on saving throws until the start of the soul monger's next turn.

**Wave of Weariness (Recharge 4–6).** The soul monger emits weariness in a 60-foot cube. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 45 (10d8) psychic damage and suffers 1 level of exhaustion. On a successful save, it takes 22 (5d8) psychic damage.


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