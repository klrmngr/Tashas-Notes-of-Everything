---
type: pc
race: "Aberration"
class:
 - "Lesser Star Spawn Emissary"
subClass:
 - "CR 19"
cover: "Lesser Star Spawn Emissary.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/19
  - source/vrgr
---
###### Lesser Star Spawn Emissary
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Lesser Star Spawn Emissary.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 241 (21d8 + 147) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 24 | 25 | 20 | 23 |
| **Mod** | +5 | +4 | +7 | +7 | +5 | +6 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 1,000 ft.
**Saving Throws:** Int +13, Wis +11, Cha +12
**Skills:** Arcana +19, Deception +18, Perception +11
**Damage Resistances:** acid; force; necrotic; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Aberrant Rejuvenation.** When the emissary drops to 0 hit points, its body melts away. A greater star spawn emissary instantly appears in an unoccupied space within 60 feet of where the lesser emissary disappeared. The greater emissary uses the lesser emissary's initiative count.

**Legendary Resistance (3/Day).** If the emissary fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The emissary doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The emissary makes three attacks.

**Lashing Maw.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 13 (3d8) acid damage.

**Psychic Orb.** Ranged Spell Attack: +13 to hit, range 120 ft., one creature. *Hit:* 18 (2d10 + 7) psychic damage.

**Change Shape.** The emissary polymorphs into a Small or Medium creature of its choice or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


---

### Legendary Actions

### 

**Psychic Orb.** The emissary makes a Psychic Orb attack.

**Teleportation Maw (Costs 2 Actions).** The emissary teleports to an unoccupied space it can see within 30 feet of it and can make a Lashing Maw attack.

**Psychic Lash (Costs 3 Actions).** The emissary targets a creature it can see within 30 feet of it and psychically lashes at that creature's mind. The target must succeed on a DC 21 Wisdom saving throw or take 36 (8d8) psychic damage and be stunned until the start of its next turn.


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