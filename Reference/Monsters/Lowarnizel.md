---
type: pc
race: "Dragon (young gem)"
class:
 - "Lowarnizel"
subClass:
 - "CR 9"
cover: "Lowarnizel.png"
campaign:
locations:
tags:
  - race/young gem
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/pabtso
---
###### Lowarnizel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Lowarnizel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon (young gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 168 (16d10 + 80) |
> | :FasUserGroup: Race | Dragon (young gem) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 21 | 18 | 15 | 19 |
| **Mod** | +5 | +1 | +5 | +4 | +2 | +4 |

**Speed:** 40 ft., fly 80 ft. ((hover)), swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 20
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +5, Con +9, Wis +6, Cha +8
**Skills:** Arcana +12, Perception +10, Persuasion +8, Stealth +5
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened; prone

---

### Traits

**Amphibious.** Lowarnizel can breathe both air and water.


---

### Actions

**Multiattack.** Lowarnizel makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 4 (1d8) force damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.

**Singularity Breath (Recharge 5–6).** Lowarnizel creates a shining bead of gravitational force, then releases the energy in a 30-foot cone. Each creature in that area must make a DC 17 Strength saving throw. On a failed save, a creature takes 36 (8d8) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, a creature takes half as much damage only.


---

### Bonus Actions

**Change Shape.** Lowarnizel magically transforms into any creature that is Medium or Small, while retaining his game statistics (other than his size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.


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