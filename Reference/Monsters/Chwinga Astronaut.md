---
type: pc
race: "Elemental"
class:
 - "Chwinga Astronaut"
subClass:
 - "CR 0"
cover: "Chwinga Astronaut.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/tiny
  - cr/0
  - source/bam
---
###### Chwinga Astronaut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Chwinga Astronaut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Elemental |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 7 (3d4) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Boo's Astral Menagerie |

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

**Evasion.** When the chwinga is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails, provided it isn't incapacitated.

**Unusual Nature.** The chwinga doesn't require air, food, or drink. When it dies, it turns into a tiny pile of moondust, a cloud of glittering spores, a statuette resembling its former self, a chunk of ice, or a sponge shaped like a dodecahedron (DM's choice).


---

### Actions

**Magical Gift (1/Day).** The chwinga targets a Humanoid it can see within 5 feet of itself. The target gains a type=charm of the DM's choice. See 7 for more information on supernatural charms.

**Natural Shelter.** The chwinga takes shelter inside a rock, a bush, a tree, or a natural source of fresh water in its space. The chwinga can't be targeted by any attack, spell, or other effect while it is magically protected in this way, and the shelter doesn't impair the chwinga's blindsight. The chwinga can use its action to emerge from a shelter. If its shelter is destroyed, the chwinga is forced out and appears in the shelter's space, but is otherwise unharmed.


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