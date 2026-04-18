---
type: pc
race: "Elemental"
class:
 - "Flail Snail"
subClass:
 - "CR 3"
cover: "Flail Snail.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/mpmm
---
###### Flail Snail
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Flail Snail.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (5d10 + 25) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 5 | 20 | 3 | 10 | 5 |
| **Mod** | +3 | -3 | +5 | -4 | +0 | -3 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Antimagic Shell.** The snail has advantage on saving throws against spells, and any creature making a spell attack against the snail has disadvantage on the attack roll.
If the snail succeeds on its saving throw against a spell or a spell's attack roll misses it, the snail's shell converts some of the spell's energy into a burst of destructive force if the spell is of 1st level or higher; each creature within 30 feet of the snail must make a DC 15 Constitution saving throw, taking 3 (1d6) force damage per level of the spell on a failed save, or half as much damage on a successful one.


---

### Actions

**Multiattack.** The snail makes five Flail Tentacle attacks.

**Flail Tentacle.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.

**Scintillating Shell (Recharges after a Short or Long Rest).** The snail's shell emits dazzling, colored light until the end of the snail's next turn. During this time, the shell sheds bright light in a 30-foot radius and dim light for an additional 30 feet, and creatures that can see the snail have disadvantage on attack rolls against it. In addition, any creature within the bright light and able to see the snail when this power is activated must succeed on a DC 15 Wisdom saving throw or be stunned until the light ends.

**Shell Defense.** The flail snail withdraws into its shell. Until it emerges, it gains a +4 bonus to its AC and is restrained. It can emerge from its shell as a bonus action on its turn.


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