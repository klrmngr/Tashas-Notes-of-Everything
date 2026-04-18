---
type: pc
race: "Humanoid (gnome)"
class:
 - "Flimp Shagglecran"
subClass:
 - "CR 9"
cover: "Flimp Shagglecran.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/9
  - source/mabjov
---
###### Flimp Shagglecran
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Flimp Shagglecran.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 21 (+2 plate, cloak of protection) |
> | :FasHeart: HP | 137 (25d6 + 50) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 18 | 12 | 11 |
| **Mod** | +2 | +0 | +2 | +4 | +1 | +0 |

**Speed:** 25 ft., fly 25 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Dwarvish, Giant, Gnomish
**Saving Throws:** Con +6, Int +8
**Skills:** Arcana +8, History +8, Medicine +5

---

### Traits

**Battle Smith.** Flimp uses his Intelligence modifier for attack and damage rolls with his weapons.

**Gnome Cunning.** Flimp has advantage on all Intelligence, Wisdom, and Charisma Saving Throws against magic.

**Special Equipment.** Flimp wears a cloak of the manta ray, a cloak of protection, +2 plate armor, and winged boots. Flimp wields a +2 warhammer. These items vanish 4 days after Flimp dies.


---

### Actions

**Multiattack.** Flimp makes two Magic Warhammer attacks.

**Magic Warhammer.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage plus 3 (1d6) force damage.

**Hurl Acid (Recharge 6).** Flimp hurls a vial of acid at a location within 60 feet. Every creature within 10 feet of the target location must succeed on a DC 16 Dexterity saving throw or take 21 (6d6) acid damage.

**Summon Steel Defender (1/Day).** Flimp summons a metallic panther to aid him in combat. The panther has 24 hit points and is immune to poison damage and the poison and charmed conditions.


---

### Reactions

**Flash of Genius.** When Flimp or another creature he can see within 30 feet of him makes an ability check or a saving throw, Flimp can use his reaction to add +4 to the roll.


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