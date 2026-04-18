---
type: pc
race: "Monstrosity (warlock)"
class:
 - "Yuan-ti Pit Master"
subClass:
 - "CR 5"
cover: "Yuan-ti Pit Master.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/mpmm
---
###### Yuan-ti Pit Master
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Yuan-ti Pit Master.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Monstrosity (warlock) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 12 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +4, Cha +6
**Skills:** Deception +6, Stealth +5
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the yuan-ti's darkvision.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes three Bite attacks or two Spectral Fangs attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.

**Spectral Fangs.** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 16 (3d8 + 3) poison damage.

**Merrshaulk's Slumber (1/Day).** The yuan-ti targets up to five creatures that it can see within 60 feet of it. Each target must succeed on a DC 13 Constitution saving throw or fall into a magical sleep and be unconscious for 10 minutes. A sleeping target awakens if it takes damage or if someone uses an action to shake or slap it awake. This magical sleep has no effect on a creature immune to being charmed.


---

### Bonus Actions

**Change Shape.** The yuan-ti transforms into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It doesn't change form if it dies.


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