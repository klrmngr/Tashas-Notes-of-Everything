---
type: pc
race: "Fiend (demon)"
class:
 - "Marilith"
subClass:
 - "CR 16"
cover: "Marilith.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/16
  - source/xmm
---
###### Marilith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Marilith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 220 (21d10 + 105) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 20 | 20 | 18 | 16 | 20 |
| **Mod** | +4 | +5 | +5 | +4 | +3 | +5 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 18
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Str +9, Con +10, Wis +8, Cha +10
**Skills:** Perception +8
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the marilith dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The marilith has Advantage on saving throws against spells and other magical effects.

**Reactive.** The marilith can take one Reaction on every turn of combat.


---

### Actions

**Multiattack.** The marilith makes six Pact Blade attacks and uses Constrict.

**Pact Blade.** m +10, reach 5 ft. *Hit:* 10 (1d10 + 5) Slashing damage plus 7 (2d6) Necrotic damage.

**Constrict.** str DC 17, one Medium or smaller creature the marilith can see within 5 feet.  15 (2d10 + 4) Bludgeoning damage. The target has the Grappled condition (escape DC 14), and it has the Restrained condition until the grapple ends.


---

### Bonus Actions

**Teleport (Recharge 5–6).** The marilith teleports up to 120 feet to an unoccupied space it can see.


---

### Reactions

**Parry.**  The marilith is hit by a melee attack roll while holding a weapon.  The marilith adds 5 to its AC against that attack, possibly causing it to miss.


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