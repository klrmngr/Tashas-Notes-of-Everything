---
type: pc
race: "Fey"
class:
 - "Brigganock"
subClass:
 - "CR 1/8"
cover: "Brigganock.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-8
  - source/wbtw
---
###### Brigganock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Brigganock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 9 (2d4 + 4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 14 | 10 | 11 | 13 |
| **Mod** | -3 | +2 | +2 | +0 | +0 | +1 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Sylvan
**Saving Throws:** Dex +4, Con +4
**Condition Immunities:** exhaustion

---

### Traits

**Fey Ancestry.** The brigganock has advantage on saving throws against being charmed, and magic can't put it to sleep.

**Soul Light.** The brigganock is accompanied by an insubstantial, invulnerable ball of light that contains its soul. The brigganock can't turn off the light or control its brightness. The soul light sheds bright light in a 10-foot radius and dim light for an additional 10 feet. If the brigganock dies, its soul light fades away.

**Tunneler.** Using a pickaxe or similar tool, a brigganock can burrow through solid rock at a speed of 5 feet, leaving a 6-inch-diameter tunnel in its wake.


---

### Actions

**Pickaxe.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Time Lapse (Recharges after a Short or Long Rest).** The brigganock accelerates the passage of time around itself, enabling it to accomplish up to 1 hour of work in a matter of seconds. This work can't affect any creature other than the brigganock, or any object being worn or carried by another creature, and the activity must take place within a 10-foot cube. For example, the brigganock could use this action to rapidly carve a pumpkin, cook and eat dinner, move a pile of stones, or tie a dozen knots in a length of rope.


---

### Bonus Actions

**Move Soul Light.** The brigganock moves its soul light up to 30 feet in any direction to an unoccupied space it can see. At the end of the current turn, the light returns to the brigganock.


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