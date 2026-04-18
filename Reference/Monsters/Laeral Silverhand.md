---
type: pc
race: "Humanoid (human)"
class:
 - "Laeral Silverhand"
subClass:
 - "CR 17"
cover: "Laeral Silverhand.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/17
  - source/wdh
---
###### Laeral Silverhand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Laeral Silverhand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 (robe of the archmagi) |
> | :FasHeart: HP | 228 (24d8 + 120) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 17 | 20 | 20 | 20 | 19 |
| **Mod** | +1 | +3 | +5 | +5 | +5 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 21
**Languages:** Common, Draconic, Dwarvish, Elvish, Giant, Infernal
**Saving Throws:** Int +11, Wis +11
**Skills:** Arcana +17, History +17, Insight +11, Perception +11, Persuasion +10
**Damage Resistances:** fire
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Special Equipment.** Laeral wears a white robe of the archmagi (accounted for in her statistics). She wields a flame tongue longsword.

**Magic Resistance.** While wearing her robe of the archmagi, Laeral has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Laeral makes three attacks with her silver hair and flame tongue, in any combination. She can cast one of her cantrips or 1st-level spells before or after making these attacks.

**Silver Hair.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 7 (2d6) force damage, and the target must succeed on a DC 19 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Flame Tongue.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage plus 7 (2d6) fire damage, or 6 (1d10 + 1) slashing damage plus 7 (2d6) fire damage when used with two hands.

**Spellfire (Recharges after a Long Rest).** Magical, heatless, silver fire harmlessly erupts from Laeral and surrounds her until she is incapacitated or until she uses an action to quench it. She gains one of the following benefits of her choice, which lasts until the silver fire ends:
- She can breathe underwater.
- She can survive without food and water.
- She is immune to magic that would ascertain her thoughts, truthfulness, alignment, or creature type.
- She gains resistance to cold damage, and she is unharmed by temperatures as low as -50 degrees Fahrenheit.
While the silver fire is present, she has the following additional action options:
- Cast the cure wounds spell. The target regains 1d8 + 5 hit points. After Laeral takes this action, roll a d6. On a roll of 1, the silver fire disappears.
- Cast the revivify spell without material components. After Laeral takes this action, roll a d6. On a roll of 1-2, the silver fire disappears.
- Release a 60-foot line of silver fire that is 5 feet wide or a 30-foot cone of silver fire. Objects in the area that aren't being worn or carried take 26 (4d12) fire damage. Each creature in the area must succeed on a DC 21 Dexterity saving throw, taking 26 (4d12) fire damage on a failed save, or half as much damage on a successful one. After Laeral takes this action, roll a d6. On a roll of 1-3, the silver fire disappears.


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