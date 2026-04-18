---
type: pc
race: "Giant (wizard)"
class:
 - "Stone Giant Rockspeaker"
subClass:
 - "CR 16"
cover: "Stone Giant Rockspeaker.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/16
  - source/bgg
---
###### Stone Giant Rockspeaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Stone Giant Rockspeaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Giant (wizard) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 276 (24d12 + 120) |
> | :FasUserGroup: Race | Giant (wizard) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 20 | 19 | 14 | 10 |
| **Mod** | +6 | +2 | +5 | +4 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Common, Giant, Terran
**Saving Throws:** Dex +7, Con +10, Int +9, Wis +7
**Skills:** Athletics +16, History +9, Perception +7

---

### Traits

**Legendary Resistance (3/Day).** If the giant fails a saving throw, it can choose to succeed instead.

**Stone Rune.** The giant has a stone rune inscribed on a mineral object in its possession. While holding or wearing the object bearing the rune, the giant can use its Prismatic Rays action.
The object bearing the rune has AC 18; 30 hit points; and immunity to necrotic, poison, and psychic damage. The object regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the giant dies. If the rune is destroyed, the giant can inscribe a stone rune on an object in its possession when it finishes a short or long rest.


---

### Actions

**Multiattack.** The giant makes three Prism Staff attacks.

**Prism Staff.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage plus 13 (3d8) radiant damage.

**Exploding Geode.** The giant throws a geode at a point within 60 feet of itself, and the geode explodes in a dazzling flash. Each creature in a 20-foot-radius sphere centered on that point must make a DC 17 Dexterity saving throw. On a failed save, a creature takes 13 (3d8) piercing damage plus 13 (3d8) radiant damage and has the blinded condition until the end of its next turn. On a successful save, a creature takes half as much damage only. After the giant throws the geode, roll a d6; on a roll of 4 or lower, the giant has no more geodes to throw.

**Prismatic Rays (Requires Stone Rune).** The giant's stone rune emits beams of light that form a 60-foot cone. Each creature in that area must make a DC 17 Dexterity saving throw. For each creature in that area, roll a d6 to determine what ray affects it:

**1-2: Blazing Red.** On a failed save, the creature takes 35 (10d6) radiant damage and has the blinded condition until the end of the giant's next turn. On a successful save, the creature takes half as much damage only.

**3-4: Dreadful Blue.** On a failed save, the creature takes 35 (10d6) necrotic damage and has the frightened condition until the end of the giant's next turn. On a successful save, the creature takes half as much damage only.

**5-6: Sapping Green.** On a failed save, the creature takes 35 (10d6) force damage and has the incapacitated condition until the end of the giant's next turn. On a successful save, the creature takes half as much damage only.


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