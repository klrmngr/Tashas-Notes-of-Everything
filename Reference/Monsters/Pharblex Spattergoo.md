---
type: pc
race: "Humanoid (bullywug)"
class:
 - "Pharblex Spattergoo"
subClass:
 - "CR 3"
cover: "Pharblex Spattergoo.png"
campaign:
locations:
tags:
  - race/bullywug
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/hotdq
---
###### Pharblex Spattergoo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Pharblex Spattergoo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bullywug) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (studded leather, shield) |
> | :FasHeart: HP | 59 (7d8 + 28) |
> | :FasUserGroup: Race | Humanoid (bullywug) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 18 | 11 | 16 | 7 |
| **Mod** | +2 | +1 | +4 | +0 | +3 | -2 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Bullywug
**Saving Throws:** Str +4, Con +6
**Skills:** Perception +5, Religion +2, Stealth +3

---

### Traits

**Amphibious.** Pharblex can breathe air and water.

**Poison Strike (3/Day).** Once per turn, when Pharblex hits with a melee attack, he can expend a use of this trait to deal an extra 9 (2d8) poison damage.

**Standing Leap.** As part of his movement and without a running start, Pharblex can long jump up to 20 feet and high jump up to 10 feet.

**Swamp Camouflage.** Pharblex has advantage on Dexterity (Stealth) checks made to hide in swampy terrain.


---

### Actions

**Multiattack.** Pharblex attacks twice. Once with his bite and once with his spear.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Spear.** Melee or Ranged Weapon Attack: +5 to hit. reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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