---
type: pc
race: "Undead"
class:
 - "Death Knight Aspirant"
subClass:
 - "CR 11"
cover: "Death Knight Aspirant.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/11
  - source/xmm
---
###### Death Knight Aspirant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Knight Aspirant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 18 | 10 | 12 | 16 |
| **Mod** | +5 | +0 | +4 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, Common
**Saving Throws:** Dex +4, Wis +5
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; poisoned

---

### Traits

**Magic Resistance.** The aspirant has Advantage on saving throws against spells and other magical effects.

**Marshal Undead.** Undead creatures of the aspirant's choice (excluding itself) in a 60-foot Emanation originating from it have Advantage on attack rolls and saving throws. It can't use this trait if it has the Incapacitated condition.


---

### Actions

**Multiattack.** The aspirant makes three Dread Blade attacks.

**Dread Blade.** m +9, reach 5 ft. *Hit:* 14 (2d8 + 5) Slashing damage plus 10 (3d6) Necrotic damage.

**Hellfire Orb (Recharge 5–6).** dex DC 15, each creature in a 20-foot-radius Sphere centered on a point the aspirant can see within 120 feet of itself.  21 (6d6) Fire damage plus 21 (6d6) Necrotic damage.  Half damage.


---

### Reactions

**Parry.**  The aspirant is hit by a melee attack roll while holding a weapon.  The aspirant adds 4 to its AC against that attack, possibly causing it to miss.


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