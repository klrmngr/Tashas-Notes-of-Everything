---
type: pc
race: "Undead"
class:
 - "Bodak"
subClass:
 - "CR 6"
cover: "Bodak.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/mpmm
---
###### Bodak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Bodak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 15 | 7 | 12 | 12 |
| **Mod** | +2 | +3 | +2 | -2 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, the languages it knew in life
**Skills:** Perception +4, Stealth +6
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Death Gaze.** When a creature that can see the bodak's eyes starts its turn within 30 feet of the bodak, the bodak can force it to make a DC 13 Constitution saving throw if the bodak isn't incapacitated and can see the creature. If the saving throw fails by 5 or more, the creature is reduced to 0 hit points unless it is immune to the frightened condition. Otherwise, a creature takes 16 (3d10) psychic damage on a failed save.
Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it has disadvantage on attack rolls against the bodak until the start of its next turn. If the creature looks at the bodak in the meantime, that creature must immediately make the saving throw.

**Sunlight Hypersensitivity.** The bodak takes 5 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

**Unusual Nature.** The bodak doesn't require air, food, drink, or sleep.


---

### Actions

**Fist.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage plus 9 (2d8) necrotic damage.

**Withering Gaze.** One creature that the bodak can see within 60 feet of it must make a DC 13 Constitution saving throw, taking 22 (4d10) necrotic damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Aura of Annihilation.** The bodak activates or deactivates this deathly aura. While active, the aura deals 5 necrotic damage to any creature that ends its turn within 30 feet of the bodak. Undead and Fiends ignore this effect.


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