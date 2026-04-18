---
type: pc
race: "Undead"
class:
 - "Vampire Umbral Lord"
subClass:
 - "CR 15"
cover: "Vampire Umbral Lord.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/15
  - source/xmm
---
###### Vampire Umbral Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vampire Umbral Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 18 | 18 | 19 | 16 | 21 |
| **Mod** | +5 | +4 | +4 | +4 | +3 | +5 |

**Speed:** 40 ft., climb 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 23
**Languages:** Common plus three other languages
**Saving Throws:** Str +10, Dex +9, Wis +8, Cha +10
**Skills:** Arcana +9, Perception +13, Stealth +9
**Damage Immunities:** cold; necrotic
**Condition Immunities:** charmed; exhaustion

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the vampire fails a saving throw, it can choose to succeed instead.

**Shadow Escape.** If the vampire drops to 0 Hit Points outside its resting place, it teleports into its resting place unless it is in running water or sunlight. If it can't teleport, it is destroyed. Once inside its resting place, it has the Paralyzed condition for 1 hour, after which it regains 1 Hit Point.

**Vampire Weakness.** The vampire has these weaknesses:
- **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.
- **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.
- **Stake to the Heart.** If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition in its resting place, the vampire has the Paralyzed condition until the weapon is removed.
- **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack.** The vampire makes two attacks, using Grave Strike or Sickening Ray in any combination.

**Grave Strike.** m +10, reach 5 ft. *Hit:* 9 (1d8 + 5) Slashing damage plus 13 (3d8) Necrotic damage.

**Sickening Ray.** r +10, range 120 ft. *Hit:* 16 (2d10 + 5) Necrotic damage, and the target has the Poisoned condition until the start of the vampire's next turn.


---

### Bonus Actions

**Sanguine Drain.** con DC 18, one creature the vampire can see within 30 feet that isn't a Construct or an Undead.  14 (4d6) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the damage taken, and the vampire regains Hit Points equal to that amount.


---

### Legendary Actions

### 

**Umbral Strike.** The vampire moves up to half its Speed, and it makes one Grave Strike or Sickening Ray attack.


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