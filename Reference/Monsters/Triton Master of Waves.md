---
type: pc
race: "Humanoid (triton)"
class:
 - "Triton Master of Waves"
subClass:
 - "CR 8"
cover: "Triton Master of Waves.png"
campaign:
locations:
tags:
  - race/triton
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mot
---
###### Triton Master of Waves
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Triton Master of Waves.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (triton) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Humanoid (triton) |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 16 | 10 | 12 | 19 |
| **Mod** | +3 | +0 | +3 | +0 | +1 | +4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Primordial
**Saving Throws:** Dex +3, Int +3, Cha +7
**Skills:** Athletics +6, Nature +6, Survival +4
**Damage Resistances:** cold; fire

---

### Traits

**Amphibious.** The triton can breathe air and water.

**Summon Water Weird (Recharges after a Short or Long Rest).** As a bonus action, the triton magically summons 1d4 [[Water Weird|water weirds]]. The summoned weirds appear in unoccupied spaces in water within 60 feet of the triton. The water weirds act immediately after the triton on the same initiative count and fight until they're destroyed. They disappear if the triton dies.


---

### Actions

**Multiattack.** The triton makes two attacks using Wave Touch and casts ray of frost.

**Wave Touch.** Melee Spell Attack: +7 to hit, reach 5 ft., one target. *Hit:* 22 (4d10) cold damage.

**Ray of Frost (Cantrip).** Ranged Spell Attack: +7 to hit, range 60 ft., one creature. *Hit:* 13 (3d8) cold damage, and the target's speed is reduced by 10 feet until the start of the triton's next turn.


---

### Reactions

**Frigid Shield.** When a creature the triton can see targets the triton with an attack, the triton gains 10 temporary hit points. If the attack hits and reduces the temporary hit points to 0, each creature within 5 feet of the triton takes 9 (2d8) cold damage.


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