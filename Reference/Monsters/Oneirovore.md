---
type: pc
race: "Fiend"
class:
 - "Oneirovore"
subClass:
 - "CR 11"
cover: "Oneirovore.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/coa
---
###### Oneirovore
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Oneirovore.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 237 (19d10 + 133) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 25 | 12 | 10 | 10 |
| **Mod** | +3 | +1 | +7 | +1 | +0 | +0 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 14
**Languages:** —
**Saving Throws:** Con +11, Int +5
**Skills:** Insight +4, Nature +5, Perception +4, Survival +4
**Damage Resistances:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; frightened

---

### Actions

**Stomp.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 16 (2d12 + 3) force damage.

**Realize Nightmares (Recharge 4–6).** The oneirovore manipulates the perception of nearby creatures, sending them into a panic. Creatures of the oneirovore's choice that it can see within 60 feet must make a DC 19 Charisma saving throw. On a failed save, the creature has the charmed condition, their vision distorted such that they view their allies as creatures of pure fear and hatred. While charmed, a creature will use their actions to attack their allies with intent to kill. A charmed creature may repeat the saving throw at the end of each turn, ending the effect on a success.

**Warning Cry (1/Day).** The oneirovore lets out an earsplitting shriek, calling for infernal reinforcements. Creatures that are not Fiends that are within 120 feet of the oneirovore must make a DC 19 Constitution saving throw, taking 55 (10d10) thunder damage on a failed save, or half as much damage on a successful one. Any lesser devils within a 1-mile-radius, centered on the oneirovore, are required by contract to come to its aid upon hearing its Warning Cry. Higher ranking devils may investigate if they desire, but the call holds no magical sway over them.


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