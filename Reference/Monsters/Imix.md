---
type: pc
race: "Elemental"
class:
 - "Imix"
subClass:
 - "CR 19"
cover: "Imix.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/19
  - source/pota
---
###### Imix
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Imix.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 325 (26d12 + 156) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 24 | 22 | 15 | 16 | 23 |
| **Mod** | +4 | +7 | +6 | +2 | +3 | +6 |

**Speed:** 50 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 13
**Languages:** Common, Ignan
**Saving Throws:** Dex +13, Con +12, Cha +12
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Empowered Attacks.** Imix's slam attacks are treated as magical for the purpose of bypassing resistance and immunity to nonmagical attacks.

**Fire Aura.** At the start of each of Imix's turns, each creature within 10 feet of him takes 17 (5d6) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature also takes 17 (5d6) fire damage if it touches Imix or hits him with a melee attack while within 10 feet of him, and a creature takes that damage the first time on a turn that Imix moves into its space. Nonmagical weapons that hit Imix are destroyed by fire immediately after dealing damage to him

**Fire Form.** Imix can enter a hostile creature's space and stop there. He can move through a space as narrow as 1 inch without squeezing if fire could pass through that space.

**Illumination.** Imix sheds bright light in a 60-foot radius and dim light for an additional 60 feet.

**Legendary Resistance (3/Day).** If Imix fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Imix has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Imix makes two slam attacks or two flame blast attacks.

**Slam.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) bludgeoning damage plus 18 (5d6) fire damage.

**Flame Blast.** Ranged Spell Attack: +12 to hit, range 250 ft., one target. *Hit:* 35 (10d6) fire damage.

**Summon Elementals (1/Day).** Imix summons up to three [[Fire Elemental|fire elementals]] and loses 30 hit points for each elemental he summons. Summoned elementals have maximum hit points, appear within 100 feet of Imix, and disappear if Imix is reduced to 0 hit points.


---

### Legendary Actions

### 

**Heat Wave.** Imix creates a blast of heat within 300 feet of himself. Each creature in the area in physical contact with metal objects (for example, carrying metal weapons or wearing metal armor) takes 9 (2d8) fire damage. Each creature in the area that isn't resistant or immune to fire damage must make a DC 21 Constitution saving throw or gain one level of exhaustion.

**Teleport (Costs 2 Actions).** Imix magically teleports up to 120 feet to an unoccupied space he can see. Anything Imix is wearing or carrying isn't teleported with him.

**Combustion (Costs 3 Actions).** Imix causes one creature he can see within 30 feet of him to burst into flames. The target must make a DC 21 Constitution saving throw. On a failed save, the target takes 70 (20d6) fire damage and catches fire. A target on fire takes 10 (3d6) fire damage when it starts its turn, and remains on fire until it or another creature takes an action to douse the flames. On a successful save, the target takes half as much damage and doesn't catch fire.


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