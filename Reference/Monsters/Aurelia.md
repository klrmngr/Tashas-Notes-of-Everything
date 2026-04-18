---
type: pc
race: "Celestial (angel)"
class:
 - "Aurelia"
subClass:
 - "CR 23"
cover: "Aurelia.png"
campaign:
locations:
tags:
  - race/angel
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/23
  - source/ggr
---
###### Aurelia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Aurelia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Medium Celestial (angel) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 287 (25d8 + 175) |
> | :FasUserGroup: Race | Celestial (angel) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 24 | 25 | 17 | 25 | 30 |
| **Mod** | +8 | +7 | +7 | +3 | +7 | +10 |

**Speed:** 50 ft., fly 150 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all
**Saving Throws:** Dex +14, Con +14, Cha +17
**Skills:** Insight +14, Perception +14
**Damage Resistances:** necrotic; radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Aurelia fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Aurelia has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Aurelia makes three longsword attacks and uses Leadership.

**Longsword.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 12 (1d8 + 8) slashing damage, or 13 (1d10 + 8) slashing damage when used with two hands, plus 27 (6d8) radiant damage.

**Leadership.** Aurelia utters a few inspiring words to one creature she can see within 30 feet of her. If the creature can hear her, it can add a d10 to one attack roll or saving throw it makes before the start of Aurelia's next turn.

**Warleader's Helix (Recharge 5–6).** Ranged Spell Attack: +17 to hit, range 60 ft., one creature. *Hit:* 54 (12d8) radiant damage, and Aurelia can choose another creature she can see within 10 feet of the target. The second creature regains 27 (6d8) hit points.


---

### Reactions

**Parry.** Aurelia adds 7 to her AC against one melee attack that would hit her. To do so, Aurelia must see the attacker and be wielding a melee weapon.

**Unyielding.** When Aurelia is subjected to an effect that would move her, knock her prone, or both, she can use her reaction to be neither moved nor knocked prone.


---

### Legendary Actions

### 

**Command Allies.** Aurelia chooses up to three creatures she can see within 30 feet of her. If a chosen creature can see or hear Aurelia, it can immediately use its reaction to make one weapon attack, with advantage on the attack roll.

**Longsword Attack (Costs 2 Actions).** Aurelia makes one longsword attack.

**Frighten Foes (Costs 3 Actions).** Aurelia targets up to five creatures she can see within 30 feet of her. Each target must succeed on a DC 25 Wisdom saving throw or be frightened of her until the end of her next turn. Any target within 5 feet of Aurelia has disadvantage on the saving throw.


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