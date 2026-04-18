---
type: pc
race: "Fiend (devil)"
class:
 - "Hulgaz"
subClass:
 - "CR 14"
cover: "Hulgaz.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/14
  - source/bmt
---
###### Hulgaz
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Hulgaz.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 190 (20d10 + 80) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 18 | 14 | 15 | 20 |
| **Mod** | +3 | +0 | +4 | +2 | +2 | +5 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Wis +7, Cha +10
**Skills:** Deception +10, Insight +7, Perception +7, Persuasion +10
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Hulgaz fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Hulgaz has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Hulgaz makes two Claw attacks and one Intoxicating Sting attack.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage.

**Intoxicating Sting.** Melee Weapon Attack: +8 to hit, reach 10 ft., one creature. *Hit:* 8 (1d10 + 3) piercing damage plus 10 (3d6) poison damage, and the target must succeed on a DC 17 Wisdom saving throw or have the charmed condition until the start of Hulgaz's next turn.

**Brimstone Vapor (Recharge 5–6).** Hulgaz exhales a 30-foot cone of noxious, scorching-hot vapor. Each creature in that area must succeed on a DC 17 Constitution saving throw or have the poisoned condition for 1 minute. While poisoned in this way, a creature takes 31 (7d8) fire damage at the start of each of its turns and has disadvantage on Wisdom saving throws. A target can repeat the Constitution saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Attack.** Hulgaz makes one Claw attack.

**Charm.** Hulgaz uses Spellcasting to cast Charm Person.

**Curdle Heart (Costs 2 Actions).** Hulgaz sours the good feelings of her charmed victims. She chooses any number of creatures she can see who are charmed by her. Each target takes 17 (5d6) psychic damage as the charmed condition applied by Hulgaz ends on it.


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