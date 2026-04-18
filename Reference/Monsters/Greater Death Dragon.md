---
type: pc
race: "Undead"
class:
 - "Greater Death Dragon"
subClass:
 - "CR 14"
cover: "Greater Death Dragon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/14
  - source/dsotdq
---
###### Greater Death Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Greater Death Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 20 | 11 | 14 | 10 |
| **Mod** | +6 | +0 | +5 | +0 | +2 | +0 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +7
**Skills:** Perception +7, Stealth +5
**Damage Resistances:** piercing
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The dragon doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 4 (1d8) necrotic damage. If the target is a Large or smaller creature, it is grappled (escape DC 19). Until this grapple ends, the target is restrained, and the dragon can't bite a different target.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft. one target. *Hit:* 10 (1d8 + 6) slashing damage.

**Cataclysmic Breath (Recharge 5–6).** The dragon exhales a wave of ghostly purple flames in a 60-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 45 (10d8) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creature within the cone, becomes a zombie (see the Monster Manual) under the dragon's control. The zombie acts on the dragon's initiative but immediately after the dragon's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Cataclysmic Rush (Costs 2 Actions).** The dragon moves up to half its flying speed without provoking opportunity attacks, carrying with it any creatures it is grappling. During this move, if it enters the space of a Medium or smaller creature, that creature takes 4 (1d8) necrotic damage. A creature can take this damage only once per turn.


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