---
type: pc
race: "Fiend (demon)"
class:
 - "Master of Cruelties"
subClass:
 - "CR 9"
cover: "Master of Cruelties.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/ggr
---
###### Master of Cruelties
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Master of Cruelties.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 17 | 16 | 19 | 16 | 21 |
| **Mod** | +4 | +3 | +3 | +4 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Con +7, Int +8, Wis +7, Cha +9
**Skills:** Deception +9, Intimidation +9, Performance +9, Persuasion +9
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Aura of Blood Lust.** When any other creature starts its turn within 30 feet of the master, that creature must succeed on a DC 17 Wisdom saving throw, or it must immediately take the Attack action, making one melee attack against a random creature within reach. If no creatures are within reach, it makes a ranged attack against a random creature within range, throwing its weapon if necessary.

**Feed on the Crowd.** Whenever a creature within 60 feet of the master dies, the master gains 15 temporary hit points and has advantage on all attack rolls, ability checks, and saving throws until the end of its next turn.

**Magic Resistance.** The master has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The master makes two melee attacks with its spear.

**Spear.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack, plus 13 (3d8) psychic damage.

**Captivating Presence (Recharge 6).** Each creature within 120 feet of the master must succeed on a DC 17 Wisdom saving throw or be charmed by the master for 1 hour. While charmed in this way, a creature's speed is 0. If the charmed creature takes damage, it can repeat the saving throw, ending the effect on itself on a success. A target that succeeds on the saving throw is immune to the Captivating Presence of all masters of cruelties for the next 24 hours.


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