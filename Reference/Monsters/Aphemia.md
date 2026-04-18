---
type: pc
race: "Monstrosity"
class:
 - "Aphemia"
subClass:
 - "CR 5"
cover: "Aphemia.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/mot
---
###### Aphemia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Aphemia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 13 | 14 | 16 |
| **Mod** | +1 | +3 | +2 | +1 | +2 | +3 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Common
**Saving Throws:** Dex +6, Cha +6
**Skills:** Arcana +4, Intimidation +6, Perception +5
**Damage Resistances:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (2/Day).** If Aphemia fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Aphemia has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Aphemia makes two attacks: one with her bite and one with her claws.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) piercing damage plus 13 (3d8) necrotic damage.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.

**Discordant Song.** Aphemia shrieks a cacophony of magical sounds. Each humanoid within 120 feet of her must succeed on a DC 14 Wisdom saving throw or be frightened of her until the song ends. A frightened creature takes 7 (2d6) psychic damage at the start of its turn while Aphemia is singing. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Aphemia's Discordant Song for the next 24 hours. Aphemia must take a bonus action on her subsequent turns to continue singing. She can stop singing at any time. The song ends if Aphemia is incapacitated or dies.

**Grave Calling Song.** Aphemia intones a low, growling magical melody. Every undead within 300 feet of her must succeed on a DC 14 Wisdom saving throw or fall under her control until the song ends. Aphemia must take a bonus action on her subsequent turns to continue singing, and she can mentally command the undead under her control as part of the same bonus action. She can stop singing at any time. The song ends if Aphemia is incapacitated or dies.


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