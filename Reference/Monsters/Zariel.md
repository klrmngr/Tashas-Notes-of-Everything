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
  - source/coa
---
###### Zariel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
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
> | :FasHeart: HP | 420 (29d10 + 261) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

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

**Legendary Resistance (3/Day).** If Zariel fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Zariel has advantage on saving throws against spells and other magical effects.

**Regeneration.** Zariel regains 20 hit points at the start of her turn. If she takes radiant damage, this trait doesn't function at the start of her next turn. Zariel dies only if she starts her turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Zariel makes three Flail or Longsword attacks. She can replace one attack with a use of Horrid Touch, if available.

**Flail.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) force damage plus 36 (8d8) fire damage.

**Longsword.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) radiant damage or 19 (2d10 + 8) radiant damage when used with two hands, plus 36 (8d8) fire damage.

**Horrid Touch (Recharge 5–6).** Zariel touches one creature within 10 feet of her. The target must succeed on a DC 26 Constitution saving throw or take 44 (8d10) necrotic damage and have the poisoned condition for 1 minute. While poisoned in this way, the target has the blinded and deafened conditions. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Teleport.** Zariel magically teleports, along with any equipment she is wearing or carrying, up to 120 feet to an unoccupied space she can see.


---

### Legendary Actions

### 

**Teleport.** Zariel uses Teleport.

**Immolating Gaze (Costs 2 Actions).** Zariel turns her magical gaze toward one creature she can see within 120 feet of her and commands it to burn. The target must succeed on a DC 26 Wisdom saving throw or take 22 (4d10) fire damage.


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