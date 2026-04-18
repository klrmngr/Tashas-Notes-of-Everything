---
type: pc
race: "Undead"
class:
 - "Wersten Kern"
subClass:
 - "CR 14"
cover: "Wersten Kern.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/14
  - source/dsotdq
---
###### Wersten Kern
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Wersten Kern.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 18 | 13 | 14 | 16 |
| **Mod** | +5 | +0 | +4 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Infernal, Solamnic
**Saving Throws:** Con +9, Wis +7
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; frightened; poisoned

---

### Traits

**Undead Fortitude.** If damage reduces Wersten to 0 hit points, she must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning or from a critical hit. On a success, Wersten drops to 1 hit point instead.

**Unusual Nature.** Wersten doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Wersten makes three Banner Pike attacks and uses Terrifying Litany if it's available.

**Banner Pike.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) piercing damage plus 13 (3d8) necrotic damage. If the target is a Humanoid, it must succeed on a DC 16 Charisma saving throw or be cursed. The curse lasts until it is lifted by remove curse or similar magic. Black, thorny rose stems sprout from the creature's body while it is cursed, imposing disadvantage on the creature's ability checks and attack rolls and halving its speed. A creature that succeeds on the saving throw against the curse is immune to it for 24 hours.

**Terrifying Litany (Recharge 5–6).** Wersten recites names of souls slain by Soth and his company, channeling their mortal terror. Each creature that isn't an Undead within 30 feet of her must make a DC 16 Wisdom saving throw. On a failed save, the creature takes 22 (4d10) psychic damage and is frightened of Wersten for 1 minute. On a successful save, the creature takes half as much damage and isn't frightened. At the end of each of its turns, a frightened creature can repeat the saving throw, ending the effect on itself on a success.


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