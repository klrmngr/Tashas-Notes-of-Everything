---
type: pc
race: "Fiend"
class:
 - "Udaak"
subClass:
 - "CR 16"
cover: "Udaak.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/gargantuan
  - cr/16
  - source/egw
---
###### Udaak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Udaak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Fiend |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 165 (10d20 + 60) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 22 | 3 | 11 | 10 |
| **Mod** | +8 | +2 | +6 | -4 | +0 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Str +13, Con +11
**Damage Vulnerabilities:** thunder
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened; grappled; poisoned; restrained

---

### Traits

**Charge.** If the udaak moves at least 20 feet straight toward a target and then hits it with a slam attack on the same turn, the target takes an extra 27 (6d8) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be pushed up to 20 feet away from the udaak and knocked prone.

**Siege Monster.** The udaak deals double damage to objects and structures.


---

### Actions

**Multiattack.** The udaak makes three attacks: one with its bite and two with its slam.

**Bite.** Melee Weapon Attack: +13 to hit, reach 5 ft., one creature. *Hit:* 21 (2d12 + 8) piercing damage, and the target is grappled (escape DC 21). Until this grapple ends, the target is restrained, and the udaak can't bite another target.

**Slam.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage.

**Swallow.** The udaak makes one bite attack against a Large or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. A swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the udaak, and it takes 21 (6d6) acid damage at the start of each of the udaak's turns.
If the udaak takes 30 damage or more on a single turn from a creature inside it, the udaak must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the udaak. If the udaak dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.


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