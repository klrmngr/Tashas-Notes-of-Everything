---
type: pc
race: "Undead"
class:
 - "Grim Champion of Pestilence"
subClass:
 - "CR 15"
cover: "Grim Champion of Pestilence.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/15
  - source/bmt
---
###### Grim Champion of Pestilence
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Grim Champion of Pestilence.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 16 | 17 | 15 | 21 |
| **Mod** | +0 | +4 | +3 | +3 | +2 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Infernal
**Saving Throws:** Dex +9, Cha +10
**Skills:** Arcana +8, Perception +7, Stealth +9
**Damage Resistances:** cold; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; poisoned; stunned; unconscious

---

### Traits

**Halo of Pestilence.** The champion is surrounded by an aura of deadly magic that takes the form of a host of glowing white insects. Each creature that starts its turn within 10 feet of the champion must succeed on a DC 18 Constitution saving throw or have the incapacitated condition until the start of its next turn, as the insects ravage its body.

**Legendary Resistance (3/Day).** If the champion fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The champion makes two Blight Staff attacks, two Plague Bolt attacks, or one of each.

**Blight Staff.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage plus 21 (6d6) necrotic damage.

**Plague Bolt.** Ranged Spell Attack: +10 to hit, range 120 ft., one target. *Hit:* 23 (4d8 + 5) poison damage, and the target has the poisoned condition until the start of the champion's next turn.


---

### Legendary Actions

### 

**Attack.** The champion makes one Blight Staff or Plague Bolt attack.

**Furious Pursuit.** The champion moves up to its speed or commands its mount to move up to its speed. This movement doesn't provoke opportunity attacks.

**Cast a Spell (Costs 2 Actions).** The champion uses Spellcasting.


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