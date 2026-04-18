---
type: pc
race: "Undead"
class:
 - "Miirym"
subClass:
 - "CR 22"
cover: "Miirym.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/22
  - source/cm
---
###### Miirym
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Miirym.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 262 (25d10 + 125) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 20 | 18 | 15 | 23 |
| **Mod** | +3 | +0 | +5 | +4 | +2 | +6 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft.; see also "x-ray vision" below, passive Perception 26
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Con +12, Int +11, Wis +9, Cha +13
**Skills:** Arcana +11, History +11, Perception +16, Stealth +14
**Damage Resistances:** acid; fire; lightning; thunder
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; poisoned; prone; restrained

---

### Traits

**Bound to Candlekeep.** Miirym can't leave Candlekeep and is immune to any effect that would place her in a location outside it, including an extradimensional space. If she dies, Miirym regains her form and all her hit points after 1d10 days, reappearing in the location where she died or in the nearest unoccupied space.

**Regeneration.** Miirym regains 40 hit points at the start of her turn. If Miirym takes damage from a magic weapon or a spell, this trait doesn't function at the start of Miirym's next turn. Miirym dies only if she starts her turn with 0 hit points and doesn't regenerate.

**Incorporeal Movement.** Miirym can move through other creatures and objects as if they were 3. She takes 5 (1d10) force damage if she ends her turn inside an object.

**Legendary Resistance (3/Day).** If Miirym fails a saving throw, she can choose to succeed instead.

**X-Ray Vision.** Miirym can see through solid matter out to a range of 60 feet. To her, opaque creatures, objects, and obstacles within that distance appear transparent and don't prevent light from passing through them. This vision can penetrate 5 feet of stone, 3 inches of common metal, and up to 10 feet of wood or dirt. Thicker substances block this vision, as does a thin sheet of lead.


---

### Actions

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 34 (9d6 + 3) force damage.

**Breath Weapon (Recharge 5–6).** Miirym uses one of the following breath weapons:

**Cold Breath.** Miirym exhales an icy blast in a 90-foot cone. Each creature in that area must make a DC 21 Constitution saving throw, taking 67 (15d8) cold damage on a failed save, or half as much damage on a successful one.

**Necrotic Breath.** Miirym exhales a bolt of necrotic energy in a 120-foot line that is 10 feet wide. Each creature in that line must make a DC 21 Dexterity saving throw, taking 82 (15d10) necrotic damage on a failed save, or half as much damage on a successful one.

**Paralyzing Breath.** Miirym exhales paralyzing gas in a 90-foot cone. Each creature in that area must succeed on a DC 21 Constitution saving throw or be paralyzed for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Frightful Presence.** Each creature of Miirym's choice that is within 120 feet of her and aware of her must succeed on a DC 21 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Miirym's Frightful Presence for the next 24 hours.


---

### Legendary Actions

### 

**Bite.** Miirym makes a bite attack.

**Teleport (Costs 2 Actions).** Miirym magically teleports up to 120 feet to an unoccupied space she can see.


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