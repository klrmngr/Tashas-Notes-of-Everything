---
type: pc
race: "Humanoid"
class:
 - "Priest of Osybus"
subClass:
 - "CR 6"
cover: "Priest of Osybus.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/vrgr
---
###### Priest of Osybus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Priest of Osybus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 16 | 18 | 17 | 11 |
| **Mod** | +0 | +2 | +3 | +4 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** any three languages
**Saving Throws:** Int +7, Wis +6, Cha +3
**Condition Immunities:** frightened

---

### Traits

**Tattoo of Osybus.** If the priest drops to 0 hit points, roll on the Boons of Undeath table for the boon the priest receives. The priest dies if it receives a boon it already has. If it receives a new boon, it revives at the start of its next turn with half its hit points restored, and its creature type is now Undead.
To prevent this revival, the Tattoo of Osybus on the priest's body must be destroyed. The tattoo is invulnerable while the priest has at least 1 hit point. The tattoo is otherwise an object with AC 15, and it is immune to poison and psychic damage. It has 15 hit points, but it regains all its hit points at the end of every combatant's turn.


---

### Actions

**Multiattack.** The priest attacks twice.

**Soul Blade.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) piercing damage, and if the target is a creature, it is paralyzed until the start of the priest's next turn. If this damage reduces a Medium or smaller creature to 0 hit points, the creature dies, and its soul is trapped in the priest's body, manifesting as a shadowy Soul Tattoo on the priest. The soul is freed if the priest dies.

**Necrotic Bolt.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 17 (3d8 + 4) necrotic damage, and the target can't regain hit points until the start of the priest's next turn.


---

### Bonus Actions

**Soul Tattoo (Recharge 5–6).** The priest touches one of the Soul Tattoos on its body. The tattoo vanishes as the trapped soul manifests as a shadowy creature that appears in an unoccupied space the priest can see within 30 feet of it. The creature has the size and silhouette of its original body, but it otherwise uses the stat block of a shadow.
The shadow obeys the priest's mental commands (no action required) and takes its turn immediately after the priest. If the creature is within 5 feet of the priest, it can turn back into a tattoo as an action, reappearing on the priest's flesh and regaining all its hit points.


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