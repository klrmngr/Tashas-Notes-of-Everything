---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Shemeshka"
subClass:
 - "CR 14"
cover: "Shemeshka.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/14
  - source/mpp
---
###### Shemeshka
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Shemeshka.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 162 (25d8 + 50) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 14 | 21 | 16 | 18 |
| **Mod** | +5 | +2 | +2 | +5 | +3 | +4 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +7, Int +10, Wis +8, Cha +9
**Skills:** Deception +9, Insight +8, Perception +8
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Legendary Resistance (4/Day).** If Shemeshka fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Shemeshka has advantage on saving throws against spells and other magical effects.

**Special Equipment.** Shemeshka carries a magic crown called the Razorvine Tiara. In the hands of anyone other than Shemeshka, the Razorvine Tiara functions as a tentacle rod that deals slashing damage instead of bludgeoning damage.


---

### Actions

**Multiattack.** Shemeshka uses Arcane Flux or Spellcasting. She then makes one Claw attack or one attack with her Razorvine Tiara.

**Arcane Flux.** Shemeshka causes a surge of arcane energy to burst around one creature she can see within 120 feet of herself. The target must make a DC 18 Dexterity saving throw. On a failed save, the target takes 45 (7d12) force damage and has the incapacitated condition until the end of its next turn. On a successful save, the target takes half as much damage only.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (2d4 + 5) slashing damage plus 14 (4d6) poison damage.

**Razorvine Tiara.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 10 (3d6) slashing damage plus 9 (2d8) necrotic damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw, or its speed is halved and it has disadvantage on attack rolls and saving throws until the end of its next turn.


---

### Bonus Actions

**Teleport.** Shemeshka teleports, along with any equipment she is wearing or carrying, up to 60 feet to an unoccupied space she can see.


---

### Reactions

**Fell Counterspell (3/Day).** Shemeshka utters a magical word to interrupt a creature she can see that is casting a spell. If the spell is 5th level or lower, it fails and has no effect. If the spell is 6th level or higher, Shemeshka makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect. Whatever the spell's level, the caster gains the poisoned condition until the end of its next turn.


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