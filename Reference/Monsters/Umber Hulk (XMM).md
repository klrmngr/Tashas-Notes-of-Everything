---
type: pc
race: "Monstrosity"
class:
 - "Umber Hulk"
subClass:
 - "CR 5"
cover: "Umber Hulk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/xmm
---
###### Umber Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Umber Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 16 | 9 | 10 | 10 |
| **Mod** | +5 | +1 | +3 | -1 | +0 | +0 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Tremorsense 60 ft., passive Perception 10
**Languages:** Umber Hulk

---

### Traits

**Tunneler.** The umber hulk can burrow through solid rock at half its Burrow Speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The umber hulk makes three Rend attacks.

**Rend.** m +8, reach 10 ft. *Hit:* 12 (2d6 + 5) Slashing damage.


---

### Bonus Actions

**Confusing Gaze (Recharge 5–6).** wis DC 14, each creature in a 30-foot Cone.  The target can't take Reactions until the start of the umber hulk's next turn, and the target rolls 1d8 to determine what it does on its next turn:
- **1-4.** The target does nothing.
- **5-6.** The target takes no action or Bonus Action and uses all its movement to move in a random direction.
- **7-8.** The target makes a melee attack against a random creature within its reach or does nothing if it can't make such an attack.


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