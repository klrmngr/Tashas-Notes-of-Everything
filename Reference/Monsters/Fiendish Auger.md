---
type: pc
race: "Construct"
class:
 - "Fiendish Auger"
subClass:
 - "CR 5"
cover: "Fiendish Auger.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/5
  - source/pabtso
---
###### Fiendish Auger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Fiendish Auger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (9d12 + 27) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 17 | 6 | 12 | 5 |
| **Mod** | +6 | +0 | +3 | -2 | +1 | -3 |

**Speed:** 40 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 11
**Languages:** —
**Damage Immunities:** fire; poison
**Condition Immunities:** blinded; charmed; exhaustion; frightened; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Siege Monster.** The auger deals double damage to objects and structures.

**Tunneler.** The auger can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Flaming Drill.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 7 (2d6) fire damage. If the auger moves at least 20 feet in a straight line toward the target immediately before the hit, the target takes an additional 11 (2d10) piercing damage, and if the target is a creature, it must succeed on a DC 17 Strength saving throw or have the prone condition.


---

### Bonus Actions

**Burst of Heat (Recharge 5–6).** The auger releases an intense burst of heat in a 30-foot-radius sphere centered on itself. This heat spreads around corners. Each creature in this area must make a DC 17 Constitution saving throw, taking 13 (3d8) fire damage on a failed save, or half as much damage on a successful one.


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