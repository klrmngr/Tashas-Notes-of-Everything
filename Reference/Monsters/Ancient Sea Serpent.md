---
type: pc
race: "Dragon"
class:
 - "Ancient Sea Serpent"
subClass:
 - "CR 14"
cover: "Ancient Sea Serpent.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/14
  - source/ftd
---
###### Ancient Sea Serpent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Sea Serpent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 170 (11d20 + 55) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 15 | 20 | 13 | 16 | 12 |
| **Mod** | +7 | +2 | +5 | +1 | +3 | +1 |

**Speed:** 20 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Str +12, Con +10
**Skills:** Perception +8, Stealth +7
**Damage Immunities:** cold

---

### Traits

**Amphibious.** The sea serpent can breathe air and water.

**Legendary Resistance (2/Day).** If the sea serpent fails a saving throw, it can choose to succeed instead.

**Siege Monster.** The sea serpent deals double damage to objects and structures.


---

### Actions

**Multiattack.** The sea serpent makes one Bite attack and one Constrict or Tail attack.

**Bite.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 20 (2d12 + 7) piercing damage plus 6 (1d12) cold damage.

**Constrict.** Melee Weapon Attack: +12 to hit, reach 20 ft., one creature. *Hit:* 29 (4d10 + 7) bludgeoning damage, and the target is grappled (escape DC 20). Until this grapple ends, the target is restrained, and the sea serpent can't constrict another target.

**Tail.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 13 (1d12 + 7) bludgeoning damage. If the target is a creature, it must succeed on a DC 20 Strength saving throw or be pushed up to 30 feet away from the sea serpent and knocked prone.

**Rime Breath (Recharge 5–6).** The sea serpent exhales a 60-foot cone of cold. Each creature in that area must make a DC 18 Constitution saving throw, taking 49 (9d10) cold damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tail.** The sea serpent makes one Tail attack.

**Bite (Costs 2 Actions).** The sea serpent makes one Bite attack


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