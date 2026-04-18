---
type: pc
race: "Undead"
class:
 - "Gremorly's Ghost"
subClass:
 - "CR 9"
cover: "Gremorly's Ghost.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/9
  - source/bmt
---
###### Gremorly's Ghost
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Gremorly's Ghost.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 14 | 12 | 18 | 12 | 17 |
| **Mod** | -2 | +2 | +1 | +4 | +1 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Giant
**Saving Throws:** Int +8, Wis +5
**Skills:** Arcana +8, History +8
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Ethereal Sight.** Gremorly can see 60 feet into the Ethereal Plane when he is on the Material Plane, and vice versa.

**Incorporeal Movement.** Gremorly can move through other creatures and objects as if they were difficult terrain. He takes 5 (1d10) force damage if he ends his turn inside an object.

**Legendary Resistance (3/Day).** If Gremorly fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Gremorly makes three Withering Strike attacks.

**Withering Strike.** Melee Spell Attack: +8 to hit, reach 5 ft., one target. *Hit:* 19 (3d12) necrotic damage.

**Fell Necromancy.** Gremorly targets one creature he can see within 60 feet of himself. The target must make a DC 16 Constitution saving throw, taking 61 (7d8 + 30) necrotic damage on a failed save, or half as much damage on a successful one. In addition, Gremorly regains 9 (2d8) hit points.

**Possession (Recharge 6).** One Humanoid Gremorly can see within 5 feet of himself must succeed on a DC 15 Charisma saving throw or be possessed by him; Gremorly disappears, and the target has the incapacitated condition and loses control of its body. Gremorly can't be targeted by any attack, spell, or other effect, except ones that turn Undead, and he retains his alignment, Intelligence, Wisdom, Charisma, and immunity to the charmed and frightened conditions. He otherwise uses the target's game statistics, but Gremorly doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the target drops to 0 hit points, Gremorly ends it as a bonus action, or Gremorly is turned or forced out by an effect like the Dispel Evil and Good spell. When the possession ends, Gremorly reappears in an unoccupied space within 5 feet of the target. The target is immune to this Possession for 24 hours after succeeding on the saving throw or after the possession ends.


---

### Bonus Actions

**Ethereal Step (Recharge 4–6).** Gremorly teleports up to 30 feet to an unoccupied space he can see.


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