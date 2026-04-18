---
type: pc
race: "Plant"
class:
 - "Violet Fungus Necrohulk"
subClass:
 - "CR 7"
cover: "Violet Fungus Necrohulk.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/7
  - source/xmm
---
###### Violet Fungus Necrohulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Violet Fungus Necrohulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 18 | 7 | 14 | 10 |
| **Mod** | +4 | +1 | +4 | -2 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 12
**Languages:** —
**Damage Immunities:** necrotic; poison
**Condition Immunities:** blinded; charmed; deafened; frightened; poisoned

---

### Actions

**Multiattack.** The necrohulk makes two Rotting Slam attacks.

**Rotting Slam.** m +7, reach 10 ft. *Hit:* 9 (1d10 + 4) Bludgeoning damage plus 7 (2d6) Necrotic damage.

**Spore Bomb (Recharge 5–6).** con DC 15, each creature in a 20-foot-radius Sphere centered on a point the necrohulk can see within 60 feet.  28 (8d6) Necrotic damage, and the target has the Poisoned condition until the start of the necrohulk's next turn. While Poisoned, the target can't regain Hit Points.  Half damage only.


---

### Bonus Actions

**Absorb Body.** str DC 15, one Medium or Small creature the necrohulk can see within 5 feet.  The target is pulled into the necrohulk's space and becomes grafted to its body. The necrohulk can have only one target grafted at a time.
While grafted, the target has the Restrained condition and Disadvantage on Constitution saving throws. When the necrohulk moves, the grafted target moves with it. If the target dies while grafted, its body is destroyed, and the necrohulk regains 10 Hit Points.
The grafted target or a creature within 5 feet of the necrohulk can take an action to make a DC 15 Strength (Athletics) check. On a successful check, the target is no longer grafted and moves to an unoccupied space within 5 feet of the necrohulk.


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