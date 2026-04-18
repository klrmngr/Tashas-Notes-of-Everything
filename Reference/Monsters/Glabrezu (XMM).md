---
type: pc
race: "Fiend (demon)"
class:
 - "Glabrezu"
subClass:
 - "CR 9"
cover: "Glabrezu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/xmm
---
###### Glabrezu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Glabrezu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 21 | 19 | 17 | 16 |
| **Mod** | +5 | +2 | +5 | +4 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 17
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Str +9, Con +9, Wis +7, Cha +7
**Skills:** Deception +7, Perception +7
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the glabrezu dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The glabrezu has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The glabrezu makes two Pincer attacks and uses Pummel or Spellcasting.

**Pincer.** m +9, reach 10 ft. *Hit:* 16 (2d10 + 5) Slashing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 15) from one of two pincers.

**Pummel.** dex DC 17, one creature Grappled by the glabrezu.  15 (3d6 + 5) Bludgeoning damage.  Half damage.


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