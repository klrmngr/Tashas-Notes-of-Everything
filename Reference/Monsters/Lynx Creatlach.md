---
type: pc
race: "Undead (tiefling)"
class:
 - "Lynx Creatlach"
subClass:
 - "CR 5"
cover: "Lynx Creatlach.png"
campaign:
locations:
tags:
  - race/tiefling
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/imr
---
###### Lynx Creatlach
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Lynx Creatlach.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead (tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Undead (tiefling) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 13 | 16 | 18 |
| **Mod** | +4 | +2 | +4 | +1 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Infernal
**Saving Throws:** Str +7, Con +7, Wis +6, Cha +7
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Special Equipment.** Lynx's crystal eye is a magically shrunken crystal ball of true seeing. One of her teeth is a refashioned ring of mind shielding, while another has been magicked to place her under a permanent Nystul's magic aura spell, concealing the magic of these items and hiding her true nature from magic or features that can detect undead.

**Aversion of Fire.** If Lynx takes fire damage, she has disadvantage on attack rolls and ability checks until the end of her next turn.

**Immutable Form.** Lynx is immune to any spell or effect that would alter her form.

**Lightning Absorption.** Whenever Lynx is subjected to lightning damage, she takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

**Magic Resistance.** Lynx has advantage on saving throws against spells and other magical effects.

**Regeneration.** Lynx regains 10 hit points at the start of her turn. If she takes fire or radiant damage, this trait doesn't function at the start of her next turn. Lynx's body is destroyed only if she starts her turn with 0 hit points and doesn't regenerate.

**Turn Immunity.** Lynx is immune to effects that turn undead.


---

### Actions

**Multiattack.** Lynx makes two shortsword attacks.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


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