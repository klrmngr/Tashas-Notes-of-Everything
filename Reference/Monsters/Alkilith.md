---
type: pc
race: "Fiend (demon)"
class:
 - "Alkilith"
subClass:
 - "CR 11"
cover: "Alkilith.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/11
  - source/mpmm
---
###### Alkilith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Alkilith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 168 (16d8 + 96) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 22 | 6 | 11 | 7 |
| **Mod** | +1 | +4 | +6 | -2 | +0 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Abyssal but can't speak
**Saving Throws:** Dex +8, Con +10
**Skills:** Stealth +8
**Damage Resistances:** acid; cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Abyssal Rift.** If the alkilith surrounds a door, window, or similar opening continuously for 6d6 days, the opening becomes a permanent portal to a random layer of the Abyss.

**Amorphous.** The alkilith can move through a space as narrow as 1 inch wide without squeezing.

**False Appearance.** If the alkilith is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the alkilith move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the alkilith isn't ordinary slime or fungus.

**Foment Confusion.** Any creature that isn't a demon that starts its turn within 30 feet of the alkilith must succeed on a DC 18 Wisdom saving throw, or it hears a faint buzzing in its head for a moment and has disadvantage on its next attack roll, saving throw, or ability check.
If the saving throw against Foment Confusion fails by 5 or more, the creature is instead subjected to the confusion spell for 1 minute (no concentration required by the alkilith). While under the effect of that confusion, the creature is immune to Foment Confusion.

**Magic Resistance.** The alkilith has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The alkilith can climb difficult surfaces, such as upside down on ceilings, without making an ability check.

**Unusual Nature.** The alkilith doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The alkilith makes three Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 15 ft., one target. *Hit:* 18 (4d6 + 4) acid damage.


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