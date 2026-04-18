---
type: pc
race: "Humanoid (ranger, genasi)"
class:
 - "Ayo Jabe (Tier 3)"
subClass:
 - "CR 8"
cover: "Ayo Jabe (Tier 3).png"
campaign:
locations:
tags:
  - race/ranger
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/crcotn
---
###### Ayo Jabe (Tier 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Ayo Jabe (Tier 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (ranger, genasi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 (studded leather) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (ranger, genasi) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 20 | 16 | 10 | 16 | 14 |
| **Mod** | +3 | +5 | +3 | +0 | +3 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Goblin, Orc
**Saving Throws:** Str +6, Dex +8
**Skills:** Athletics +6, Perception +6, Survival +6
**Damage Resistances:** acid
**Condition Immunities:** frightened

---

### Traits

**Amphibious.** Ayo can breathe air and water.

**Special Equipment.** Ayo wields a ruidium harpoon (see appendix B). If Ayo rolls a 1 on an attack roll made with the harpoon, she must succeed on a DC 20 Charisma saving throw or gain 1 level of exhaustion.


---

### Actions

**Multiattack.** Ayo makes three Harpoon or Longbow attacks.

**Ruidium Harpoon.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage plus 7 (2d6) psychic damage.

**Longbow.** Ranged Weapon Attack: +8 to hit, range 150/600 ft., one target. *Hit:* 18 (3d8 + 5) piercing damage.


---

### Bonus Actions

**Reposition.** Ayo issues orders to one ally she can see within 30 feet of herself. If the target can see or hear Ayo, it can spend its reaction to move up to its speed. This movement doesn't provoke opportunity attacks.


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