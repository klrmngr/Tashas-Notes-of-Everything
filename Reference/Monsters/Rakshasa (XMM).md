---
type: pc
race: "Fiend"
class:
 - "Rakshasa"
subClass:
 - "CR 13"
cover: "Rakshasa.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/xmm
---
###### Rakshasa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Rakshasa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 221 (26d8 + 104) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 18 | 13 | 16 | 20 |
| **Mod** | +2 | +3 | +4 | +1 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 18
**Languages:** Common, Infernal
**Skills:** Deception +10, Insight +8, Perception +8
**Damage Vulnerabilities:** piercing damage from weapons wielded by creatures under the effect of a Bless spell
**Condition Immunities:** charmed; frightened

---

### Traits

**Greater Magic Resistance.** The rakshasa automatically succeeds on saving throws against spells and other magical effects, and the attack rolls of spells automatically miss it. Without the rakshasa's permission, no spell can observe the rakshasa remotely or detect its thoughts, creature type, or alignment.

**Fiendish Restoration.** If the rakshasa dies outside the Nine Hells, its body turns to ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.


---

### Actions

**Multiattack.** The rakshasa makes three Cursed Touch attacks.

**Cursed Touch.** m +10, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 19 (3d12) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target gains no benefit from finishing a Short or Long Rest.

**Baleful Command (Recharge 5–6).** wis DC 18, each enemy in a 30-foot Emanation originating from the rakshasa.  28 (8d6) Psychic damage, and the target has the Frightened and Incapacitated conditions until the start of the rakshasa's next turn.


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