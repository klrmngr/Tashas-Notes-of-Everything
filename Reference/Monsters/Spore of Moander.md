---
type: pc
race: "Plant"
class:
 - "Spore of Moander"
subClass:
 - "CR 12"
cover: "Spore of Moander.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/12
  - source/fraif
---
###### Spore of Moander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Spore of Moander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 9 | 20 | 4 | 10 | 6 |
| **Mod** | +6 | -1 | +5 | -3 | +0 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 10
**Languages:** understands Abyssal but can't speak
**Saving Throws:** Str +10, Con +9
**Damage Resistances:** acid; cold; lightning
**Damage Immunities:** fire; poison
**Condition Immunities:** blinded; deafened; exhaustion; paralyzed; poisoned; prone

---

### Traits

**Explosive Core.** When the spore is subjected to Fire damage, each creature in a 5-foot Emanation originating from the spore takes 7 (2d6) Fire damage.

**Rolling Mass.** The spore doesn't need to expend extra movement to move through Difficult Terrain.


---

### Actions

**Multiattack.** The spore makes four Tendril attacks. Alternatively, it makes two Tendril attacks and uses Consume once.

**Tendril.** m +10, reach 20 ft. *Hit:* 11 (1d10 + 6) Piercing damage plus 10 (3d6) Acid damage. If the target is Large or smaller, the spore pulls the target 5 feet straight toward itself.

**Consume.** str DC 18, one Large or smaller creature within 5 feet.  The target is pulled into the spore's space and has the Grappled condition (escape DC 16). Until the grapple ends, the target has the Blinded and Restrained conditions, and it takes 17 (5d6) Acid damage at the start of each of the spore's turns. When the spore moves, the Grappled target moves with it, costing it no extra movement. The spore can have one Large creature or up to nine Medium or smaller creatures Grappled at a time.


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