---
type: pc
race: "Humanoid (merfolk)"
class:
 - "Zegana"
subClass:
 - "CR 16"
cover: "Zegana.png"
campaign:
locations:
tags:
  - race/merfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/16
  - source/ggr
---
###### Zegana
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Zegana.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (merfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Humanoid (merfolk) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 20 | 18 | 16 |
| **Mod** | +0 | +2 | +2 | +5 | +4 | +3 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** Common, Elvish, Merfolk
**Saving Throws:** Int +10, Wis +9
**Skills:** Insight +9, Nature +10, Perception +9
**Damage Resistances:** cold; poison

---

### Traits

**Amphibious.** Zegana can breathe air and water.

**Legendary Resistance (3/Day).** If Zegana fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Zegana has advantage on saving throws against spells and other magical effects.


---

### Actions

**Prime Speaker's Trident.** Melee or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage, and the trident emits a thunderous boom. Each creature in a 15-foot cube originating from the prongs of the trident must make a DC 18 Constitution saving throw. On a failed save, the creature takes 9 (2d8) thunder damage and is pushed 10 feet away from Zegana. If the creature is underwater, the damage is increased to 13 (3d8). On a successful save, the creature takes half as much damage and isn't pushed.

**Deluge (Recharge 4–6).** Zegana conjures a wave of water that crashes down on an area within 120 feet of her. The area can be up to 30 feet long, up to 10 feet wide, and up to 10 feet tall. Each creature in that area must make a DC 18 Dexterity saving throw. On a failed save, a creature takes 18 (4d8) bludgeoning damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone. The water spreads out across the ground, extinguishing unprotected flames it comes in contact with, and then vanishes.


---

### Legendary Actions

### 

**Adaptive Skin.** Zegana gains resistance to one damage type of her choice-acid, fire, lightning, or thunder-until the start of her next turn.

**Trident.** Zegana makes one melee attack with the Prime Speaker's Trident.

**Enlarge (Costs 2 Actions).** Zegana casts enlarge/reduce on herself, using the enlarge option, without expending a spell slot.

**Deluge (Costs 3 Actions).** Zegana uses Deluge, if available.


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