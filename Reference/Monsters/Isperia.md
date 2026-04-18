---
type: pc
race: "Monstrosity"
class:
 - "Isperia"
subClass:
 - "CR 21"
cover: "Isperia.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/21
  - source/ggr
---
###### Isperia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Isperia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 261 (18d20 + 72) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 23 | 26 | 20 |
| **Mod** | +5 | +2 | +4 | +6 | +8 | +5 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 25
**Languages:** Common, Sphinx
**Saving Throws:** Dex +9, Con +11, Int +13, Wis +15
**Skills:** Arcana +13, History +13, Insight +15, Perception +15
**Damage Immunities:** psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** Isperia is immune to any effect that would sense her emotions or read her thoughts, as well as any divination spell that she refuses. Wisdom (Insight) checks made to ascertain her intentions or sincerity have disadvantage.

**Legendary Resistance (3/Day).** If Isperia fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Isperia has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Isperia makes two claw attacks. She can cast a spell with a casting time of 1 action in place of one claw attack.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 21 (3d10 + 5) slashing damage. If the target is a creature, it must succeed on a DC 23 Wisdom saving throw or take 14 (4d6) psychic damage after each attack it makes against Isperia before the start of her next turn.

**Supreme Legal Authority.** Isperia chooses up to three creatures she can see within 90 feet of her. Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses an action for that target: Attack, Cast a Spell, Dash, Disengage, Dodge, Help, Hide, Ready, Search, or Use an Object. The affected target can't take that action for 1 minute. At the end of each of the target's turns, it can end the effect on itself with a successful DC 23 Intelligence saving throw. A target that succeeds on the saving throw becomes immune to Isperia's Supreme Legal Authority for 24 hours.


---

### Legendary Actions

### 

**Claw Attack.** Isperia makes one claw attack.

**Cast a Spell (Costs 2 Actions).** Isperia casts a spell of 3rd level or lower from her list of prepared spells, using a spell slot as normal.

**Supreme Legal Authority (Costs 3 Actions).** Isperia uses Supreme Legal Authority.


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