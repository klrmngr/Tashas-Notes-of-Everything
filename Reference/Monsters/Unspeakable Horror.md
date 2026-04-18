---
type: pc
race: "Monstrosity"
class:
 - "Unspeakable Horror"
subClass:
 - "CR 8"
cover: "Unspeakable Horror.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/8
  - source/vrgr
---
###### Unspeakable Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Unspeakable Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor); 17 (Aberrant Armor Only) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 13 | 19 | 3 | 14 | 17 |
| **Mod** | +5 | +1 | +4 | -4 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Con +7, Wis +5
**Skills:** Perception +5

---

### Traits

**Formed by the Mists.** When created, the horror's body composition takes one of four forms: Aberrant Armor, Loathsome Limbs, Malleable Mass, or Oozing Organs. This form determines certain traits in this stat block.

**Amorphous (Malleable Mass Only).** The horror can move through any opening at least 1 inch wide without squeezing.

**Bile Body (Oozing Organs Only).** Any creature that touches the horror or hits it with a melee attack takes 5 (1d10) acid damage.

**Relentless Stride (Loathsome Limbs Only).** The horror can move through the space of another creature. The first time on a turn that the horror enters a creature's space during this move, the creature must succeed on a DC 16 Strength saving throw or be knocked prone.


---

### Actions

**Multiattack.** The horror makes two Limbs attacks.

**Limbs.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 21 (3d10 + 5) bludgeoning damage.

**Hex Blast (Recharge 5–6).** The horror expels necrotic energy in a 30-foot cone. Each creature in that area must make a DC 15 Constitution saving throw, taking 45 (7d12) necrotic damage on a failed save, or half as much damage on a successful one.


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