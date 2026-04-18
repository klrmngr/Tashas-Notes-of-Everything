---
type: pc
race: "Fiend (demon)"
class:
 - "Echo of Demogorgon"
subClass:
 - "CR 6"
cover: "Echo of Demogorgon.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/bgg
---
###### Echo of Demogorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Echo of Demogorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 17 | 10 | 12 | 14 |
| **Mod** | +6 | +0 | +3 | +0 | +1 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Giant, Orc
**Saving Throws:** Str +9, Cha +5
**Skills:** Perception +7
**Damage Resistances:** cold; fire; lightning
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Resistance.** The echo has advantage on saving throws against spells and other magical effects.

**Wakeful.** When one of the echo's heads is asleep, its other head is awake.


---

### Actions

**Multiattack.** The echo makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) bludgeoning damage plus 9 (2d8) necrotic damage.


---

### Bonus Actions

**Discordant Screams.** The echo directs its frenzied howls at one creature it can see within 60 feet of itself. The target must succeed on a DC 13 Wisdom saving throw or suffer one of the following effects of the echo's choice:
- **Confused Reaction.** The target must use its reaction to make a melee attack against another creature of the echo's choice that the echo can see.
- **Psychic Torment.** The target takes 13 (2d12) psychic damage.


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