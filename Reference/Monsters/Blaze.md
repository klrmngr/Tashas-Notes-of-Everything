---
type: pc
race: "Elemental"
class:
 - "Blaze"
subClass:
 - "CR 5"
cover: "Blaze.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/5
  - source/mcv3mc
---
###### Blaze
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV3MC
___

> [!infobox|no-t right]
> ![[Blaze.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | MCV3MC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 16 | 6 | 10 | 7 |
| **Mod** | +3 | +3 | +3 | -2 | +0 | -2 |

**Speed:** 20 ft., fly 20 ft. ((vertical movement only; hover)) (hover) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Blaze Rod.** When the blaze drops to 0 hit points, it disappears in a cloud of smoke and has a 50 percent chance of leaving behind a glowing rod worth 100 gp. The rod sheds dim light in a 5-foot radius. As an action, a creature can try to snap the rod, doing so with a successful DC 14 Strength check. The snapped rod releases its fiery energy in a 5-foot-radius sphere centered on itself. Each creature in that area must make a DC 14 Dexterity saving throw, taking 6 (1d12) fire damage on a failed save, or half as much damage on a successful one.

**Heat Aura.** Any creature that starts its turn within 5 feet of the blaze takes 3 (1d6) fire damage.

**Illumination.** The blaze sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

**Water Susceptibility.** The blaze takes 1 cold damage for every 5 feet it moves in water, for every gallon of water splashed on it, or whenever it starts its turn in the rain.


---

### Actions

**Multiattack.** The blaze makes three Fiery Doom attacks.

**Fiery Doom.** Melee or Ranged Spell Attack: +6 to hit; reach 5 ft. or ranged 60 ft., one target. *Hit:* 8 (1d10 + 3) fire damage, and the target catches fire if it's a creature or a flammable object. Until a creature takes an action to extinguish the fire, the burning target takes 3 (1d6) fire damage at the end of each of its turns.


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