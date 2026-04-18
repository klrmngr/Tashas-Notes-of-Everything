---
type: pc
race: "Humanoid (elf)"
class:
 - "Shadar-kai Soul Monger"
subClass:
 - "CR 11"
cover: "Shadar-kai Soul Monger.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mpmm
---
###### Shadar-kai Soul Monger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Shadar-kai Soul Monger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 136 (21d8 + 42) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 14 | 19 | 16 | 13 |
| **Mod** | -1 | +3 | +2 | +4 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Elvish
**Saving Throws:** Dex +7, Wis +7, Cha +5
**Skills:** Perception +7
**Damage Immunities:** necrotic; psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Fey Ancestry.** The shadar-kai has advantage on saving throws against being charmed, and magic can't put it to sleep.

**Magic Resistance.** The shadar-kai has advantage on saving throws against spells and other magical effects.

**Soul Thirst.** When it reduces a creature to 0 hit points, the shadar-kai can gain temporary hit points equal to half the creature's hit point maximum. While the shadar-kai has temporary hit points from this trait, it has advantage on attack rolls.

**Weight of Ages.** Any Beast or Humanoid (except an elf) that starts its turn within 5 feet of the shadar-kai has its speed reduced by 20 feet until the start of that creature's next turn.


---

### Actions

**Multiattack.** The shadar-kai makes two Shadow Dagger attacks.

**Shadow Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 13 (4d4 + 3) piercing damage plus 19 (3d12) necrotic damage, and the target has disadvantage on saving throws until the end of the shadar-kai's next turn. The dagger magically returns to the shadar-kai's hand immediately after a ranged attack.

**Wave of Weariness (Recharge 4–6).** The shadar-kai emits weariness in a 60-foot cube. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 45 (10d8) psychic damage and suffers 1 level of exhaustion. On a successful save, it takes half as much damage and doesn't gain a level of exhaustion.


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