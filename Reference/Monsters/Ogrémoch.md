---
type: pc
race: "Elemental"
class:
 - "Ogrémoch"
subClass:
 - "CR 20"
cover: "Ogrémoch.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/20
  - source/pota
---
###### Ogrémoch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Ogrémoch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 526 (27d20 + 243) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 11 | 28 | 11 | 15 | 22 |
| **Mod** | +8 | +0 | +9 | +0 | +2 | +6 |

**Speed:** 50 ft., burrow 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., tremorsense 120 ft., passive Perception 12
**Languages:** Common, Terran
**Saving Throws:** Str +14, Con +15, Wis +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Empowered Attacks.** Ogrémoch's slam attacks are treated as magical and adamantine for the purpose of bypassing resistance and immunity to nonmagical attacks.

**Legendary Resistance (3/Day).** If Ogrémoch fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Ogrémoch has advantage on saving throws against spells and other magical effects.

**Siege Monster.** Ogrémoch deals double damage to objects and structures with his melee and ranged weapon attacks.


---

### Actions

**Multiattack.** Ogrémoch makes two slam attacks.

**Slam.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Boulder.** Ranged Weapon Attack: +6 to hit, range 500 ft., one target. *Hit:* 46 (7d10 + 8) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Strength saving throw or be knocked prone.

**Summon Elementals (1/Day).** Ogrémoch summons up to three earth elementals and loses 30 hit points for each elemental he summons. Summoned elementals have maximum hit points, appear within 100 feet of Ogrémoch, and disappear if Ogrémoch is reduced to 0 hit points.


---

### Legendary Actions

### 

**Illuminating Crystals.** Ogrémoch's crystalline protrusions flare. Each creature within 30 feet of Ogrémoch becomes outlined in orange light, shedding dim light in a 10-foot radius. Any attack roll against an affected creature has advantage if the attacker can see it, and the affected creature can't benefit from being invisible.

**Stomp (Costs 2 Actions).** Ogrémoch stomps the ground, creating an earth tremor that extends in a 30-foot radius. Other creatures standing on the ground in that radius must succeed on a DC 23 Dexterity saving throw or fall prone.

**Create Gargoyle (Costs 3 Actions).** Ogrémoch's hit points are reduced by 50 as he breaks off a chunk of his body and places it on the ground in an unoccupied space within 15 feet of him. The chunk of rock instantly transforms into a gargoyle and acts on the same initiative count as Ogrémoch. Ogrémoch can't use this action if he has 50 hit points or fewer. The gargoyle obeys Ogrémoch's commands and fights until destroyed.


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