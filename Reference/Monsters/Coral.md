---
type: pc
race: "Fey"
class:
 - "Coral"
subClass:
 - "CR 9"
cover: "Coral.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/9
  - source/mismv1
---
###### Coral
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Coral.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 15 | 14 | 18 | 19 |
| **Mod** | +5 | +1 | +2 | +2 | +4 | +4 |

**Speed:** 10 ft., fly 60 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 18
**Languages:** Common, Primordial, Sylvan
**Saving Throws:** Dex +5, Con +6, Wis +8, Cha +8
**Skills:** Arcana +6, Insight +8, Perception +8
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** Coral has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Coral makes two Hoof attacks and uses Tail Thump.

**Hoof.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage.

**Tail Thump.** Coral slams her tail down, unleashing a burst of magical force toward one creature she can see within 60 feet of her. The target must make a DC 16 Dexterity saving throw. On a failed save, the target takes 22 (4d10) force damage and has the prone condition. On a successful save, the target takes half as much damage only. If this damage reduces the target to 0 hit points, the target dies, and its body is reduced to fine dust.


---

### Bonus Actions

**Bubbles of Whimsy (2/Day).** Coral produces a stream of magical bubbles from her horn. These bubbles float toward a creature Coral can see within 60 feet of herself. Roll a d6 to determine the bubbles' effect:
- **1-2: Bolstering Treat.** The bubbles transform into 1d4 cookies that appear in the target's space. The target gains 11 (2d8 + 2) temporary hit points if it immediately uses its reaction to eat one of the cookies. Any leftover cookies are delicious but confer no benefits.
- **3-4: Sparkle Burst.** The bubbles transform into glitter that swirls around the target before bursting outward. Each creature within 5 feet of the target must succeed on a DC 16 Constitution saving throw or have the blinded condition until the start of Coral's next turn.
- **5-6: Stink Bomb Shield.** The bubbles transform into a foul-smelling cloud of gas that surrounds and shields the target. The target has 3 until the gas disappears at the start of Coral's next turn.

**Gift of Speech (1/Day).** Coral targets one Beast she can see within 10 feet of herself. The target gains the ability to understand and speak Common or Sylvan (Coral's choice) for 10 minutes.


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