---
type: pc
race: "Dragon"
class:
 - "Dragon Turtle"
subClass:
 - "CR 17"
cover: "Dragon Turtle.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/17
  - source/xmm
---
###### Dragon Turtle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dragon Turtle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 356 (23d20 + 115) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 20 | 10 | 12 | 12 |
| **Mod** | +7 | +0 | +5 | +0 | +1 | +1 |

**Speed:** 20 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Draconic, Primordial (Aquan)
**Saving Throws:** Con +11, Wis +7
**Damage Resistances:** fire

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three Bite attacks. It can replace one attack with a Tail attack.

**Bite.** m +13, reach 15 ft. *Hit:* 23 (3d10 + 7) Piercing damage plus 7 (2d6) Fire damage. Being underwater doesn't grant Resistance to this Fire damage.

**Tail.** m +13, reach 15 ft. *Hit:* 18 (2d10 + 7) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.

**Steam Breath (Recharge 5–6).** con DC 19, each creature in a 60-foot Cone.  56 (16d6) Fire damage.  Half damage.  Being underwater doesn't grant Resistance to this Fire damage.


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