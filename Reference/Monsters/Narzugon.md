---
type: pc
race: "Fiend (devil)"
class:
 - "Narzugon"
subClass:
 - "CR 13"
cover: "Narzugon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/mpmm
---
###### Narzugon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Narzugon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 17 | 16 | 14 | 19 |
| **Mod** | +5 | +0 | +3 | +3 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 22
**Languages:** Common, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +5, Con +8, Cha +9
**Skills:** Perception +12
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Infernal Tack.** The narzugon wears spurs that are part of infernal tack, which allow it to summon its nightmare companion as an action.

**Magic Resistance.** The narzugon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The narzugon makes three Hellfire Lance attacks. It also uses Infernal Command or Terrifying Command.

**Hellfire Lance.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 11 (1d12 + 5) piercing damage plus 16 (3d10) fire damage. If this damage kills a creature with a soul, the soul rises from the River Styx as a lemure in Avernus in 1d4 hours. If the creature isn't revived before then, only a wish spell or killing the lemure and casting true resurrection on the creature's original body can restore it to life. Constructs and devils are immune to this effect.

**Infernal Command.** Each ally of the narzugon within 60 feet of it can't be charmed or frightened until the end of the narzugon's next turn.

**Terrifying Command.** Each creature within 60 feet of the narzugon that isn't a Fiend must succeed on a DC 17 Charisma saving throw or become frightened of the narzugon for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that makes a successful saving throw is immune to this narzugon's Terrifying Command for 24 hours.

**Healing (1/Day).** The narzugon, or one creature it touches, regains 100 hit points.


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