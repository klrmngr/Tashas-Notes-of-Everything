---
type: pc
race: "Giant (ogre)"
class:
 - "Maggie Keeneyes (Tier 3)"
subClass:
 - "CR 8"
cover: "Maggie Keeneyes (Tier 3).png"
campaign:
locations:
tags:
  - race/ogre
  - affinity/hostile
  - type/giant
  - size/large
  - cr/8
  - source/crcotn
---
###### Maggie Keeneyes (Tier 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Maggie Keeneyes (Tier 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Giant (ogre) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Giant (ogre) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 14 | 14 | 8 |
| **Mod** | +5 | +2 | +4 | +2 | +2 | -1 |

**Speed:** 30 ft., swim 30 ft. ((ruidium armor)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Giant
**Saving Throws:** Str +8, Con +7
**Skills:** Athletics +8, Insight +5, Perception +5, Persuasion +5
**Damage Resistances:** psychic (granted by ruidium armor)
**Condition Immunities:** charmed; frightened

---

### Traits

**Push.** Once during each of her turns, after hitting a creature with an attack, Maggie can force the target to make a DC 16 Strength saving throw; on a failed save, the target is pushed up to 15 feet horizontally away from Maggie and knocked prone.

**Special Equipment.** Maggie wears a suit of ruidium armor (plate; see appendix B). If Maggie rolls a 1 on a saving throw while wearing the armor, she must succeed on a DC 20 Charisma saving throw or gain 1 level of exhaustion.

**Tactical Readiness.** Maggie and allies within 30 feet of her have advantage on initiative rolls, as long as Maggie isn't incapacitated.


---

### Actions

**Multiattack.** Maggie makes two Heavy Greataxe or Hammer Toss attacks.

**Heavy Greataxe.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d12 + 5) slashing damage.

**Hammer Toss.** Ranged Weapon Attack: +8 to hit, range 20/60 ft., one target. *Hit:* 15 (4d4 + 5) bludgeoning damage.


---

### Bonus Actions

**Rally (1/Day).** Maggie targets one creature she can see within 60 feet of herself and bolsters it with words of encouragement. The target gains 30 temporary hit points if it can see or hear Maggie.


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