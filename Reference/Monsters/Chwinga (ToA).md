---
type: pc
race: "Elemental"
class:
 - "Chwinga"
subClass:
 - "CR 0"
cover: "Chwinga.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/tiny
  - cr/0
  - source/toa
---
###### Chwinga
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Chwinga.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Elemental |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 5 (2d4) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 20 | 10 | 14 | 16 | 16 |
| **Mod** | -5 | +5 | +0 | +2 | +3 | +3 |

**Speed:** 20 ft., climb 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 17
**Languages:** —
**Skills:** Acrobatics +7, Perception +7, Stealth +7

---

### Traits

**Unusual Nature.** The chwinga doesn't require air, food, or drink. When it dies, it turns into a handful of flower petals, a cloud of pollen, a stone statuette resembling its former self, a tiny sphere of smooth stone, or a puddle of fresh water (your choice).

**Evasion.** When the chwinga is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.


---

### Actions

**Magical Gift (1/Day).** The chwinga targets a humanoid it can see within 5 feet of it. The target gains a type=charm of the DM's choice. See 7 of the Dungeon Masters Guide for more information on supernatural charms.

**Natural Shelter.** The chwinga magically takes shelter inside a rock, a living plant, or a natural source of fresh water in its space. The chwinga can't be targeted by any attack, spell, or other effect while inside this shelter, and the shelter doesn't impair the chwinga's blindsight. The chwinga can use its action to emerge from a shelter. If its shelter is destroyed, the chwinga is forced out and appears in the shelter's space, but is otherwise unharmed.


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