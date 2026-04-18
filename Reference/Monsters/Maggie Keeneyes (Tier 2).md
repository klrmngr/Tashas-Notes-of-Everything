---
type: pc
race: "Giant (ogre)"
class:
 - "Maggie Keeneyes (Tier 2)"
subClass:
 - "CR 5"
cover: "Maggie Keeneyes (Tier 2).png"
campaign:
locations:
tags:
  - race/ogre
  - affinity/hostile
  - type/giant
  - size/large
  - cr/5
  - source/crcotn
---
###### Maggie Keeneyes (Tier 2)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Maggie Keeneyes (Tier 2).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Giant (ogre) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Giant (ogre) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 14 | 16 | 8 |
| **Mod** | +4 | +2 | +4 | +2 | +3 | -1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Giant
**Saving Throws:** Str +7, Con +7
**Skills:** Athletics +7, Insight +6, Perception +6, Persuasion +5
**Condition Immunities:** frightened

---

### Traits

**Push.** Once during each of her turns, after hitting a creature with an attack, Maggie can force the target to make a DC 15 Strength saving throw; on a failed save, the target is pushed up to 10 feet horizontally away from Maggie and knocked prone.

**Tactical Readiness.** Maggie and allies within 30 feet of her have advantage on initiative rolls, as long as Maggie isn't incapacitated.


---

### Actions

**Multiattack.** Maggie makes two Giant Maul or Hammer Toss attacks.

**Giant Maul.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.

**Hammer Toss.** Ranged Weapon Attack: +7 to hit, range 20/60 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage.


---

### Bonus Actions

**Rally (1/Day).** Maggie targets one creature she can see within 30 feet of herself and bolsters it with words of encouragement. The target gains 15 temporary hit points if it can see or hear Maggie.


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