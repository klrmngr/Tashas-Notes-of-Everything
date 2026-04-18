---
type: pc
race: "Humanoid (human, sorcerer)"
class:
 - "Kelek"
subClass:
 - "CR 5"
cover: "Kelek.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/wbtw
---
###### Kelek
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Kelek.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 (bracers of defense) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (human, sorcerer) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 14 | 15 | 13 | 17 |
| **Mod** | +2 | +0 | +2 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Elvish
**Saving Throws:** Con +5, Cha +6
**Skills:** Deception +6, Intimidation +6

---

### Traits

**Special Equipment.** Kelek wears bracers of defense and carries a staff of striking with 10 charges. The staff regains 1d6 + 4 expended charges daily at dawn. If its last charge is expended, roll a d20; on a 1, the staff becomes a nonmagical quarterstaff.


---

### Actions

**Multiattack.** Kelek makes three attacks using Sorcerer's Bolt, Staff of Striking, or a combination of them. He can replace one of the attacks with a use of Spellcasting.

**Sorcerer's Bolt.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 13 (2d12) force damage.

**Staff of Striking.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) bludgeoning damage, or 9 (1d8 + 5) bludgeoning damage when used with two hands, and Kelek can expend up to 3 of the staff's charges, dealing an extra 3 (1d6) force damage for each expended charge.

**Fiery Explosion (Recharge 4–6).** Kelek creates a magical explosion of fire centered on a point he can see within 120 feet of him. Each creature in a 20-foot-radius sphere centered on that point must make a DC 14 Dexterity saving throw, taking 35 (10d6) fire damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Arcane Defense (3/Day).** When he is hit by an attack, Kelek protects himself with an invisible barrier of magical force. Until the end of his next turn, he gains a +5 bonus to AC, including against the triggering attack.


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