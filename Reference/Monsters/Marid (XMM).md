---
type: pc
race: "Elemental (genie)"
class:
 - "Marid"
subClass:
 - "CR 11"
cover: "Marid.png"
campaign:
locations:
tags:
  - race/genie
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/xmm
---
###### Marid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Marid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental (genie) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 229 (17d10 + 136) |
> | :FasUserGroup: Race | Elemental (genie) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 26 | 18 | 17 | 18 |
| **Mod** | +6 | +1 | +8 | +4 | +3 | +4 |

**Speed:** 30 ft., fly 60 ft., swim 90 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 13
**Languages:** Primordial (Aquan)
**Saving Throws:** Dex +5, Cha +8
**Damage Resistances:** acid; cold; lightning

---

### Traits

**Amphibious.** The marid can breathe air and water.

**Elemental Restoration.** If the marid dies outside the Elemental Plane of Water, its body dissolves into brine, and it gains a new body in 1d4 days, reviving with all its Hit Points somewhere on the Plane of Water.

**Wishes.** The marid has a 30 percent chance of knowing the Wish spell. If the marid knows it, the marid can cast it only on behalf of a non-genie creature who communicates a wish in a way the marid can understand. If the marid casts the spell for the creature, the marid suffers none of the spell's stress. Once the marid has cast it three times, the marid can't do so again for 365 days.


---

### Actions

**Multiattack.** The marid makes three Aquatic Lash attacks.

**Aquatic Lash.** m +10, reach 15 ft. *Hit:* 15 (2d8 + 6) Slashing damage plus 9 (2d8) Cold damage.

**Water Jet.** dex DC 18, each creature in a 60-foot-long, 10-foot-wide Line.  31 (9d6) Cold damage. If the target is a Huge or smaller creature, it is pushed up to 20 feet straight away from the marid and has the Prone condition.  Half damage only.


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