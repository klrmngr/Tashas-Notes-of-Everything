---
type: pc
race: "Undead (paladin)"
class:
 - "Lord Soth"
subClass:
 - "CR 19"
cover: "Lord Soth.png"
campaign:
locations:
tags:
  - race/paladin
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/19
  - source/dsotdq
---
###### Lord Soth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Lord Soth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Medium Undead (paladin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 228 (24d8 + 120) |
> | :FasUserGroup: Race | Undead (paladin) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 20 | 12 | 16 | 20 |
| **Mod** | +6 | +0 | +5 | +1 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Common, Infernal, Solamnic
**Saving Throws:** Dex +6, Wis +9, Cha +11
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Soth fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Soth has advantage on saving throws against spells and other magical effects.

**Marshal Undead.** Unless Soth is incapacitated, he and Undead creatures of his choice within 60 feet of him are immune to features that turn Undead.

**Unusual Nature.** Soth doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Soth makes three Forsaken Brand attacks.

**Forsaken Brand.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage plus 18 (4d8) necrotic damage, and if the target is a creature, it can't regain hit points until the start of Soth's next turn.

**Cataclysmic Fire (1/Day).** Soth hurls a magical ball of fire that explodes at a point he can see within 120 feet of himself. Each creature in a 20-foot-radius sphere centered on that point must make a DC 19 Dexterity saving throw. A creature takes 35 (10d6) fire damage and 35 (10d6) necrotic damage on a failed save, or half as much damage on a successful one.
Additionally, any Medium or smaller Humanoid killed by this damage, as well as every corpse of such a creature within the sphere, becomes a skeleton (see the Monster Manual) under Soth's control. The skeleton acts on Soth's initiative but immediately after his turn. Absent any other command, the skeleton tries to kill any non-Undead creature it encounters.

**Word of Death (1/Day).** Soth points at a creature he can see within 60 feet of himself and magically commands it to die. The target must make a DC 19 Constitution saving throw, taking 100 necrotic damage on a failed save, or half as much damage on a successful one. If this damage reduces the target to 0 hit points, the target dies.


---

### Legendary Actions

### 

**Implacable Maneuver.** Soth moves up to his speed or commands a mount he is riding to move up to its speed. The movement from this action doesn't provoke opportunity attacks. If he or his mount moves within 5 feet of a creature during this movement, he can force the creature to make a DC 20 Strength saving throw. The creature is knocked prone unless it succeeds on the saving throw.

**Strike (Costs 2 Actions).** Soth makes one Forsaken Brand attack.

**Cast a Spell (Costs 3 Actions).** Soth uses Spellcasting.


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