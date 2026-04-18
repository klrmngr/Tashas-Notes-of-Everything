---
type: pc
race: "Construct"
class:
 - "Deck Defender"
subClass:
 - "CR —"
cover: "Deck Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/bmt
---
###### Deck Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Deck Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 5 + five times your level (the deck defender has a number of Hit Dice [d8s] equal to your level) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 14 | 3 | 10 | 1 |
| **Mod** | +3 | +3 | +2 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
**Languages:** understands one of your languages but can't speak
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Allied Knight.** Some of the deck defender's statistics are based on the character who drew the Knight card. Where the deck defender stat block refers to "you," it refers to that character.

**Folded Versatility.** After finishing a long rest, you can refold the deck defender's shape, changing it to acrobat form, berserker form, or guardian form.

**Fragile.** If the deck defender is reduced to 0 hit points, it collapses into a haphazard pile of nonmagical playing cards and can't be resurrected or reconstructed.


---

### Actions

**Multiattack.** The deck defender makes a number of attacks equal to half its proficiency bonus (rounded down).

**Paper Cut.** Melee Weapon Attack: PB + +3 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.

**Reckless Strike (Berserker Form Only).** Melee Weapon Attack: PB + +3 to hit (with advantage), reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage, and attacks made against the deck defender until the start of its next turn have advantage.


---

### Bonus Actions

**Swift Step (Acrobat Form Only).** The deck defender takes the Dash or Disengage action.


---

### Reactions

**Protection (Guardian Form Only).** When a creature the deck defender can see attacks a target other than the deck defender and is within 5 feet of the deck defender, the deck defender imposes disadvantage on the attack roll.


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