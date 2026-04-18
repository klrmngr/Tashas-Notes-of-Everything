---
type: pc
race: "Humanoid (human)"
class:
 - "Viktor"
subClass:
 - "CR 9"
cover: "Viktor.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mabjov
---
###### Viktor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Viktor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 20 (plate, shield) |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 18 | 11 | 11 | 16 |
| **Mod** | +4 | +1 | +4 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Saving Throws:** Con +8, Wis +4
**Skills:** Persuasion +7, Religion +4

---

### Traits

**Brave.** Viktor has advantage on saving throws against being frightened.

**Shadow Dragon Companion.** Viktor has a young gold shadow dragon that accompanies him at all times. If Viktor dies, the young gold shadow dragon returns to the Shadowfell.

**Sun Blade.** Viktor wields a sun blade. Viktor gains a +2 bonus to attack and damage rolls made with this weapon, which deals radiant damage instead of slashing damage (this is already factored into Viktor's stat block). When Viktor hits an Undead creature with this sword, that target takes an extra 4 (1d8) radiant damage. The sword's luminous blade emits bright light in a 15-foot radius and dim light for an additional 15 feet. The light is sunlight.


---

### Actions

**Multiattack.** Viktor makes two Sun Blade attacks and one Raven's Whisper attack.

**Sun Blade.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) radiant damage or 11 (1d10 + 6) radiant damage if used with two hands.

**Raven's Whisper.** Ranged Spell Attack: +7 to hit, range 60 ft., one target. *Hit:* 22 (4d10 + 3) radiant damage.


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