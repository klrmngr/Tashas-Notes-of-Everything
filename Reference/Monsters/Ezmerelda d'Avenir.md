---
type: pc
race: "Humanoid (human)"
class:
 - "Ezmerelda d'Avenir"
subClass:
 - "CR 8"
cover: "Ezmerelda d'Avenir.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/cos
---
###### Ezmerelda d'Avenir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Ezmerelda d'Avenir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 (+1 studded leather armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 19 | 16 | 16 | 11 | 17 |
| **Mod** | +2 | +4 | +3 | +3 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Elvish
**Saving Throws:** Wis +3
**Skills:** Acrobatics +7, Arcana +6, Deception +9, Insight +3, Medicine +3, Perception +6, Performance +6, Sleight Of Hand +7, Stealth +7, Survival +6

---

### Traits

**Special Equipment.** In addition to her magic armor and weapons, Ezmerelda has two potions of greater healing, six vials of holy water, and three wooden stakes.


---

### Actions

**Multiattack.** Ezmerelda makes three attacks: two with her +1 rapier and one with her +1 handaxe or her silvered shortsword.

**Rapier +1.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Handaxe +1.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Silvered Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Curse (Recharges after a Long Rest).** Ezmerelda targets one creature that she can see within 30 feet of her. The target must succeed on a DC 14 Wisdom saving throw or be cursed. While cursed, the target has vulnerability to one type of damage of Ezmerelda's choice. The curse lasts until ended with a greater restoration spell, a remove curse spell, or similar magic. When the curse ends, Ezmerelda takes 3d6 psychic damage.

**Evil Eye (Recharges after a Short or Long Rest).** Ezmerelda targets one creature that she can see within 10 feet of her and casts one of the following spells on the target (save DC 14), requiring neither somatic nor material components to do so: animal friendship, charm person, or hold person. If the target succeeds on the initial saving throw, Ezmerelda is blinded until the end of her next turn. Once a target succeeds on a saving throw against this effect, it is immune to the Evil Eye power of all Vistani for 24 hours.


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