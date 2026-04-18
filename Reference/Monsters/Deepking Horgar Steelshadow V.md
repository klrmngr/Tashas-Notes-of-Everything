---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Deepking Horgar Steelshadow V"
subClass:
 - "CR 3"
cover: "Deepking Horgar Steelshadow V.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/oota
---
###### Deepking Horgar Steelshadow V
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Deepking Horgar Steelshadow V.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (dwarven plate) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 14 | 11 | 11 | 15 |
| **Mod** | +4 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Draconic, Giant, Dwarvish
**Saving Throws:** Con +4, Wis +2

---

### Traits

**Duergar Resilience.** Horgar has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sunlight Sensitivity.** While in sunlight, Horgar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Gauntlets of Ogre Power.** Horgar wields Gauntlets of Ogre Power giving him a Strength score of 19 (+4).

**Brave.** Horgar has advantage on saving throws against being frightened.


---

### Actions

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, Horgar magically increases in size, along with anything he is wearing or carrying. While enlarged, Horgar is Large, doubles his damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If Horgar lacks the room to become Large, he attains the maximum size possible in the space available.

**Invisibility (Recharges after a Short or Long Rest).** Horgar magically turns invisible until he attacks, casts a spell, or uses his Enlarge, or until his concentration is broken, up to 1 hour (as if concentrating on a spell). Any equipment Horgar wears or carries is invisible with him.

**Multiattack.** Horgar makes two melee attacks.

**+2 Warhammer.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage, or 11 (1d10 + 6) bludgeoning damage if used with two hands. While Horgar is enlarged, the damage increases to 15 (2d8 + 6) or 17 (2d10 + 6) bludgeoning damage, respectively.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage.

**Leadership (Recharges after a Short or Long Rest).** For 1 minute, Horgar can utter a special command or warning whenever a nonhostile creature that he can see within 30 feet of Horgar makes an attack roll or a saving throw. The creature can add a d4 to its roll provided it can hear and understand Horgar. A creature can benefit from only one Leadership die at a time. This effect ends if Horgar is incapacitated.


---

### Reactions

**Parry.** Horgar adds 2 to its AC against one melee attack that would hit him. To do so, Horgar must see the attacker and be wielding a melee weapon.


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