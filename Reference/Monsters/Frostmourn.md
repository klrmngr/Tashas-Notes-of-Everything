---
type: pc
race: "Undead"
class:
 - "Frostmourn"
subClass:
 - "CR 10"
cover: "Frostmourn.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/10
  - source/bgg
---
###### Frostmourn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Frostmourn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 21 | 9 | 11 | 18 |
| **Mod** | +6 | -1 | +5 | -1 | +0 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Giant
**Saving Throws:** Con +9, Wis +4
**Skills:** Athletics +10, Perception +4
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Actions

**Multiattack.** The frostmourn makes one Freezing Touch attack and one Icy Axe attack. It can replace one of these attacks with a Polar Ray attack.

**Freezing Touch.** Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. *Hit:* 18 (4d8) cold damage plus 18 (4d8) necrotic damage. If this damage would reduce the target to 0 hit points, the target drops to 1 hit point instead and has the petrified condition, turning into a frozen statue.
If the statue takes bludgeoning damage, it shatters, killing the frozen creature. If the statue would take fire damage, it instead takes no damage and thaws, ending the petrification.

**Icy Axe.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) slashing damage plus 7 (2d6) cold damage.

**Polar Ray.** Ranged Spell Attack: +8 to hit, range 120 ft., one target. *Hit:* 31 (5d10 + 4) cold damage, and the target's speed is reduced by 10 feet until the end of its next turn.


---

### Reactions

**Blizzard Escape.** Immediately after a creature the frostmourn can see hits it with an attack roll, the frostmourn momentarily dissolves into a blizzard, reducing the damage to itself by half. The frostmourn can then magically teleport to an unoccupied space it can see within 30 feet of itself.


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