---
type: pc
race: "Celestial"
class:
 - "Guardian Naga"
subClass:
 - "CR 10"
cover: "Guardian Naga.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/10
  - source/xmm
---
###### Guardian Naga
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Guardian Naga.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 18 | 16 | 16 | 19 | 18 |
| **Mod** | +4 | +4 | +3 | +3 | +4 | +4 |

**Speed:** 40 ft., climb 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Celestial, Common
**Saving Throws:** Dex +8, Con +7, Int +7, Wis +8, Cha +8
**Skills:** Arcana +11, History +11, Religion +11
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned; restrained

---

### Traits

**Celestial Restoration.** If the naga dies, it returns to life in 1d6 days and regains all its Hit Points unless Dispel Evil and Good is cast on its remains.


---

### Actions

**Multiattack.** The naga makes two Bite attacks. It can replace any attack with a use of Poisonous Spittle.

**Bite.** m +8, reach 10 ft. *Hit:* 17 (2d12 + 4) Piercing damage plus 22 (4d10) Poison damage.

**Poisonous Spittle.** con DC 16, one creature the naga can see within 60 feet.  31 (7d8) Poison damage, and the target has the Blinded condition until the start of the naga's next turn.  Half damage only.


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