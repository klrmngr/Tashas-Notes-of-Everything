---
type: pc
race: "Humanoid (human, paladin)"
class:
 - "Strongheart"
subClass:
 - "CR 4"
cover: "Strongheart.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/wbtw
---
###### Strongheart
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Strongheart.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid (human, paladin) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 13 | 12 | 13 | 17 |
| **Mod** | +2 | +1 | +1 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Dwarvish
**Saving Throws:** Wis +3, Cha +5
**Skills:** Insight +3, Persuasion +5
**Condition Immunities:** frightened

---

### Traits

**Special Equipment.** Strongheart wields Steel, a sentient, lawful good longsword (see appendix A).


---

### Actions

**Multiattack.** Strongheart makes three Steel attacks.

**Steel.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage when used with two hands. Once on each of his turns, Strongheart can also cause the blade to gleam with holy light. If he does so, the target is blinded until the start of Strongheart's next turn.

**Revivify (Recharges at the Next Dawn).** While holding Steel, Strongheart casts revivify.


---

### Reactions

**Protect Another.** When a creature Strongheart can see attacks another creature that is within 5 feet of him, Strongheart can use his reaction to impose disadvantage on the attack roll, provided he is carrying a shield.


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