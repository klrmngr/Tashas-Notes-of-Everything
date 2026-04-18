---
type: pc
race: "Humanoid"
class:
 - "Cultist of Bhaal"
subClass:
 - "CR 7"
cover: "Cultist of Bhaal.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/fraif
---
###### Cultist of Bhaal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Cultist of Bhaal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 19 | 18 | 15 | 17 | 14 |
| **Mod** | +1 | +4 | +4 | +2 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 16
**Languages:** Common
**Saving Throws:** Dex +7, Int +5
**Skills:** Perception +6, Stealth +7

---

### Traits

**Blood-Soaked Resolve.** While Bloodied, the cultist has Advantage on saving throws.


---

### Actions

**Multiattack.** The cultist makes three Cursed Blade attacks. It can replace one of these attacks with a use of Spellcasting.

**Cursed Blade.** m,r +7 (with Advantage if the target doesn't have all its Hit Points), reach 5 ft. or range 20/80 ft. *Hit:* 14 (3d6 + 4) Slashing damage. The blade magically returns to the cultist's hand immediately after a ranged attack.


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