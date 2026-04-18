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
  - source/vgm
---
###### Flail Snail
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
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
> | :FasBook: Source | Volo's Guide to Monsters |

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

**Antimagic Shell.** The snail has advantage on saving throws against spells, and any creature making a spell attack against the snail has disadvantage on the attack roll. If the snail succeeds on its saving throw against a spell or a spell attack misses it, an additional effect might occur, as determined by rolling a d6:
- If the spell affects an area or has multiple targets, it fails and has no effect. If the spell targets only the snail, it has no effect on the snail and is reflected back at the caster, using the spell slot level, spell save DC, attack bonus, and spellcasting ability of the caster.
- No additional effect.
- The snail's shell converts some of the spell's energy into a burst of destructive force. Each creature within 30 feet of the snail must make a DC 15 Constitution saving throw, taking 1d6 force damage per level of the spell on a failed save, or half as much damage on a successful one.

**Flail Tentacles.** The flail snail has five flail tentacles. Whenever the snail takes 10 damage or more on a single turn, one of its tentacles dies. If even one tentacle remains, the snail regrows all dead ones within 1d4 days. If all its tentacles die, the snail retracts into its shell, gaining 3, and it begins wailing, a sound that can be heard for 600 feet, stopping only when it dies 5d6 minutes later. Healing magic that restores limbs, such as the regenerate spell, can halt this dying process.


---

### Actions

**Multiattack.** The flail snail makes as many flail tentacle attacks as it has flail tentacles, all against the same target.

**Flail Tentacle.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.

**Scintillating Shell (Recharges after a Short or Long Rest).** The snail's shell emits dazzling, colored light until the end of the snail's next turn. During this time, the shell sheds bright light in a 30-foot radius and dim light for an additional 30 feet, and creatures that can see the snail have disadvantage on attack rolls against it. In addition, any creature within the bright light and able to see the snail when this power is activated must succeed on a DC 15 Wisdom saving throw or be stunned until the light ends.

**Shell Defense.** The flail snail withdraws into its shell, gaining a +4 bonus to AC until it emerges. It can emerge from its shell as a bonus action on its turn.


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