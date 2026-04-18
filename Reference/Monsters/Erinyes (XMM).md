---
type: pc
race: "Fiend (devil)"
class:
 - "Erinyes"
subClass:
 - "CR 12"
cover: "Erinyes.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/xmm
---
###### Erinyes
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Erinyes.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 18 | 14 | 14 | 18 |
| **Mod** | +4 | +3 | +4 | +2 | +2 | +4 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 16
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Dex +7, Con +8, Cha +8
**Skills:** Perception +6, Persuasion +8
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the erinyes dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The erinyes has Advantage on saving throws against spells and other magical effects.

**Magic Rope.** The erinyes has a magic rope. While bearing it, the erinyes can use the Entangling Rope action. The rope has AC 20, HP 90, and Immunity to Poison and Psychic damage. The rope turns to dust if reduced to 0 Hit Points, if it is 5+ feet away from the erinyes for 1 hour or more, or if the erinyes dies. If the rope is damaged or destroyed, the erinyes can fully restore it when finishing a Short or Long Rest.


---

### Actions

**Multiattack.** The erinyes makes three Withering Sword attacks and can use Entangling Rope.

**Withering Sword.** m +8, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage plus 11 (2d10) Necrotic damage.

**Entangling Rope (Requires Magic Rope).** str DC 16, one creature the erinyes can see within 120 feet.  14 (4d6) Force damage, and the target has the Restrained condition until the rope is destroyed, the erinyes uses a Bonus Action to release the target, or the erinyes uses Entangling Rope again.


---

### Reactions

**Parry.**  The erinyes is hit by a melee attack roll while holding a weapon.  The erinyes adds 4 to its AC against that attack, possibly causing it to miss.


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