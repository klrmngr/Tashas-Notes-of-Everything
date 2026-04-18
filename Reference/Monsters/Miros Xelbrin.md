---
type: pc
race: "Humanoid (human)"
class:
 - "Miros Xelbrin"
subClass:
 - "CR —"
cover: "Miros Xelbrin.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Miros Xelbrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Miros Xelbrin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 11 | 12 | 14 |
| **Mod** | +3 | +0 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Skills:** Intimidation +4, Perception +3

---

### Traits

**Roleplaying Information.** Innkeeper Miros is a retired carnival attraction, dubbed "the Yeti" because of his barrel-shaped body and the thick, white hair covering his arms, chest, back, and head. When Goldenfields suffers, so does his business, so he takes strides to protect the compound.
Ideal: "As does the Emerald Enclave, I believe that civilization and the wilderness need to learn to coexist."
Bond: "Make fun of me all you like, but don't speak ill of my inn or my employees."
Flaw: "When something upsets me, I have a tendency to fly into a rage."


---

### Actions

**Bear Hug.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) bludgeoning damage, and the target grappled (escape DC 13) and takes 5 (1d4 + 3) bludgeoning damage at the start of each of Miros's turns until the grapple ends. Miros cannot make attacks while grappling a creature.

**Club.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 1) bludgeoning damage.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage. Miros carries ten crossbow bolts.


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