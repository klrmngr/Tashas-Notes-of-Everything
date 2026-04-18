---
type: pc
race: "Fiend (demon)"
class:
 - "Goristro"
subClass:
 - "CR 17"
cover: "Goristro.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/17
  - source/xmm
---
###### Goristro
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Goristro.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 310 (23d12 + 161) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 11 | 25 | 6 | 13 | 14 |
| **Mod** | +7 | +0 | +7 | -2 | +1 | +2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 17
**Languages:** Abyssal
**Saving Throws:** Str +13, Dex +6, Con +13, Wis +7
**Skills:** Perception +7, Survival +7
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the goristro dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The goristro has Advantage on saving throws against spells and other magical effects.

**Siege Monster.** The goristro deals double damage to objects and structures.


---

### Actions

**Multiattack.** The goristro makes one Brutal Gore attack and two Slam attacks.

**Brutal Gore.** m +13, reach 10 ft. *Hit:* 40 (6d10 + 7) Piercing damage. If the target is a Huge or smaller creature, it is pushed up to 20 feet straight away from the goristro and has the Prone condition.

**Slam.** m +13, reach 10 ft. *Hit:* 29 (4d10 + 7) Bludgeoning damage.


---

### Bonus Actions

**Charge.** The goristro moves up to half its Speed straight toward an enemy it can see.


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