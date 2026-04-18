---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Malaxxix"
subClass:
 - "CR 18"
cover: "Malaxxix.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/18
  - source/bmt
---
###### Malaxxix
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Malaxxix.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (yugoloth) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 312 (25d12 + 150) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 22 | 22 | 20 | 18 |
| **Mod** | +6 | +3 | +6 | +6 | +5 | +4 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Abyssal, Infernal, telepathy 120 ft.
**Saving Throws:** Str +12, Con +12
**Skills:** Arcana +12, Athletics +12, Perception +11
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Malaxxix fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Malaxxix has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Malaxxix makes two Forge Hammer or Whip attacks in any combination.

**Forge Hammer.** Melee or Ranged Weapon Attack: +12 to hit, reach 10 ft. or range 60/180 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage, and the target can't take reactions until the end of Malaxxix's next turn. The hammer then magically returns to Malaxxix's hand.

**Whip.** Melee Weapon Attack: +12 to hit, reach 30 ft., one creature. *Hit:* 15 (2d8 + 6) slashing damage, and the target has the restrained condition for 1 minute. The restrained target can make a DC 20 Strength saving throw at the end of each of its turns, ending the effect on itself on a success. Only one creature can be restrained by the whip at a time.

**Mezzoloth Vortex (Recharge 5–6).** Malaxxix summons a vortex of whirling mezzoloths at a point it can see within 90 feet of itself. The vortex is a 30-foot-radius, 100-foot-high cylinder centered on that point. Each creature other than Malaxxix in that area must make a DC 20 Dexterity saving throw. On a failed save, a creature takes 35 (10d6) force damage and has the restrained condition while within the cylinder. On a successful save, a creature takes half as much damage and is pushed to the nearest unoccupied space outside the cylinder. The vortex lasts until the start of Malaxxix's next turn.


---

### Legendary Actions

### 

**Fiendish Stride.** Malaxxix moves up to its speed. This movement doesn't provoke opportunity attacks. When Malaxxix moves within 5 feet of a creature during this movement, that creature takes 5 (1d10) lightning damage. A creature can take this damage only once per turn.

**Attack (Costs 2 Actions).** Malaxxix makes one Forge Hammer or Whip attack.


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