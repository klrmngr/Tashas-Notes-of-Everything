---
type: pc
race: "Undead"
class:
 - "Gnoll Witherling"
subClass:
 - "CR 1/4"
cover: "Gnoll Witherling.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1-4
  - source/mpmm
---
###### Gnoll Witherling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Gnoll Witherling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 8 | 12 | 5 | 5 | 5 |
| **Mod** | +2 | -1 | +1 | -3 | -3 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 7
**Languages:** understands Gnoll but can't speak
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Unusual Nature.** The witherling doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The witherling makes two Bite or Spiked Club attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) necrotic damage.

**Spiked Club.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


---

### Bonus Actions

**Rampage.** After the witherling reduces a creature to 0 hit points with a melee attack on its turn, the gnoll moves up to half its speed and makes one Bite attack.


---

### Reactions

**Vengeful Strike.** In response to a gnoll being reduced to 0 hit points within 30 feet of the witherling, the witherling makes one Bite or Spiked Club attack.


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