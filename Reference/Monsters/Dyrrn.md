---
type: pc
race: "Aberration"
class:
 - "Dyrrn"
subClass:
 - "CR 24"
cover: "Dyrrn.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/24
  - source/erlw
---
###### Dyrrn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Dyrrn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 325 (31d8 + 186) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 21 | 22 | 26 | 23 | 24 |
| **Mod** | +8 | +5 | +6 | +8 | +6 | +7 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +15, Wis +13, Cha +14
**Skills:** Arcana +15, History +15, Insight +13, Perception +13
**Damage Resistances:** poison; psychic
**Condition Immunities:** blinded; charmed; exhaustion; frightened; poisoned; prone

---

### Traits

**Alien Mind.** If a creature tries to read Dyrrn's thoughts or deals psychic damage to it, that creature must succeed on a DC 23 Intelligence saving throw or be stunned for 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Legendary Resistance (3/Day).** If Dyrrn fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Dyrrn has advantage on saving throws against spells and other magical effects.

**Regeneration.** Dyrrn regains 20 hit points at the start of its turn. If Dyrrn takes radiant damage, this trait doesn't function at the start of its next turn. Dyrrn dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Teleport.** As a bonus action, Dyrrn can teleport up to 30 feet to an unoccupied space it can see.


---

### Actions

**Multiattack.** Dyrrn makes one Tentacle Whip attack and uses its Corruption once. Dyrrn can replace its Tentacle Whip attack with Extract Brain if it has a creature grappled.

**Tentacle Whip.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 24 (3d10 + 8) slashing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 23), pulled into an unoccupied space within 5 feet of Dyrrn, and must succeed on a DC 23 Intelligence saving throw or be stunned until this grapple ends. Dyrrn can't use the same tentacle whip on another target until this grapple ends. Dyrrn has two tentacle whips.

**Corruption.** Dyrrn targets one creature it can see within 60 feet of it. The target must succeed on a DC 23 Constitution saving throw or take 22 (4d6 + 8) necrotic damage and become corrupted for 1 minute.
A corrupted creature's flesh twists in alien ways. The creature has disadvantage on attack rolls, its speed is reduced by half, and if it tries to cast a spell, it must first succeed on a DC 15 Intelligence check or the spell fails and is wasted. The corrupted creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Extract Brain.** Melee Weapon Attack: +15 to hit, reach 5 ft., one incapacitated creature grappled by Dyrrn. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, Dyrrn kills the target by extracting and devouring its brain.


---

### Legendary Actions

### 

**Tentacle Whip.** Dyrrn makes one attack with its Tentacle Whip.

**Spawn Aberration (Costs 2 Actions).** Dyrrn regurgitates an intellect devourer in an unoccupied space within 5 feet of it. The intellect devourer is under Dyrrn's control and acts immediately after Dyrrn in the initiative order.

**Mind Blast (Costs 3 Actions).** Dyrrn magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 23 Intelligence saving throw or take 30 (5d8 + 8) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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