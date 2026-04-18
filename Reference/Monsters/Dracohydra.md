---
type: pc
race: "Monstrosity"
class:
 - "Dracohydra"
subClass:
 - "CR 11"
cover: "Dracohydra.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/11
  - source/ftd
---
###### Dracohydra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dracohydra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 218 (19d12 + 95) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 6 | 12 | 12 |
| **Mod** | +5 | +1 | +5 | -2 | +1 | +1 |

**Speed:** 30 ft., fly 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** understands Draconic but can't speak
**Skills:** Perception +9

---

### Traits

**Multiple Heads.** The dracohydra has five heads. While it has more than one head, the dracohydra has advantage on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.
Whenever the dracohydra takes 30 or more damage in a single turn, one of its heads dies. If all its heads die, the dracohydra dies.
At the end of its turn, the dracohydra grows two heads for each of its heads that died since its last turn, unless it has taken radiant damage since its last turn. The dracohydra regains 10 hit points for each head regrown this way.

**Reactive Heads.** For each head the dracohydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

**Wakeful.** While the dracohydra sleeps, at least one of its heads is awake.


---

### Actions

**Multiattack.** The dracohydra makes as many Bite attacks as it has heads.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) damage of a type chosen by the dracohydra: acid, cold, fire, lightning, or poison.

**Prismatic Breath (Recharge 4–6).** The dracohydra's heads exhale a single breath of multicolored energy in a 60-foot cone. Each creature in that area must make a DC 17 Dexterity saving throw. On a failed save, the creature takes 33 (6d10) damage of a type chosen by the dracohydra: acid, cold, fire, lightning, or poison. On a successful save, the creature takes half as much damage.


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