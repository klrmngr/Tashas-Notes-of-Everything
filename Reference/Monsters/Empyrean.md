---
type: pc
race: "Celestial (titan)"
class:
 - "Empyrean"
subClass:
 - "CR 23"
cover: "Empyrean.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/celestial
  - size/huge
  - cr/23
  - source/mm
---
###### Empyrean
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Empyrean.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Huge Celestial (titan) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good or Neutral Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 313 (19d12 + 190) |
> | :FasUserGroup: Race | Celestial (titan) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 21 | 30 | 21 | 22 | 27 |
| **Mod** | +10 | +5 | +10 | +5 | +6 | +8 |

**Speed:** 50 ft., fly 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** all
**Saving Throws:** Str +17, Int +12, Wis +13, Cha +15
**Skills:** Insight +13, Persuasion +15
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Legendary Resistance (3/Day).** If the empyrean fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The empyrean has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The empyrean's weapon attacks are magical.


---

### Actions

**Maul.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 31 (6d6 + 10) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or be stunned until the end of the empyrean's next turn.

**Bolt.** Ranged Spell Attack: +15 to hit, range 600 ft., one target. *Hit:* 24 (7d6) damage of one of the following types (empyrean's choice): acid, cold, fire, force, lightning, radiant, or thunder.


---

### Legendary Actions

### 

**Attack.** The empyrean makes one attack.

**Bolster.** The empyrean bolsters all nonhostile creatures within 120 feet of it until the end of its next turn. Bolstered creatures can't be charmed or frightened, and they gain advantage on ability checks and saving throws until the end of the empyrean's next turn.

**Trembling Strike (Costs 2 Actions).** The empyrean strikes the ground with its maul, triggering an earth tremor. All other creatures on the ground within 60 feet of the empyrean must succeed on a DC 25 Strength saving throw or be knocked prone.


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