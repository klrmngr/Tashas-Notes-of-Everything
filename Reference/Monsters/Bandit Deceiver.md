---
type: pc
race: "Humanoid"
class:
 - "Bandit Deceiver"
subClass:
 - "CR 7"
cover: "Bandit Deceiver.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/xmm
---
###### Bandit Deceiver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bandit Deceiver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 14 | 17 | 12 | 16 |
| **Mod** | -1 | +3 | +2 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +6, Int +6
**Skills:** Acrobatics +6, Perception +4, Stealth +9

---

### Actions

**Multiattack.** The bandit makes three Dagger attacks.

**Dagger.** m,r +6, reach 5 ft. or range 20/60 ft. *Hit:* 8 (2d4 + 3) Piercing damage plus 10 (3d6) Poison damage.

**Blinding Flash (Recharge 4–6).** con DC 14, each creature in a 10-foot-radius Sphere centered on a point the bandit can see within 120 feet.  13 (3d6 + 3) Radiant damage, and the target has the Blinded condition until the start of the bandit's next turn.  Half damage only.


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