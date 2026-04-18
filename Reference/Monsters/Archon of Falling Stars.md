---
type: pc
race: "Celestial"
class:
 - "Archon of Falling Stars"
subClass:
 - "CR 12"
cover: "Archon of Falling Stars.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/12
  - source/mot
---
###### Archon of Falling Stars
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Archon of Falling Stars.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 19 | 15 | 21 | 19 |
| **Mod** | +5 | +2 | +4 | +2 | +5 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** all
**Saving Throws:** Str +9, Con +8, Wis +9, Cha +8
**Skills:** Arcana +6, History +6, Insight +9, Perception +9
**Damage Immunities:** radiant
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Magic Resistance.** The archon has advantage on saving throws against spells and other magical effects.

**Mount.** If the archon isn't mounted, it can use a bonus action to magically teleport onto the creature serving as its mount, provided the archon and its mount are on the same plane of existence. When it teleports, the archon appears astride the mount, along with any equipment it is wearing or carrying. While mounted and not incapacitated, the archon can't be surprised, and both it and its mount have advantage on Dexterity saving throws. If the archon is reduced to 0 hit points while riding its mount, the mount is reduced to 0 hit points as well.

**Radiant Rebirth (Recharges after a Long Rest).** If the archon is reduced to 0 hit points, it regains 30 hit points and springs back to its feet with a burst of radiance. Each creature of the archon's choice within 30 feet of it must succeed on a DC 16 Constitution saving throw, or the creature takes 13 (3d8) radiant damage and is blinded until the start of the archon's turn.


---

### Actions

**Multiattack.** The archon makes two attacks with its radiant spear.

**Radiant Spear.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 10 (3d6) radiant damage.


---

### Legendary Actions

### 

**Attack.** The archon makes a radiant spear attack or casts guiding bolt.

**Coordinated Assault (Costs 2 Actions).** The archon makes a radiant spear attack, and then its mount can use its reaction to make a melee weapon attack.

**Return to Nyx (Costs 3 Actions).** The archon causes a corpse it can see within 30 feet of it to burst into a shower of radiant stars leaving no trace of it behind. Everything it is wearing or carrying remains. Each creature within 10 feet of the corpse when it bursts must succeed on a DC 16 Dexterity saving throw or take 22 (4d10) radiant damage.


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