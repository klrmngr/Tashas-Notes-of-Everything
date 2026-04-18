---
type: pc
race: "Fiend (demon)"
class:
 - "Nalfeshnee"
subClass:
 - "CR 13"
cover: "Nalfeshnee.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/13
  - source/xmm
---
###### Nalfeshnee
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Nalfeshnee.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 184 (16d10 + 96) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 22 | 19 | 12 | 15 |
| **Mod** | +5 | +0 | +6 | +4 | +1 | +2 |

**Speed:** 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 11
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Con +11, Int +9, Wis +6, Cha +7
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** frightened; poisoned

---

### Traits

**Demonic Restoration.** If the nalfeshnee dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The nalfeshnee has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The nalfeshnee makes three Rend attacks.

**Rend.** m +10, reach 10 ft. *Hit:* 16 (2d10 + 5) Slashing damage plus 11 (2d10) Force damage.

**Teleport.** The nalfeshnee teleports up to 120 feet to an unoccupied space it can see.


---

### Bonus Actions

**Horror Nimbus (Recharge 5–6).** wis DC 15, each creature in a 15-foot Emanation originating from the nalfeshnee.  28 (8d6) Psychic damage, and the target has the Frightened condition for 1 minute, until it takes damage, or until it ends its turn with the nalfeshnee out of line of sight.  The target is immune to this nalfeshnee's Horror Nimbus for 24 hours.


---

### Reactions

**Pursuit.**  Another creature the nalfeshnee can see ends its move within 120 feet of the nalfeshnee.  The nalfeshnee uses Teleport, but its destination space must be within 10 feet of the triggering creature.


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