---
type: pc
race: "Undead"
class:
 - "Psionic Ashenwight"
subClass:
 - "CR 7"
cover: "Psionic Ashenwight.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/7
  - source/pabtso
---
###### Psionic Ashenwight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Psionic Ashenwight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 15 | 17 | 14 | 6 |
| **Mod** | +4 | +1 | +2 | +3 | +2 | -2 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** telepathy 120 ft., understands the languages it knew in life but can't speak
**Saving Throws:** Str +7, Con +5, Int +6, Wis +5
**Damage Resistances:** necrotic; poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; unconscious

---

### Actions

**Multiattack.** The ashenwight makes two Necrotic Shard attacks. It also uses Psionic Crown if available.

**Necrotic Shard.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 9 (2d8) necrotic damage. If the target is a creature, it has disadvantage on the next attack roll it makes before the end of its next turn.

**Psionic Crown (Recharge 5–6).** The ashenwight wreathes the head of a creature it can see within 60 feet of itself with a crown of jagged, spectral crystals. The target must succeed on a DC 14 Wisdom saving throw or have the charmed condition for 1 minute. While charmed in this way, the target's thoughts are sluggish; it can't take reactions, its speed is halved, and it takes 9 (2d8) psychic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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