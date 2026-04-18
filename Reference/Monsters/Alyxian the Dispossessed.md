---
type: pc
race: "Humanoid (human)"
class:
 - "Alyxian the Dispossessed"
subClass:
 - "CR 13"
cover: "Alyxian the Dispossessed.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/crcotn
---
###### Alyxian the Dispossessed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian the Dispossessed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (leather armor, shield) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 18 | 13 | 14 | 20 |
| **Mod** | +4 | +2 | +4 | +1 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Celestial, Common, Elvish, telepathy 120 ft.
**Saving Throws:** Str +9, Con +9, Wis +7
**Skills:** Insight +7, Perception +7, Persuasion +10
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; stunned

---

### Traits

**Divinely Blessed.** Alyxian can't be surprised and can't be changed into another form against his will.

**Legendary Resistance (2/Day).** If Alyxian fails a saving throw, he can choose to succeed instead.

**Special Equipment.** Alyxian carries a magic dagger that he uses to make Stoneheart Dagger attacks. In the hands of creatures other than Alyxian, the dagger is nonmagical and has no special properties.


---

### Actions

**Multiattack.** Alyxian makes two Spear attacks.

**Spear.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage when used with two hands to make a melee attack, plus 9 (2d8) radiant damage.

**Stoneheart Dagger.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 11 (3d4 + 4) force damage, and if the target is a creature, it must succeed on a DC 17 Constitution saving throw or become petrified as the dagger lodges itself in the target's body. While the dagger is lodged in the target, magic can't end the petrified condition on it and Alyxian can't make Stoneheart Dagger attacks. A creature within reach of the petrified target can use an action to try to remove the dagger, doing so with a successful DC 17 Strength check.


---

### Bonus Actions

**Summon Dagger.** Alyxian's Stoneheart Dagger teleports into his free hand, provided he has one.


---

### Reactions

**Parry.** Alyxian adds 3 to his AC against one attack roll that would hit him. To do so, Alyxian must see the attacker and be wielding a melee weapon.


---

### Legendary Actions

### 

**Attack.** Alyxian makes one Spear or Stoneheart Dagger attack.

**Warrior's Stride.** Alyxian moves up to his speed. This movement doesn't provoke opportunity attacks.

**Ruidium Shard (Costs 2 Actions).** A gem-sized shard of ruidium appears at a point Alyxian can see within 120 feet of himself and explodes. Each creature, other than Alyxian, in a 10-foot-radius sphere centered on that point must succeed on a DC 18 Charisma saving throw or gain 1 level of exhaustion. If a creature isn't suffering from ruidium corruption, it becomes corrupted when it fails the saving throw.


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