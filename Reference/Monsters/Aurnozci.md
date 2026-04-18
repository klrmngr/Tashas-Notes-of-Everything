---
type: pc
race: "Fiend (demon)"
class:
 - "Aurnozci"
subClass:
 - "CR 22"
cover: "Aurnozci.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/gargantuan
  - cr/22
  - source/bmt
---
###### Aurnozci
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Aurnozci.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Fiend (demon) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 370 (20d20 + 160) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 20 | 26 | 6 | 21 | 19 |
| **Mod** | +8 | +5 | +8 | -2 | +5 | +4 |

**Speed:** 50 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 15
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +15, Con +15
**Damage Resistances:** cold; lightning
**Damage Immunities:** acid; fire; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Heat Regeneration.** If the temperature around it is 100 degrees Fahrenheit or higher, Aurnozci regains 15 hit points at the start of its turn. If it takes cold or radiant damage, this trait doesn't function at the start of its next turn. Aurnozci dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Legendary Resistance (3/Day).** If Aurnozci fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Aurnozci has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Aurnozci makes one Bite attack and two Tail attacks.

**Bite.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 21 (2d12 + 8) slashing damage plus 9 (2d8) fire damage.

**Tail.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) bludgeoning damage.

**Mucus Spray (Recharge 5–6).** Aurnozci sprays mucus in a 60-foot cone. Each creature in that cone must make a DC 20 Dexterity saving throw, taking 42 (12d6) acid damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Move.** Aurnozci moves up to its speed.

**Tail.** Aurnozci makes one Tail attack.

**Cast a Spell (Costs 2 Actions).** Aurnozci uses Spellcasting.

**Conflagration (Costs 2 Actions).** Flames momentarily surround Aurnozci. Each creature within 15 feet of Aurnozci must make a DC 20 Dexterity saving throw, taking 18 (4d8) fire damage on a failed save, or half as much damage on a successful one.


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