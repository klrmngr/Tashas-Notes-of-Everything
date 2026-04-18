---
type: pc
race: "Undead"
class:
 - "Lesser Death Dragon"
subClass:
 - "CR 10"
cover: "Lesser Death Dragon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/10
  - source/dsotdq
---
###### Lesser Death Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Lesser Death Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 199 (21d10 + 84) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 18 | 5 | 10 | 5 |
| **Mod** | +5 | +0 | +4 | -3 | +0 | -3 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 14
**Languages:** understands Common and Draconic but can't speak
**Saving Throws:** Dex +4, Wis +4
**Skills:** Perception +4, Stealth +4
**Damage Resistances:** piercing
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Unusual Nature.** The dragon doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage plus 4 (1d8) necrotic damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft. one target. *Hit:* 8 (1d6 + 5) slashing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 15). Until this grapple ends, the target is restrained. The dragon has two claws, each of which can grapple one target.

**Cataclysmic Breath (Recharge 5–6).** The dragon exhales a wave of ghostly purple flames in a 30-foot cone. Each creature in that area must make a DC 16 Dexterity saving throw, taking 36 (8d8) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creatures within the cone, becomes a zombie (see the Monster Manual) under the dragon's control. The zombie acts on the dragon's initiative but immediately after the dragon's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.


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