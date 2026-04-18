---
type: pc
race: "Beast"
class:
 - "Gishath, Sun's Avatar"
subClass:
 - "CR 10"
cover: "Gishath, Sun's Avatar.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/gargantuan
  - cr/10
  - source/psx
---
###### Gishath, Sun's Avatar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSX
___

> [!infobox|no-t right]
> ![[Gishath, Sun's Avatar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Gargantuan Beast |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 203 (14d20 + 56) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 12 | 18 | 12 | 16 | 6 |
| **Mod** | +7 | +1 | +4 | +1 | +3 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** —
**Saving Throws:** Str +11, Con +8, Wis +7, Cha +2
**Skills:** Perception +7

---

### Traits

**Legendary Resistance (3/Day).** If Gishath fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** Gishath makes two attacks: one with its bite and one with its stomp or tail. It can't make both attacks against the same target.

**Bite.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 39 (5d12 + 7) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or it is grappled (escape DC 19). Until this grapple ends, the target is restrained, and Gishath can't bite another target.

**Swallow.** Gishath makes one bite attack against a Large or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is blinded and restrained, it has 3 against attacks and other effects outside Gishath, and it takes 21 (6d6) acid damage at the start of each of Gishath's turns.
If Gishath takes 30 damage or more on a single turn from a creature inside it, it must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of it. If Gishath dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.

**Stomp.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 29 (5d8 + 7) bludgeoning damage, and the target must succeed on a DC 19 Strength saving throw or be knocked prone.

**Tail.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 25 (4d8 + 7) bludgeoning damage.


---

### Legendary Actions

### 

**Attack.** Gishath makes one stomp or tail attack.

**Roar (Costs 2 Actions).** Each creature that is within 120 feet of Gishath and can hear it must succeed on a DC 19 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Gishath's Roar for the next 24 hours.


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