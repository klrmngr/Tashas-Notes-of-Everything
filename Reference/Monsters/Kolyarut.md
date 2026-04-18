---
type: pc
race: "Construct (inevitable)"
class:
 - "Kolyarut"
subClass:
 - "CR 20"
cover: "Kolyarut.png"
campaign:
locations:
tags:
  - race/inevitable
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/20
  - source/mpp
---
###### Kolyarut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Kolyarut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Construct (inevitable) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 297 (35d8 + 140) |
> | :FasUserGroup: Race | Construct (inevitable) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 12 | 19 | 25 | 22 | 18 |
| **Mod** | +7 | +1 | +4 | +7 | +6 | +4 |

**Speed:** 50 ft., fly 35 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 22
**Languages:** all
**Saving Throws:** Int +13, Wis +12, Cha +10
**Skills:** History +13, Insight +12, Perception +12
**Damage Resistances:** thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; unconscious

---

### Traits

**Immutable Form.** The kolyarut is immune to any spell or effect that would alter its form.

**Legendary Resistance (4/Day).** If the kolyarut fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The kolyarut has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The kolyarut makes four Unerring Blade attacks.

**Unerring Blade.** Melee Weapon Attack: automatic hit, reach 5 ft., one target. *Hit:* 24 force damage plus one of the following effects (choose one or roll a d6):
- **1-2: Disarm.** The target drops one item it is holding of the kolyarut's choice.
- **3-4: Imbalance.** The target can't take reactions until the start of the kolyarut's next turn.
- **5-6: Push.** If the target is Large or smaller, the target is pushed up to 15 feet away from the kolyarut.

**Edict of Blades (Recharge 5–6).** The kolyarut moves up to its speed without provoking opportunity attacks and can make one Unerring Blade attack against each creature it moves past. Whenever it hits a creature with an Unerring Blade attack during this movement, each spell of 5th level or lower on the creature ends, and the creature has the incapacitated condition until the end of the kolyarut's next turn.

**Plane Shift (3/Day).** The kolyarut casts plane shift, requiring no material components and using Intelligence as the spellcasting ability. The kolyarut can cast the spell normally, or it can cast the spell on an unwilling creature it can see within 60 feet of itself. If it uses the latter option, the targeted creature must succeed on a DC 18 Charisma saving throw or be sent to a teleportation circle in the Hall of Concordance in Sigil.


---

### Reactions

**Parry.** The kolyarut adds 6 to its AC against one attack roll that would hit it. To do so, the kolyarut must see the attacker and be wielding a melee weapon.


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