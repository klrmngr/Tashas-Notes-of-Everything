---
type: pc
race: "Undead"
class:
 - "Death Knight"
subClass:
 - "CR 17"
cover: "Death Knight.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/17
  - source/xmm
---
###### Death Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 199 (21d8 + 105) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 20 | 12 | 16 | 18 |
| **Mod** | +5 | +0 | +5 | +1 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Abyssal, Common
**Saving Throws:** Dex +6, Wis +9
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the death knight fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The death knight has Advantage on saving throws against spells and other magical effects.

**Marshal Undead.** Undead creatures of the death knight's choice (excluding itself) in a 60-foot Emanation originating from it have Advantage on attack rolls and saving throws. It can't use this trait if it has the Incapacitated condition.

**Undead Restoration.** If the death knight is destroyed before it atones for its evil, it gains a new body in 1d10 days, reviving with all its Hit Points. The new body appears in a location significant to the death knight.


---

### Actions

**Multiattack.** The death knight makes three Dread Blade attacks.

**Dread Blade.** m +11, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 13 (3d8) Necrotic damage.

**Hellfire Orb (Recharge 5–6).** dex DC 18, each creature in a 20-foot-radius Sphere centered on a point the death knight can see within 120 feet.  35 (10d6) Fire damage plus 35 (10d6) Necrotic damage.  Half damage.


---

### Reactions

**Parry.**  The death knight is hit by a melee attack roll while holding a weapon.  The death knight adds 6 to its AC against that attack, possibly causing it to miss.


---

### Legendary Actions

### 

**Dread Authority.** The death knight uses Spellcasting to cast Command. The death knight can't take this action again until the start of its next turn.

**Fell Word.** con DC 18, one creature the death knight can see within 120 feet.  17 (5d6) Necrotic damage, and the target's Hit Point maximum decreases by an amount equal to the damage taken.  The death knight can't take this action again until the start of its next turn.

**Lunge.** The death knight moves up to half its Speed, and it makes one Dread Blade attack.


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