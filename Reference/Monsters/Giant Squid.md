---
type: pc
race: "Beast"
class:
 - "Giant Squid"
subClass:
 - "CR 6"
cover: "Giant Squid.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/6
  - source/xmm
---
###### Giant Squid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Squid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 120 (16d12 + 16) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 12 | 5 | 11 | 4 |
| **Mod** | +6 | +2 | +1 | -3 | +0 | -3 |

**Speed:** 5 ft., swim 80 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** —
**Saving Throws:** Str +9, Dex +5
**Skills:** Perception +6

---

### Traits

**Water Breathing.** The squid can breathe only underwater.


---

### Actions

**Multiattack.** The squid makes one Bite attack and one Tentacle attack.

**Bite.** m +9, reach 5 ft. *Hit:* 28 (4d10 + 6) Piercing damage.

**Tentacle.** m +9, reach 15 ft. *Hit:* 19 (3d8 + 6) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Grappled condition (escape DC 16) from one of two tentacles, and the squid can pull the target up to 10 feet straight toward itself.


---

### Reactions

**Ink Cloud (1/Day).**  The squid takes damage while underwater.  The squid releases ink that fills a 15-foot Cube centered on itself, and the squid moves up to its Swim Speed. The Cube is Heavily Obscured for 1 minute or until a strong current or similar effect disperses the ink.


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