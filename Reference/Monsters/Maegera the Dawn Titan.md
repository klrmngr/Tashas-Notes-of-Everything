---
type: pc
race: "Elemental"
class:
 - "Maegera the Dawn Titan"
subClass:
 - "CR 23"
cover: "Maegera the Dawn Titan.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/23
  - source/skt
---
###### Maegera the Dawn Titan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Maegera the Dawn Titan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 341 (22d20 + 110) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 22 | 20 | 10 | 10 | 19 |
| **Mod** | +5 | +6 | +5 | +0 | +0 | +4 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** Ignan
**Saving Throws:** Con +12, Wis +7, Cha +11
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Empowered Attacks.** Maegera's slam attacks are treated as magical for the purpose of overcoming resistance and immunity to damage from nonmagical attacks.

**Fire Aura.** At the start of each of Maegera's turns, each creature within 30 feet of it takes 35 (10d6) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature also takes 35 (10d6) fire damage from touching Maegera or from hitting it with a melee attack while within 10 feet of it, and a creature takes that damage the first time on a turn that Maegera moves into its space. Nonmagical weapons that hit Maegera are destroyed by fire immediately after dealing damage to it.

**Fire Form.** Maegera can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing if fire could pass through that space.

**Illumination.** Maegera sheds bright light in a 120-foot radius and dim light in an additional 120 ft..

**Magic Resistance.** Maegera has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Maegera makes three slam attacks.

**Slam.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 15 (3d6 + 5) bludgeoning damage plus 35 (10d6) fire damage,


---

### Legendary Actions

### 

**Quench Magic.** Maegera targets one creature that it can see within 60 feet of it. Any resistance or immunity to fire damage that the target gains from a spell or magic item is suppressed. The effect lasts until the end of Maegera's next turn.

**Smoke Cloud (Costs 2 Actions).** Maegera exhales a billowing cloud of hot smoke and embers that fills a 60 feet cube. Each creature in the area takes 11 (2d10) fire damage. The cloud lasts until the end of Maegera's next turn. Creatures completely in the cloud are blinded and can't be seen.

**Create Fire Elemental (Costs 3 Actions).** Maegera's hit points are reduced by 50 as part of it separates and becomes a [[Fire Elemental]] with 102 hit points. The fire element appears in an unoccupied space within 15 feet of Maegera and acts on Maegera's initiative count. Maegera can't use this action if it has 50 hit points or fewer. The fire element obeys Maegera's commands and fights until destroyed.


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