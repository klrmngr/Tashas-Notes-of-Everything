---
type: pc
race: "Giant"
class:
 - "Death Giant Reaper"
subClass:
 - "CR 12"
cover: "Death Giant Reaper.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/12
  - source/bgg
---
###### Death Giant Reaper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Death Giant Reaper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 20 | 18 | 16 | 16 |
| **Mod** | +8 | +2 | +5 | +4 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Giant
**Saving Throws:** Con +9, Int +8, Wis +7, Cha +7
**Skills:** Arcana +8, History +8, Perception +7, Stealth +6
**Damage Immunities:** necrotic
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The giant makes two Scythe or Soul Bolt attacks.

**Scythe.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 21 (3d8 + 8) slashing damage plus 11 (2d10) necrotic damage.

**Soul Bolt.** Ranged Spell Attack: +8 to hit, range 120 ft., one creature. *Hit:* 26 (4d10 + 4) necrotic damage. If the target has the frightened condition, the giant gains temporary hit points equal to the damage dealt.


---

### Bonus Actions

**Frightening Teleport (Recharge 4–6).** The giant magically teleports, along with any equipment it is wearing or carrying, up to 40 feet to an unoccupied space it can see. Each creature within 10 feet of the location the giant left must succeed on a DC 16 Wisdom saving throw or have the frightened condition until the end of that creature's next turn.


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