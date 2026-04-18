---
type: pc
race: "Undead"
class:
 - "Jarad Vod Savo"
subClass:
 - "CR 22"
cover: "Jarad Vod Savo.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/22
  - source/ggr
---
###### Jarad Vod Savo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Jarad Vod Savo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 180 (24d8 + 72) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 16 | 20 | 16 | 15 |
| **Mod** | +2 | +3 | +3 | +5 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Common, Elvish, Kraul
**Saving Throws:** Con +10, Int +12, Wis +10
**Skills:** Arcana +12, Insight +10, Perception +10
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Jarad fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Jarad has advantage on saving throws against spells and other magical effects.

**Regeneration.** Jarad regains 25 hit points at the start of his turn. If he takes fire or radiant damage, this trait doesn't function at the start of his next turn. He dies only if he starts its turn with 0 hit points and doesn't regenerate.

**Spore Infusion.** Jarad is surrounded by a cloud of spores. As a bonus action, he can cause the spores to deal 11 (2d10) poison damage to a creature he can see within 10 feet of him.

**Turn Resistance.** Jarad has advantage on saving throws against any effect that turns undead.

**Undead Fortitude.** If damage reduces Jarad to 0 hit points, he must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, he drops to 1 hit point instead.


---

### Actions

**Multiattack.** Jarad makes two attacks: one with his Noxious Touch and one with his Staff of Svogthir. He can cast a spell with a casting time of 1 action in place of one of these attacks.

**Noxious Touch.** Melee Spell Attack: +12 to hit, reach 5 ft., one creature. *Hit:* 28 (8d6) poison damage, and the target must succeed on a DC 20 Constitution saving throw or be poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Staff of Svogthir.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage plus 13 (3d8) poison damage and 13 (3d8) necrotic damage.


---

### Legendary Actions

### 

**Cantrip.** Jarad casts one of his cantrips.

**Noxious Touch (Costs 2 Actions).** Jarad uses Noxious Touch.

**Disrupt Life (Costs 3 Actions).** Each creature within 30 feet of Jarad must make a DC 20 Constitution saving throw, taking 35 (10d6) necrotic damage on a failed save, or half as much damage on a successful one.


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