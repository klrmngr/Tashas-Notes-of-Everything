---
type: pc
race: "Dragon"
class:
 - "Niv-Mizzet"
subClass:
 - "CR 26"
cover: "Niv-Mizzet.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/26
  - source/ggr
---
###### Niv-Mizzet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Niv-Mizzet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 370 (19d20 + 171) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 29 | 30 | 17 | 25 |
| **Mod** | +9 | +2 | +9 | +10 | +3 | +7 |

**Speed:** 40 ft., climb 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Con +17, Int +18, Wis +11
**Skills:** Arcana +18, Insight +11, Perception +11
**Damage Resistances:** cold; psychic; thunder
**Damage Immunities:** fire; lightning
**Condition Immunities:** charmed

---

### Traits

**Legendary Resistance (3/Day).** If Niv-Mizzet fails a saving throw, he can choose to succeed instead.

**Locus of the Firemind.** Niv-Mizzet can maintain concentration on two different spells at the same time. In addition, he has advantage on saving throws to maintain concentration on spells.

**Magic Resistance.** Niv-Mizzet has advantage on saving throws against spells and other magical effects.

**Master Chemister.** When Niv-Mizzet casts a spell that deals damage, he can change the spell's damage to cold, fire, force, lightning, or thunder.


---

### Actions

**Multiattack.** Niv-Mizzet makes three attacks: one with his bite and two with his claws.

**Bite.** Melee Weapon Attack: +17 to hit, reach 15 ft., one target. *Hit:* 18 (2d8 + 9) piercing damage plus 14 (4d6) fire damage.

**Claw.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 14 (2d4 + 9) slashing damage.

**Tail.** Melee Weapon Attack: +17 to hit, reach 20 ft., one target. *Hit:* 16 (2d6 + 9) bludgeoning damage.

**Fire Breath (Recharge 5–6).** Niv-Mizzet exhales fire in a 90-foot cone. Each creature in that area must make a DC 25 Dexterity saving throw, taking 91 (26d6) fire damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Cantrip.** Niv-Mizzet casts one of his cantrips.

**Tail Attack.** Niv-Mizzet makes a tail attack.

**Wing Attack (Costs 2 Actions).** Niv-Mizzet beats his wings. Each creature within 15 feet of him must succeed on a DC 25 Dexterity saving throw or take 14 (2d4 + 9) bludgeoning damage and be knocked prone. Niv-Mizzet can then fly up to half his flying speed.

**Dracogenius (Costs 3 Actions).** Niv-Mizzet regains a spell slot of 3rd level or lower.


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