---
type: pc
race: "Fiend"
class:
 - "Daemogoth Titan"
subClass:
 - "CR 16"
cover: "Daemogoth Titan.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/gargantuan
  - cr/16
  - source/scc
---
###### Daemogoth Titan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Daemogoth Titan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Fiend |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 203 (11d20 + 88) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 26 | 24 | 18 | 20 |
| **Mod** | +8 | +0 | +8 | +7 | +4 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Abyssal, Infernal, telepathy 120 ft.
**Saving Throws:** Int +12, Wis +9, Cha +10
**Skills:** Arcana +17, Deception +15, History +12, Perception +9
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the titan fails a saving throw, it can choose to succeed instead.

**Pact of Suffering.** Using a 10-minute long ritual, the titan can forge a magical bond with a willing creature it touches throughout the ritual. The creature becomes bound by the pact until it dies, the titan dies, or the pact is broken by a wish spell.
The titan chooses one spell from the level=0;1;2;3;4;5;6;7;8. The bound creature can cast that spell using this pact, requiring no material components and using Intelligence as the spellcasting ability. When it casts the spell, the creature takes 21 (6d6) psychic damage, which can't break the creature's concentration on a spell. Once the bound creature casts the spell in this way, it can't do so again until it finishes a long rest.


---

### Actions

**Multiattack.** The titan makes two Agonizing Burst attacks.

**Agonizing Burst.** Melee or Ranged Spell Attack: +12 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 17 (3d6 + 7) force damage. If the target is a creature, the titan regains 5 hit points.

**Teleport.** The titan teleports to an unoccupied space it can see within 120 feet of itself.


---

### Legendary Actions

### 

**Attack.** The titan makes one Agonizing Burst attack.

**Stalking Nightmare (Costs 2 Actions).** The titan uses Teleport, after which it can target one creature within 20 feet of itself that it can see. The target must make a DC 20 Constitution saving throw. On a failed save, the target takes 22 (4d10) necrotic damage, and the titan regains 10 hit points. On a successful save, the target takes half as much damage, and the titan doesn't heal.

**Terrorize (Costs 3 Actions).** The titan targets one creature it can see within 120 feet of itself. The target must make a DC 20 Wisdom saving throw. On a failed save, the target takes 38 (7d10) psychic damage and is frightened of the titan until the end of the target's next turn, and the titan regains 15 hit points. On a successful save, the target takes half as much damage and isn't frightened, and the titan doesn't heal.


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