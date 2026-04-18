---
type: pc
race: "Humanoid (wizard)"
class:
 - "Sofina"
subClass:
 - "CR 15"
cover: "Sofina.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/hat-tg
---
###### Sofina
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Sofina.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 161 (19d8 + 76) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 18 | 20 | 14 | 8 |
| **Mod** | +1 | +2 | +4 | +5 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Common, Draconic, Infernal, Thayan
**Saving Throws:** Int +10, Wis +7
**Skills:** Arcana +10, History +10, Insight +7
**Damage Resistances:** necrotic

---

### Traits

**Special Equipment.** Sofina wears a magic robe that grants her a +2 bonus to AC and a +1 bonus to saving throws (included above).


---

### Actions

**Multiattack.** Sofina makes three Necrotic Strike attacks.

**Necrotic Strike.** Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 32 (5d10 + 5) necrotic damage.

**Swarm of Meteors (1/Day).** Sofina magically calls down a meteor swarm that detonates in four 40-foot-radius spheres, each one centered on a point she can see within 1 mile of herself. These spheres can overlap. Each creature in one or more of these spheres must make a DC 18 Dexterity saving throw, taking 35 (10d6) fire damage and 35 (10d6) bludgeoning damage on a failed saving throw, or half as much damage on a successful one. A creature in multiple spheres takes this damage only once.


---

### Bonus Actions

**Summon Wraith (1/Day).** Sofina magically summons the spirit of a Thayan assassin, which appears as a wraith (see the Monster Manual). The summoned wraith appears in an unoccupied space within 60 feet of Sofina, whom it obeys. The summoned wraith takes its turn immediately after Sofina. It lasts for 1 hour, until it or Sofina dies, or until Sofina dismisses it as a bonus action.


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