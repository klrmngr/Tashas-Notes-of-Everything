---
type: pc
race: "Monstrosity"
class:
 - "Carrion Stalker"
subClass:
 - "CR 3"
cover: "Carrion Stalker.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/3
  - source/vrgr
---
###### Carrion Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Carrion Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 35 (10d4 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 12 | 2 | 13 | 6 |
| **Mod** | -2 | +3 | +1 | -4 | +1 | -2 |

**Speed:** 30 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** tremorsense 60 ft., passive Perception 11
**Languages:** —
**Skills:** Stealth +7
**Condition Immunities:** blinded

---

### Actions

**Multiattack.** The carrion stalker makes three Tentacle attacks. If it is attached to a creature, it can replace one Tentacle attack with Larval Burst, if available.

**Tentacle.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) piercing damage, and the carrion stalker attaches to the target and pulls itself into the target's space. While attached, the carrion stalker moves with the target and has advantage on attack rolls against it.
A creature can use its action to try to detach the carrion stalker and force it to move into the nearest unoccupied space, doing so with a successful DC 11 Strength check. On its turn, the carrion stalker can detach itself from the target by using 5 feet of movement. When it dies, the carrion stalker detaches from any creature it is attached to.

**Larval Burst (1/Day).** The carrion stalker releases a burst of larvae in a 10-foot-radius sphere centered on itself. Each creature in that area must succeed on a DC 13 Constitution saving throw or be poisoned. A creature poisoned in this way takes 7 (2d6) poison damage at the start of each of its turns as larvae infest its body. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Any effect that cures disease or removes the poisoned condition instantly kills the larvae in the creature, ending the effect on it.
If a creature is reduced to 0 hit points by the infestation, it dies. The larvae remain in the corpse, and one survives to become a fully grown carrion stalker in 1d4 weeks. Any effect that cures diseases or removes the poisoned condition that targets the corpse instantly kills the larvae.


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