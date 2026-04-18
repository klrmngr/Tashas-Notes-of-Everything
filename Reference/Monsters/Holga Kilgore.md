---
type: pc
race: "Humanoid"
class:
 - "Holga Kilgore"
subClass:
 - "CR 5"
cover: "Holga Kilgore.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hat-tg
---
###### Holga Kilgore
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Holga Kilgore.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 (Unarmored Defense) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 16 | 11 | 16 | 13 |
| **Mod** | +4 | +2 | +3 | +0 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Halfling
**Saving Throws:** Str +7, Con +6
**Skills:** Athletics +7, Intimidation +4, Nature +3, Survival +6
**Damage Resistances:** lightning (granted by darksteel greataxe)

---

### Traits

**Reckless.** At the start of her turn, Holga can gain advantage on melee weapon attack rolls during that turn, but attack rolls against her have advantage until the start of her next turn.

**Special Equipment.** Holga carries a darksteel greataxe, a magic weapon that grants her resistance to lightning damage while she carries it (included above).

**Unarmored Defense.** While Holga isn't wearing armor, her AC includes her Constitution modifier.


---

### Actions

**Multiattack.** Holga makes three Darksteel Greataxe or Improvised Weapon attacks, in any combination.

**Darksteel Greataxe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) slashing damage.

**Improvised Weapon.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft., or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage.


---

### Bonus Actions

**Wrestle.** Holga shoves a creature within 5 feet of herself. That creature must succeed on a DC 15 Strength saving throw or be moved 5 feet into an unoccupied space of Holga's choice.


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