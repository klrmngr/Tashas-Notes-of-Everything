---
type: pc
race: "Undead"
class:
 - "Graveyard Revenant"
subClass:
 - "CR 7"
cover: "Graveyard Revenant.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/7
  - source/xmm
---
###### Graveyard Revenant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Graveyard Revenant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 161 (14d12 + 70) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 20 | 13 | 16 | 18 |
| **Mod** | +5 | +2 | +5 | +1 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Common plus two other languages
**Saving Throws:** Str +8, Con +8, Wis +6, Cha +7
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned; unconscious

---

### Traits

**Undead Restoration.** If the revenant dies, it revives 24 hours later unless Dispel Evil and Good is cast on its remains. If it revives, it animates another group of corpses elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.


---

### Actions

**Multiattack.** The revenant makes two Suffocate attacks.

**Suffocate.** m +8, reach 10 ft. *Hit:* 10 (1d10 + 5) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 15). Until the grapple ends, the target is suffocating. The revenant can have up to two targets Grappled in this way at a time.

**Haunting Glare (Recharge 5–6).** wis DC 15, each creature in a 30-foot Emanation originating from the revenant.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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