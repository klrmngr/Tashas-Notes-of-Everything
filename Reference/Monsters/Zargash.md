---
type: pc
race: "Humanoid (cleric, human)"
class:
 - "Zargash"
subClass:
 - "CR 3"
cover: "Zargash.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wbtw
---
###### Zargash
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Zargash.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric, human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (chain shirt) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (cleric, human) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 12 | 16 | 15 |
| **Mod** | +2 | +0 | +2 | +1 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Saving Throws:** Wis +5, Cha +4
**Skills:** Deception +6, Insight +5

---

### Traits

**Cling to Life (Recharges after a Long Rest).** The first time Zargash would drop to 0 hit points as a result of taking damage, he instead drops to 1 hit point.

**Special Equipment.** Zargash wears a bat-shaped amulet that has the properties of a ring of feather falling.


---

### Actions

**Warhammer.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage when used with two hands.

**Deathly Ray.** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 25 (4d10 + 3) necrotic damage.


---

### Bonus Actions

**Animate Corpse (1/Day).** Zargash targets the lifeless corpse of one Humanoid he can see within 30 feet of him and commands it to rise, transforming it into a zombie under his control. The zombie takes its turn immediately after Zargash. Animating the zombie requires Zargash's concentration (as if concentrating on a spell). The zombie reverts to an inanimate corpse after 10 minutes, when it drops to 0 hit points, or when Zargash's concentration ends.


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