---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Matron Mother"
subClass:
 - "CR 20"
cover: "Drow Matron Mother.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/20
  - source/mtf
---
###### Drow Matron Mother
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Drow Matron Mother.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 262 (35d8 + 105) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 16 | 17 | 21 | 22 |
| **Mod** | +1 | +4 | +3 | +3 | +5 | +6 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** Elvish, Undercommon
**Saving Throws:** Con +9, Wis +11, Cha +12
**Skills:** Insight +11, Perception +11, Religion +9, Stealth +10
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Fey Ancestry.** The drow has advantage on saving throws against being charmed, and magic can't put the drow to sleep.

**Lolth's Fickle Favor.** As a bonus action, the matron can bestow the Spider Queen's blessing on one ally she can see within 30 feet of her. The ally takes 7 (2d6) psychic damage but has advantage on the next attack roll it makes until the end of its next turn.

**Magic Resistance.** The drow has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The matron mother makes two demon staff attacks or three tentacle rod attacks.

**Demon Staff.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage, or 8 (1d8 + 4) bludgeoning damage if used with two hands, plus 14 (4d6) psychic damage. In addition, the target must succeed on a DC19 Wisdom saving throw or become frightened of the drow for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tentacle Rod.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 3 (1d6) bludgeoning damage. If the target is hit three times by the rod on one turn, the target must succeed on a DC 15 Constitution saving throw or suffer the following effects for 1 minute: the target's speed is halved, it has disadvantage on Dexterity saving throws, and it can't use reactions. Moreover, on each of its turns, it can take either an action or a bonus action, but not both. At the end of each of its turns, it can repeat the saving throw, ending the effect on itself on a success.

**Summon Servant (1/Day).** The drow magically summons a [[Retriever]] or a [[Yochlol]]. The summoned creature appears in an unoccupied space within 60 feet of its summoner, acts as an ally of its summoner, and can't summon other demons. It remains for 10 minutes, until it or its summoner dies, or until its summoner dismisses it as an action.


---

### Legendary Actions

### 

**Demon Staff.** The drow makes one attack with her demon staff.

**Compel Demon (Costs 2 Actions).** An allied demon within 30 feet of the drow uses its reaction to make one attack against a target of the drow's choice that she can see.

**Cast a Spell (Costs 1–3 Actions).** The drow expends a spell slot to cast a 1st-, 2nd-, or 3rd-level spell that she has prepared. Doing so costs 1 legendary action per level of the spell.


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