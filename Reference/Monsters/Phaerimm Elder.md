---
type: pc
race: "Aberration"
class:
 - "Phaerimm Elder"
subClass:
 - "CR 14"
cover: "Phaerimm Elder.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/14
  - source/nf
---
###### Phaerimm Elder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Phaerimm Elder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 218 (23d12 + 69) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 17 | 17 | 16 | 18 |
| **Mod** | +4 | +3 | +3 | +3 | +3 | +4 |

**Speed:** 30 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 18
**Languages:** telepathy 120 ft. understands Common and Deep Speech but can't speak
**Saving Throws:** Con +8, Int +8, Wis +8, Cha +9
**Skills:** Arcana +13, Insight +8, Perception +8
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Resistance.** The phaerimm has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The phaerimm makes three Mind Lash attacks. It can replace one attack with either (A) a Vicious Stinger attack or (B) a use of Spellcasting to cast Command (level 3 version).

**Mind Lash.** m,r +9, reach 10 ft. or range 120 ft. *Hit:* 32 (6d8 + 4) Psychic damage.

**Vicious Stinger.** m +9, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 26 (4d12) Poison damage, and the target's Speed is reduced to 0 feet until the start of the phaerimm's next turn.

**Siphon Magic (Recharge 5–6).** The phaerimm focuses on a magic item it can see within 10 feet. When it does, the phaerimm drains the magic item of any charges. Regardless of whether charges are drained, the phaerimm can cast Clairvoyance, Geas, Major Image, and Mirage Arcane one additional time that day.


---

### Bonus Actions

**Teleport.** The phaerimm teleports up to 30 feet to an unoccupied space it can see.


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