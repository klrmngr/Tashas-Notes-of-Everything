---
type: pc
race: "Dragon"
class:
 - "Young Sea Serpent"
subClass:
 - "CR 8"
cover: "Young Sea Serpent.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/8
  - source/ftd
---
###### Young Sea Serpent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Sea Serpent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 123 (13d12 + 39) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 17 | 11 | 13 | 10 |
| **Mod** | +4 | +1 | +3 | +0 | +1 | +0 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Common, Draconic
**Saving Throws:** Str +7, Con +6
**Skills:** Perception +4, Stealth +4
**Damage Immunities:** cold

---

### Traits

**Amphibious.** The sea serpent can breathe air and water.

**Siege Monster.** The sea serpent deals double damage to objects and structures.


---

### Actions

**Multiattack.** The sea serpent makes one Bite attack and one Constrict or Tail attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage plus 5 (1d10) cold damage.

**Constrict.** Melee Weapon Attack: +7 to hit, reach 20 ft., one creature. *Hit:* 22 (4d8 + 4) bludgeoning damage. If the target is Large or smaller, it is grappled (escape DC 15). Until this grapple ends, the target is restrained, and the sea serpent can't constrict another target.

**Tail.** Melee Weapon Attack: +7 to hit, reach 15 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be pushed up to 20 feet away and knocked prone.

**Rime Breath (Recharge 5–6).** The sea serpent exhales a 30-foot cone of cold. Each creature in that area must make a DC 14 Constitution saving throw, taking 38 (7d10) cold damage on a failed save, or half as much damage on a successful one.


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