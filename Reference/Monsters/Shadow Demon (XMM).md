---
type: pc
race: "Fiend (demon)"
class:
 - "Shadow Demon"
subClass:
 - "CR 4"
cover: "Shadow Demon.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/xmm
---
###### Shadow Demon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shadow Demon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 17 | 12 | 14 | 13 | 14 |
| **Mod** | -5 | +3 | +1 | +2 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Dex +5, Cha +4
**Skills:** Stealth +7
**Damage Vulnerabilities:** radiant
**Damage Resistances:** acid; bludgeoning; cold; fire; lightning; piercing; slashing; thunder
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Demonic Restoration.** If the demon dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Incorporeal Movement.** The demon can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.

**Light Sensitivity.** While in Bright Light, the demon has Disadvantage on ability checks and attack rolls.


---

### Actions

**Umbral Claw.** m +5, reach 5 ft. *Hit:* 16 (3d8 + 3) Psychic damage.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the demon takes the Hide action.


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