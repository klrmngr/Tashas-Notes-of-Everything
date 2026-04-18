---
type: pc
race: "Fiend (devil)"
class:
 - "Zariel"
subClass:
 - "CR 26"
cover: "Zariel.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/26
  - source/mtf
---
###### Zariel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Zariel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 580 (40d10 + 360) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 24 | 28 | 26 | 27 | 30 |
| **Mod** | +8 | +7 | +9 | +8 | +8 | +10 |

**Speed:** 50 ft., fly 150 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 26
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +16, Wis +16, Cha +18
**Skills:** Intimidation +18, Perception +16
**Damage Resistances:** cold; fire; radiant; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Zariel's darkvision.

**Magic Weapons.** Zariel's weapon attacks are magical. When she hits with any weapon, the weapon deals an extra 36 (8d8) fire damage (included in the weapon attacks below).

**Legendary Resistance (3/Day).** If Zariel fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Zariel has advantage on saving throws against spells and other magical effects.

**Regeneration.** Zariel regains 20 hit points at the start of her turn. If she takes radiant damage, this trait doesn't function at the start of her next turn. Zariel dies only if she starts her turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Zariel attacks twice with her longsword or with her javelins. She can substitute Horrid Touch for one of these attacks.

**Longsword.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) slashing damage plus 36 (8d8) fire damage, or 19 (2d10 + 8) slashing damage plus 36 (8d8) fire damage if used with two hands.

**Javelin.** Melee or Ranged Weapon Attack: +16 to hit, reach 10 ft. or range 30/120 ft., one target. *Hit:* 15 (2d6 + 8) piercing damage plus 36 (8d8) fire damage.

**Horrid Touch (Recharge 5–6).** Zariel touches one creature within 10 feet of her. The target must succeed on a DC 26 Constitution saving throw or take 44 (8d10) necrotic damage and be poisoned for 1 minute. While poisoned in this way, the target is also blinded and deafened. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Teleport.** Zariel magically teleports, along with any equipment she is wearing and carrying, up to 120 feet to an unoccupied space she can see.


---

### Legendary Actions

### 

**Immolating Gaze (Costs 2 Actions).** Zariel turns her magical gaze toward one creature she can see within 120 feet of her and commands it to combust. The target must succeed on a DC 26 Wisdom saving throw or take 22 (4d10) fire damage.

**Teleport.** Zariel uses her Teleport action.


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