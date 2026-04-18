---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Simon Aumar"
subClass:
 - "CR 5"
cover: "Simon Aumar.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hat-tg
---
###### Simon Aumar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Simon Aumar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 13 | 16 | 12 | 17 |
| **Mod** | -1 | +2 | +1 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic, Elvish
**Saving Throws:** Con +4, Cha +6
**Skills:** Arcana +6, Deception +6, History +6, Religion +6, Survival +4

---

### Traits

**Fey Ancestry.** Simon has advantage on saving throws he makes to avoid or end the charmed condition on himself, and magic can't put him to sleep.

**Special Equipment.** Simon carries a bag of holding, two pairs of sending stones, and a deathly token (see Spellcasting).

**Wild Magic.** When Simon takes 20 or more damage from a single source or takes damage from a critical hit, he must roll on the Wild Magic Surge table in the Player's Handbook.


---

### Actions

**Multiattack.** Simon makes three Quarterstaff or Chaos Bolt attacks. He can replace one attack with one use of Spellcasting.

**Quarterstaff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands, plus 11 (2d10) force damage.

**Chaos Bolt.** Ranged Spell Attack: +6 to hit, range 60 ft., one target. *Hit:* 14 (2d10 + 3) damage of a random type determined by rolling a d8: 1, acid; 2, cold; 3, fire; 4, force; 5, lightning; 6, poison; 7, psychic; 8, thunder.


---

### Reactions

**Sheltering Shield (3/Day).** When Simon or another creature he can see within 10 feet of himself would take damage, he conjures a shimmering, 10-foot-radius sphere of magical force centered on himself. Creatures inside the sphere have resistance to the damage that triggered this reaction.


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