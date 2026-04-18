---
type: pc
race: "Fiend (demon)"
class:
 - "Molydeus"
subClass:
 - "CR 21"
cover: "Molydeus.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/21
  - source/mtf
---
###### Molydeus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Molydeus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 216 (16d12 + 112) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 22 | 25 | 21 | 24 | 24 |
| **Mod** | +9 | +6 | +7 | +5 | +7 | +7 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 31
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +16, Con +14, Wis +14, Cha +14
**Skills:** Perception +21
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; frightened; poisoned; stunned

---

### Traits

**Legendary Resistance (3/Day).** If the molydeus fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The molydeus has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The molydeus' weapon attacks are magical.


---

### Actions

**Multiattack.** The molydeus makes three attacks: one with its weapon, one with its wolf bite, and one with its snakebite.

**Demonic Weapon.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) slashing damage. If the target has at least one head and the molydeus rolled a 20 on the attack roll, the target is decapitated and dies if it can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 6d8 slashing damage from the hit.

**Wolf Bite.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 16 (2d6 + 9) piercing damage.

**Snakebite.** Melee Weapon Attack: +16 to hit, reach 15 ft., one creature. *Hit:* 12 (1d6 + 9) piercing damage, and the target must succeed on a DC 22 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target transforms into a manes if this reduces its hit point maximum to 0. This transformation can be ended only by a wish spell.


---

### Legendary Actions

### 

**Attack.** The molydeus makes one attack, either with its demonic weapon or with its snakebite.

**Move.** The molydeus moves without provoking opportunity attacks.

**Cast a Spell.** The molydeus casts one spell from its Innate Spellcasting trait.


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