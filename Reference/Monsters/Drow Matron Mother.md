---
type: pc
race: "Humanoid (cleric, elf)"
class:
 - "Drow Matron Mother"
subClass:
 - "CR 20"
cover: "Drow Matron Mother.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/20
  - source/mpmm
---
###### Drow Matron Mother
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Drow Matron Mother.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric, elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 247 (33d8 + 99) |
> | :FasUserGroup: Race | Humanoid (cleric, elf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Special Equipment.** The drow wields a tentacle rod.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The drow makes two Demon Staff attacks or one Demon Staff attack and three Tentacle Rod attacks.

**Demon Staff.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage, or 8 (1d8 + 4) bludgeoning damage if used with two hands, plus 14 (4d6) psychic damage. The target must succeed on a DC 19 Wisdom saving throw or become frightened of the drow for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tentacle Rod.** Melee Weapon Attack: +9 to hit, reach 15 ft., one creature. *Hit:* 3 (1d6) bludgeoning damage. If the target is hit three times by the rod on one turn, the target must succeed on a DC 15 Constitution saving throw or suffer the following effects for 1 minute: the target's speed is halved, it has disadvantage on Dexterity saving throws, and it can't use reactions. Moreover, on each of its turns, it can take either an action or a bonus action, but not both. At the end of each of its turns, it can repeat the saving throw, ending the effect on itself on a success.

**Divine Flame (2/Day).** A 10-foot-radius, 40-foot-high column of divine fire sprouts in an area up to 120 feet away from the drow. Each creature in the column must make a DC 20 Dexterity saving throw, taking 14 (4d6) fire damage and 14 (4d6) radiant damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Lolth's Fickle Favor.** The drow bestows the Spider Queen's blessing on one ally she can see within 30 feet of her. The ally takes 7 (2d6) psychic damage but has advantage on the next attack roll it makes before the end of its next turn.

**Summon Servant (1/Day).** The drow magically summons a glabrezu or a yochlol. The summoned creature appears in an unoccupied space within 60 feet of its summoner, acts as an ally of its summoner, and can't summon other demons. It remains for 10 minutes, until it or its summoner dies, or until its summoner dismisses it as an action.


---

### Legendary Actions

### 

**Compel Demon.** An allied demon within 30 feet of the drow uses its reaction to make one attack against a target of the drow's choice that she can see.

**Demon Staff.** The drow makes one Demon Staff attack.

**Cast a Spell (Costs 2 Actions).** The drow uses Spellcasting.


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