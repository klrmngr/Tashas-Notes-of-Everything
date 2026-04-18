---
type: pc
race: "Construct"
class:
 - "Clockwork Horror"
subClass:
 - "CR 2"
cover: "Clockwork Horror.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/2
  - source/mcv1sc
---
###### Clockwork Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Clockwork Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 60 (8d6 + 32) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 18 | 13 | 14 | 10 |
| **Mod** | +2 | +2 | +4 | +1 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Thri-kreen, Ziklight
**Saving Throws:** Str +4, Wis +4
**Skills:** Perception +6
**Damage Immunities:** lightning; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Shutdown.** If targeted by dispel magic, the horror must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute or until it takes any damage.

**Unusual Nature.** The horror doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The horror makes one Bite attack and two Rotating Saw attacks, or it makes two Lightning Jolt attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Rotating Saw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Lightning Jolt.** Ranged Spell Attack: +4 to hit, range 120 ft., one target. *Hit:* 7 (1d10 + 2) lightning damage.

**Spelljamming Helm Interface.** The horror attaches to a spelljamming helm it can see within 5 feet of itself and attunes to the helm instantly. If another creature is already attuned to the helm, that creature's attunement to the helm ends when the horror's attunement begins. The horror can operate the helm even though it isn't a spellcaster. The horror can detach from the helm as a bonus action, which ends its attunement to the helm.


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