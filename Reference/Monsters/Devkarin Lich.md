---
type: pc
race: "Undead"
class:
 - "Devkarin Lich"
subClass:
 - "CR 14"
cover: "Devkarin Lich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/14
  - source/ggr
---
###### Devkarin Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Devkarin Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 19 | 16 | 15 |
| **Mod** | +0 | +3 | +2 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** Common, Elvish, Kraul
**Saving Throws:** Con +7, Int +9, Wis +8
**Skills:** Arcana +14, Insight +8, Perception +8
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the lich fails a saving throw, it can choose to succeed instead.

**Regeneration.** The lich regains 10 hit points at the start of its turn. If the lich takes fire or radiant damage, this trait doesn't function at the start of the lich's next turn. The lich dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Turn Resistance.** The lich has advantage on saving throws against any effect that turns undead.

**Undead Fortitude.** If damage reduces the lich to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the lich drops to 1 hit point instead.


---

### Actions

**Noxious Touch.** Melee Spell Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 14 (4d6) poison damage, and the target must succeed on a DC 17 Constitution saving throw or be poisoned for 1 minute. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Cantrip.** The lich casts one of its cantrips.

**Noxious Touch (Costs 2 Actions).** The lich uses Noxious Touch.

**Disrupt Life (Costs 3 Actions).** Each creature within 30 feet of the lich must make a DC 17 Constitution saving throw, taking 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one.


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