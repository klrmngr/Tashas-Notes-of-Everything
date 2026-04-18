---
type: pc
race: "Dragon (gem)"
class:
 - "Young Topaz Dragon"
subClass:
 - "CR 7"
cover: "Young Topaz Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/ftd
---
###### Young Topaz Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Topaz Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon (gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 127 (17d10 + 34) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 15 | 16 | 15 | 16 |
| **Mod** | +3 | +1 | +2 | +3 | +2 | +3 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +5, Wis +5, Cha +6
**Skills:** Intimidation +9, Perception +8, Stealth +4
**Damage Resistances:** cold; necrotic

---

### Traits

**Amphibious.** The dragon can breathe both air and water.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage plus 3 (1d6) necrotic damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Desiccating Breath (Recharge 5–6).** The dragon exhales yellowish necrotic energy in a 30-foot cone. Each creature in that area must make a DC 13 Constitution saving throw. On a failed save, the creature takes 28 (8d6) necrotic damage and is weakened until the end of its next turn. A weakened creature has disadvantage on Strength-based ability checks and Strength saving throws, and the creature's weapon attacks that rely on Strength deal half damage. On a successful save, the creature takes half as much damage and isn't weakened.


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