---
type: pc
race: "Undead"
class:
 - "Will-o'-Wisp"
subClass:
 - "CR 2"
cover: "Will-o'-Wisp.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/2
  - source/xmm
---
###### Will-o'-Wisp
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Will-o'-Wisp.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 27 (11d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 28 | 10 | 13 | 14 | 11 |
| **Mod** | -5 | +9 | +0 | +1 | +2 | +0 |

**Speed:** 5 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Common plus one other language
**Damage Resistances:** acid; bludgeoning; cold; fire; necrotic; piercing; slashing
**Damage Immunities:** lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Ephemeral.** The wisp can't wear or carry anything.

**Illumination.** The wisp sheds Bright Light in a 20-foot radius and Dim Light for an additional 20 feet.

**Incorporeal Movement.** The wisp can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.


---

### Actions

**Shock.** m +4, reach 5 ft. *Hit:* 11 (2d8 + 2) Lightning damage.


---

### Bonus Actions

**Consume Life.** con DC 10, one living creature the wisp can see within 5 feet that has 0 Hit Points.  The target dies, and the wisp regains 10 (3d6) Hit Points.

**Vanish.** The wisp and its light have the Invisible condition until the wisp's Concentration ends on this effect, which ends early immediately after the wisp makes an attack roll or uses Consume Life.


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