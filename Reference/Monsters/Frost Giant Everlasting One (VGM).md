---
type: pc
race: "Giant (frost giant)"
class:
 - "Frost Giant Everlasting One"
subClass:
 - "CR 12"
cover: "Frost Giant Everlasting One.png"
campaign:
locations:
tags:
  - race/frost giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/12
  - source/vgm
---
###### Frost Giant Everlasting One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Frost Giant Everlasting One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Giant (frost giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (patchwork armor) |
> | :FasHeart: HP | 189 (14d12 + 98) |
> | :FasUserGroup: Race | Giant (frost giant) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 9 | 24 | 9 | 10 | 12 |
| **Mod** | +7 | -1 | +7 | -1 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Giant
**Saving Throws:** Str +11, Con +11, Wis +4
**Skills:** Athletics +11, Perception +4
**Damage Immunities:** cold

---

### Traits

**Extra Heads.** The giant has a 25 chance of having more than one head. If it has more than one, it has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, or knocked unconscious.

**Regeneration.** The giant regains 10 hit points at the start of its turn. If the giant takes acid or fire damage, this trait doesn't function at the start of its next turn. The giant dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Vaprak's Rage (Recharges after a Short or Long Rest).** As a bonus action, the giant can enter a rage at the start of its turn. The rage lasts for 1 minute or until the giant is incapacitated. While raging, the giant gains the following benefits:
- The giant has advantage on Strength checks and Strength saving throws
- When it makes a melee weapon attack, the giant gains a +4 bonus to the damage roll.
- The giant has resistance to bludgeoning, piercing, and slashing damage.


---

### Actions

**Multiattack.** The giant makes two attacks with its greataxe.

**Greataxe.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 26 (3d12 + 7) slashing damage, or 30 (3d12 + 11) slashing damage while raging.

**Rock.** Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. *Hit:* 29 (4d10 + 7) bludgeoning damage.


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