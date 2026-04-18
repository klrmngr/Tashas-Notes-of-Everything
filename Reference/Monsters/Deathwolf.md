---
type: pc
race: "Undead"
class:
 - "Deathwolf"
subClass:
 - "CR 15"
cover: "Deathwolf.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/15
  - source/veor
---
###### Deathwolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Deathwolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 10 | 17 | 19 |
| **Mod** | +5 | +3 | +4 | +0 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 23
**Languages:** Common
**Saving Throws:** Str +10, Dex +8, Cha +9
**Skills:** Perception +13, Stealth +8
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (2/Day).** If the deathwolf fails a saving throw, it can choose to succeed instead.

**Moon's Grace.** When the deathwolf falls, it descends at a rate of 60 feet per round and takes no falling damage.


---

### Actions

**Multiattack.** The deathwolf makes one Bite attack and two Claw attacks. It can replace one of these attacks with Phantom Deathwolf if available.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage plus 9 (2d8) necrotic damage. The target must succeed on a DC 16 Wisdom saving throw or have disadvantage on saving throws against the frightened condition. This curse lasts until removed by the Remove Curse spell or other magic.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 4 (1d8) necrotic damage.

**Phantom Deathwolf (Recharge 5–6).** The deathwolf creates a terrifying phantom of itself in the mind of a creature the deathwolf can see within 60 feet of itself. The target must succeed on a DC 17 Intelligence saving throw or have the frightened condition for 1 minute.
While the target is frightened, the phantom deals 21 (6d6) psychic damage to the target at the start of each of the target's turns. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Imposing Slash.** When a creature within 5 feet of the deathwolf makes an attack roll against it, the deathwolf forces the creature to succeed on a DC 17 Wisdom saving throw or have disadvantage on that roll. After the attack hits or misses, the deathwolf makes one Claw attack against the creature.

**Phase Step.** Immediately after taking damage, the deathwolf teleports up to 30 feet to an unoccupied space it can see that is in dim light or darkness.


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