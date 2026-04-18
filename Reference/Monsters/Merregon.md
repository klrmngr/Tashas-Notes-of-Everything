---
type: pc
race: "Fiend (devil)"
class:
 - "Merregon"
subClass:
 - "CR 4"
cover: "Merregon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/mpmm
---
###### Merregon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Merregon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 6 | 12 | 8 |
| **Mod** | +4 | +2 | +3 | -2 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** understands Infernal but can't speak, telepathy 120 ft.
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the merregon's darkvision.

**Magic Resistance.** The merregon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The merregon makes three Halberd attacks.

**Halberd.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.


---

### Reactions

**Loyal Bodyguard.** When another Fiend within 5 feet of the merregon is hit by an attack roll, the merregon causes itself to be hit instead.


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