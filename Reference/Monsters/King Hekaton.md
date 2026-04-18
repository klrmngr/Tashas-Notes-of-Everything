---
type: pc
race: "Giant"
class:
 - "King Hekaton"
subClass:
 - "CR 13"
cover: "King Hekaton.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/13
  - source/skt
---
###### King Hekaton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[King Hekaton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (scale mail) |
> | :FasHeart: HP | 330 (20d12 + 100) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 16 | 18 | 18 |
| **Mod** | +9 | +2 | +5 | +3 | +4 | +4 |

**Speed:** 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Common, Giant
**Saving Throws:** Str +14, Con +10, Wis +9, Cha +9
**Skills:** Arcana +8, Athletics +14, History +8, Perception +9
**Damage Resistances:** cold
**Damage Immunities:** lightning; thunder

---

### Traits

**Amphibious.** Hekaton can breathe air and water.


---

### Actions

**Multiattack.** Hekaton makes two broken chain attacks.

**Broken Chain.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 18 (3d6 + 9) bludgeoning damage.

**Ballista.** Ranged Weapon Attack: +6 to hit, range 120/480 ft., one target. *Hit:* 18 (3d10 + 2) piercing damage.

**Lightning Strike (Recharge 5–6).** Hekaton hurls a magical lightning bolt at a point he can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed save, or half as much damage on a successful one.

**Thunderous Stomp (Recharge 6).** Hekaton stomps the ground, triggering a thunderclap. All other creatures within 15 feet of him must succeed on a DC 17 Constitution saving throw or take 33 (6d10) thunder damage and be deafened until the start of Hekaton's next turn. On a successful save, a creature takes half as much damage and isn't deafened. The thunderclap can be heard out to a range of 1,200 feet.


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