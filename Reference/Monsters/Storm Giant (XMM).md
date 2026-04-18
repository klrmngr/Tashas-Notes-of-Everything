---
type: pc
race: "Giant"
class:
 - "Storm Giant"
subClass:
 - "CR 13"
cover: "Storm Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/13
  - source/xmm
---
###### Storm Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Storm Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 16 | 20 | 18 |
| **Mod** | +9 | +2 | +5 | +3 | +5 | +4 |

**Speed:** 50 ft., fly 25 ft. ((hover)), swim 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 20
**Languages:** Common, Giant
**Saving Throws:** Str +14, Con +10, Wis +10, Cha +9
**Skills:** Arcana +8, Athletics +14, History +8, Perception +10
**Damage Resistances:** cold
**Damage Immunities:** lightning; thunder

---

### Traits

**Amphibious.** The giant can breathe air and water.


---

### Actions

**Multiattack.** The giant makes two attacks, using Storm Sword or Thunderbolt in any combination.

**Storm Sword.** m +14, reach 10 ft. *Hit:* 23 (4d6 + 9) Slashing damage plus 13 (3d8) Lightning damage.

**Thunderbolt.** r +14, range 500 ft. *Hit:* 22 (2d12 + 9) Lightning damage, and the target has the Blinded and Deafened conditions until the start of the giant's next turn.

**Lightning Storm (Recharge 5–6).** dex DC 18, each creature in a 10-foot-radius, 40-foot-high Cylinder originating from a point the giant can see within 500 feet.  55 (10d10) Lightning damage.  Half damage.


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