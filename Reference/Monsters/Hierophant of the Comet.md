---
type: pc
race: "Humanoid (warlock)"
class:
 - "Hierophant of the Comet"
subClass:
 - "CR 11"
cover: "Hierophant of the Comet.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/bmt
---
###### Hierophant of the Comet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Hierophant of the Comet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (warlock) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 18 | 15 | 17 | 20 |
| **Mod** | +1 | +1 | +4 | +2 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 13
**Languages:** Common plus any two languages, telepathy 60 ft.
**Saving Throws:** Wis +7, Cha +9
**Skills:** Arcana +10, Deception +9, Persuasion +9, Religion +6
**Damage Resistances:** psychic

---

### Traits

**Comet's Voice (1/Day).** The hierophant can cast Contact Other Plane, using Charisma as the spellcasting ability.

**Magic Resistance.** The hierophant has advantage on saving throws against spells and other magical effects.

**Thought Shield.** The hierophant's thoughts can't be read by any means unless the hierophant allows it.


---

### Actions

**Multiattack.** The hierophant makes two Herald's Axe attacks or three Comet Blast attacks.

**Herald's Axe.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 11 (1d12 + 5) slashing damage plus 10 (3d6) necrotic damage.

**Comet Blast.** Ranged Spell Attack: +9 to hit, range 120 ft., one target. *Hit:* 16 (2d10 + 5) force damage.

**All-Consuming Star (Recharge 6).** The hierophant conjures a manifestation of the All-Consuming Star: brilliant light and haunting screams that fill a 20-foot-radius sphere centered on a point the hierophant can see within 60 feet of itself. Each creature within the sphere has the blinded and deafened conditions. Each creature that enters the sphere for the first time on a turn or starts its turn there must make a DC 17 Wisdom saving throw. On a failed save, a creature takes 27 (6d8) psychic damage and has the incapacitated condition until the start of its next turn. On a successful save, a creature takes half as much damage only. The manifestation persists until the hierophant dies, has the incapacitated condition, uses a bonus action to end the effect, or uses this action again.


---

### Bonus Actions

**Star's Hunger.** The hierophant targets one creature within 30 feet of the center of its All-Consuming Star. The target must succeed on a DC 17 Strength saving throw or be pulled up to 30 feet toward the center of the All-Consuming Star.


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