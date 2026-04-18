---
type: pc
race: "Aberration"
class:
 - "Enderman"
subClass:
 - "CR 6"
cover: "Enderman.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/mcv3mc
---
###### Enderman
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV3MC
___

> [!infobox|no-t right]
> ![[Enderman.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MCV3MC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 18 | 15 | 10 | 18 | 11 |
| **Mod** | +2 | +4 | +2 | +0 | +4 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Endspeech
**Saving Throws:** Str +5, Con +5
**Skills:** Perception +7, Stealth +7, Survival +7
**Damage Resistances:** necrotic

---

### Traits

**Evasive Teleportation.** Whenever it takes damage or is the target of a ranged attack, the Enderman can teleport, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 20 feet of itself (no action required). If this effect is triggered by a ranged attack, the Enderman teleports just before the attack hits, causing the attack to miss it. This trait is suppressed while the Enderman has the incapacitated condition.

**Implosion.** When the Enderman drops to 0 hit points, it dies as its body implodes. Roll a d10. On a roll of 9 or less, the Enderman leaves no remains. On a roll of 10, the Enderman leaves behind a glowing, purple orb called an Ender pearl, worth 500 gp. A creature can throw the pearl up to 60 feet; if the pearl lands in an unoccupied space big enough to contain the creature, the creature teleports to that space, along with any equipment it is wearing or carrying, and the pearl disappears.

**Sunlight Sensitivity.** While in sunlight, the Enderman has disadvantage on attack rolls.

**Water Susceptibility.** The Enderman takes 1 cold damage for every 5 feet it moves in water, for every gallon of water splashed on it, or whenever it starts its turn in the rain.


---

### Actions

**Multiattack.** The Enderman makes two Slam attacks.

**Slam.** Melee Weapon Attack: +7 to hit; reach 10 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage plus 9 (2d8) necrotic damage.


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