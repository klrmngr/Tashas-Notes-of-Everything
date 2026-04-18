---
type: pc
race: "Monstrosity"
class:
 - "King of Feathers"
subClass:
 - "CR 8"
cover: "King of Feathers.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/8
  - source/toa
---
###### King of Feathers
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[King of Feathers.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 200 (19d12 + 52) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 19 | 2 | 12 | 9 |
| **Mod** | +7 | +0 | +4 | -4 | +1 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Traits

**Detect Invisibility.** The King of Feathers can see invisible creatures and objects as if they were visible.

**Legendary Resistance (3/Day).** If the King of Feathers fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The King of Feathers makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 33 (4d12 + 7) piercing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 17). Until this grapple ends, the target is restrained, and the tyrannosaurus can't bite another target.

**Tail.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage.

**Summon Swarm (Recharge 5–6).** The King of Feathers exhales a [[Swarm Of Wasps|swarm of insects (wasps)]] that forms in a space within 20 feet of it. The swarm acts as an ally of the King of Feathers and takes its turn immediately after it. The swarm disperses after 1 minute. It can't use the Summon Swarm action while it is grappling a creature with its jaws.


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