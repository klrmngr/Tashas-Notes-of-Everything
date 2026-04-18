---
type: pc
race: "Fiend (demon)"
class:
 - "Chasme"
subClass:
 - "CR 6"
cover: "Chasme.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/xmm
---
###### Chasme
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Chasme.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 78 (12d10 + 12) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 12 | 11 | 14 | 10 |
| **Mod** | +2 | +2 | +1 | +0 | +2 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 120 ft., passive Perception 15
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Dex +5, Wis +5
**Skills:** Perception +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the chasme dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The chasme has Advantage on saving throws against spells and other magical effects.

**Spider Climb.** The chasme can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Proboscis.** m +5, reach 5 ft. *Hit:* 16 (4d6 + 2) Piercing damage plus 21 (6d6) Necrotic damage. If the target is a creature, its Hit Point maximum decreases by an amount equal to the Necrotic damage taken.


---

### Bonus Actions

**Drone.** con DC 12, each creature in a 30-foot Emanation originating from the chasme (demons automatically succeed on this save).  The target has the Unconscious condition and repeats the save at the end of each of its turns. The target succeeds automatically after 10 minutes or if it takes damage or a creature within 5 feet of it takes an action to empty a flask of Holy Water on it.  The target is immune to this chasme's Drone for 24 hours.


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