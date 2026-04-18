---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Mind Master"
subClass:
 - "CR 2"
cover: "Duergar Mind Master.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mpmm
---
###### Duergar Mind Master
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Duergar Mind Master.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 14 | 15 | 10 | 12 |
| **Mod** | +0 | +3 | +2 | +2 | +0 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 30 ft., passive Perception 12
**Languages:** Dwarvish, Undercommon
**Saving Throws:** Wis +2
**Skills:** Perception +2, Stealth +5
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** The duergar has advantage on saving throws against spells and the charmed, paralyzed, and poisoned conditions.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The duergar makes two Mind-Poison Dagger attacks. It can replace one attack with a use of Mind Mastery.

**Mind-Poison Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 10 (3d6) psychic damage, or 1 piercing damage plus 10 (3d6) psychic damage while under the effect of Reduce.

**Invisibility (Recharge 4–6).** The duergar magically turns invisible for up to 1 hour or until it attacks, it forces a creature to make a saving throw, or its concentration is broken (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it.

**Mind Mastery.** The duergar targets one creature it can see within 60 feet of it. The target must succeed on a DC 12 Intelligence saving throw, or the duergar causes it to use its reaction, if available, either to make one weapon attack against another creature the duergar can see or to move up to 10 feet in a direction of the duergar's choice. Creatures that can't be charmed are immune to this effect.


---

### Bonus Actions

**Reduce (Recharges after a Short or Long Rest).** For 1 minute, the duergar magically decreases in size, along with anything it is wearing or carrying. While reduced, the duergar is Tiny, reduces its weapon damage to 1, and makes attack rolls, ability checks, and saving throws with disadvantage if they use Strength. It gains a +5 bonus to all Dexterity (Stealth) checks and a +5 bonus to its AC. It can also take a bonus action on each of its turns to take the Hide action.


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