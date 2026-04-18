---
type: pc
race: "Humanoid (cleric)"
class:
 - "Firbolg Wanderer"
subClass:
 - "CR 5"
cover: "Firbolg Wanderer.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bgg
---
###### Firbolg Wanderer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Firbolg Wanderer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 14 | 17 | 16 |
| **Mod** | +3 | +2 | +3 | +2 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Giant
**Saving Throws:** Dex +5, Cha +6
**Skills:** Perception +6, Persuasion +6, Stealth +5

---

### Actions

**Multiattack.** The firbolg makes two attacks using Longsword, Bewitching Bolt, or a combination of them.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands, plus 9 (2d8) psychic damage.

**Bewitching Bolt.** Ranged Spell Attack: +6 to hit, range 60 ft., one creature. *Hit:* 10 (2d6 + 3) psychic damage, and the target must succeed on a DC 14 Charisma saving throw or have the charmed condition until the start of the target's next turn.


---

### Bonus Actions

**Duplicitous Movement (1/Day).** The firbolg projects an illusory duplicate of itself in an unoccupied space it can see within 30 feet of itself. The firbolg can then swap places with the illusion. The illusion vanishes after 1 minute, if the firbolg is incapacitated, or if the illusion is more than 120 feet from the firbolg.
As a bonus action on later turns, the firbolg can move the illusion up to 30 feet and can then swap places with it.


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