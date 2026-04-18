---
type: pc
race: "Undead"
class:
 - "Dullahan"
subClass:
 - "CR 10"
cover: "Dullahan.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/vrgr
---
###### Dullahan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Dullahan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 11 | 15 | 16 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Con +7
**Skills:** Perception +6
**Damage Resistances:** cold; lightning; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Headless Summoning (Recharges after a Short or Long Rest).** If the dullahan is reduced to 0 hit points, it doesn't die or fall unconscious. Instead, it regains 97 hit points. In addition, it summons three death's heads, one of each type, in unoccupied spaces within 5 feet of it. The death's heads are under the dullahan's control and act immediately after the dullahan in the initiative order. Additionally, the dullahan can now use the options in the "Mythic Actions" section. Award a party an additional 5,900 XP (11,800 XP total) for defeating the dullahan after it uses Headless Summoning.

**Legendary Resistance (2/Day).** If the dullahan fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The dullahan doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The dullahan makes two attacks.

**Battleaxe.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands, plus 11 (2d10) necrotic damage. If the dullahan scores a critical hit against a creature, the target must succeed on a DC 15 Constitution saving throw or the dullahan cuts off the target's head. The target dies if it can't survive without the lost head. A creature that doesn't have or need a head, or has legendary actions, instead takes an extra 27 (6d8) slashing damage.

**Fiery Skull.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 14 (2d10 + 3) fire damage.


---

### Legendary Actions

### 

**Attack.** The dullahan makes one attack.

**Frightful Presence (Costs 2 Actions).** Each creature of the dullahan's choice within 30 feet of it must succeed on a DC 15 Wisdom saving throw or become frightened of the dullahan until the end of its next turn.

**Head Hunt (Costs 3 Actions).** The dullahan moves up to its speed without provoking opportunity attacks and makes one Battleaxe attack with advantage. If the attack hits, but is not a critical hit, the attack deals an extra 27 (6d8) necrotic damage.


---

### Mythic Actions

If the dullahan's Headless Summoning trait is active, it can use the options below as legendary actions.

### 

**Coordinated Assault.** The dullahan makes a Battleaxe attack, and then one death's head the dullahan can see within 30 feet of it can use its reaction to make a melee attack.

**Headless Wail (Costs 2 Actions).** An echoing shriek issues from the dullahan's headless stump. Each creature of the dullahan's choice within 10 feet of it must make a DC 15 Wisdom saving throw. Each creature takes 16 (3d10) psychic damage on a failed save, or half as much damage on a successful one. If one or more creatures fail the saving throw, the dullahan gains 10 temporary hit points.


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