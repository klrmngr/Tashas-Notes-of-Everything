---
type: pc
race: "Humanoid (paladin)"
class:
 - "Solar Bastion Knight"
subClass:
 - "CR 9"
cover: "Solar Bastion Knight.png"
campaign:
locations:
tags:
  - race/paladin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/bmt
---
###### Solar Bastion Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Solar Bastion Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (paladin) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 17 | 15 | 16 | 17 |
| **Mod** | +4 | +0 | +3 | +2 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common plus any one language
**Saving Throws:** Wis +7, Cha +7
**Skills:** Arcana +6, History +6
**Condition Immunities:** blinded; charmed; frightened

---

### Traits

**Aura of Protection.** The knight and each ally within 10 feet of it have advantage on saving throws. This trait is suppressed while the knight has the incapacitated condition.


---

### Actions

**Multiattack.** The knight makes three Sunspear attacks.

**Sunspear.** Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) radiant damage, or 21 (5d6 + 4) radiant damage if the target is a Fiend or an Undead.

**Solar Flare (Recharge 5–6).** The knight unleashes a blaze of brilliant energy that fills a 30-foot-radius sphere centered on the knight. Each creature of the knight's choice in that area must make a DC 15 Dexterity saving throw. On a failed save, a creature takes 22 (4d10) radiant damage and has the blinded condition until the end of its next turn. On a successful save, a creature takes half as much damage only. For the next minute, the affected area is filled with bright light that is sunlight.


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