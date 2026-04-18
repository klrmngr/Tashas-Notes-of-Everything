---
type: pc
race: "Swarm of Tiny Monstrositys"
class:
 - "Swarm of Corrupted Rats"
subClass:
 - "CR 1"
cover: "Swarm of Corrupted Rats.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/wtthc
---
###### Swarm of Corrupted Rats
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Swarm of Corrupted Rats.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Monstrositys |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Swarm of Tiny Monstrositys |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 10 | 2 | 11 | 4 |
| **Mod** | -1 | +2 | +0 | -4 | +0 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Dex +4
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Death Burst.** The rat explodes when it dies. con DC 10, each creature in a 10-foot Emanation originating from the rat.  2d4 Acid Damage.  Half damage.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny rat. The swarm can't regain Hit Points.


---

### Actions

**Bite.** m +4, Reach 5 ft. *Hit:* 6 (2d4 + 2) Piercing damage or 1d4 + 2 Piercing damage if the swarm is Bloodied.


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