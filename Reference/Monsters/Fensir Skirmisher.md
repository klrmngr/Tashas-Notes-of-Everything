---
type: pc
race: "Giant"
class:
 - "Fensir Skirmisher"
subClass:
 - "CR 6"
cover: "Fensir Skirmisher.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/6
  - source/bgg
---
###### Fensir Skirmisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fensir Skirmisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 20 | 14 | 11 | 12 |
| **Mod** | +4 | +2 | +5 | +2 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Giant
**Saving Throws:** Int +5, Wis +3
**Skills:** Perception +6

---

### Traits

**Regeneration.** The fensir regains 10 hit points at the start of its turn if it isn't in sunlight. If the fensir takes acid or fire damage, this trait doesn't function at the start of the fensir's next turn. The fensir dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Sunlight Hypersensitivity.** When the fensir starts its turn in sunlight, it must succeed on a DC 15 Constitution saving throw or have the petrified condition until the fensir is no longer in sunlight.


---

### Actions

**Multiattack.** The fensir makes three Battleaxe attacks or two Magic Stone attacks.

**Battleaxe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage, or 15 (2d10 + 4) slashing damage if used with two hands.

**Magic Stone.** Ranged Spell Attack: +5 to hit, range 60 ft., one target. *Hit:* 15 (2d12 + 2) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 13 Strength saving throw or have the prone condition.

**Mud to Stone (Recharge 6).** The fensir lobs a magical mass of mud that splashes all creatures in a 30-foot-radius sphere centered on a point the fensir can see within 60 feet of itself. Each non-fensir creature in that area must succeed on a DC 13 Dexterity saving throw or take 13 (3d8) bludgeoning damage and have the restrained condition as the mud begins to turn to stone. An affected creature must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the creature. On a failed save, the creature has the petrified condition for 24 hours.


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