---
type: pc
race: "Undead"
class:
 - "Barrowghast"
subClass:
 - "CR 7"
cover: "Barrowghast.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/7
  - source/bgg
---
###### Barrowghast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Barrowghast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 8 | 20 | 5 | 9 | 6 |
| **Mod** | +5 | -1 | +5 | -3 | -1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Giant
**Damage Resistances:** necrotic; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Stench.** Any creature that starts its turn within 10 feet of the barrowghast must make a DC 16 Constitution saving throw. On a failed save, the creature has the poisoned condition for 1 minute. While poisoned this way, the creature can't regain hit points. On a successful save, the creature is immune to the Stench of all barrowghasts for 24 hours.


---

### Actions

**Multiattack.** The barrowghast makes two Slam attacks. It can replace one Slam attack with a Life Drain attack.

**Slam.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (2d12 + 5) bludgeoning damage.

**Life Drain.** Melee Weapon Attack: +8 to hit, reach 10 ft., one creature. *Hit:* 9 (1d8 + 5) necrotic damage, and the target must succeed on a DC 16 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.
A Humanoid slain by this attack immediately rises as a zombie (see the Monster Manual). The zombie acts as an ally of the barrowghast but isn't under its control.


---

### Reactions

**Noxious Wound.** Immediately after the barrowghast takes piercing or slashing damage, poisonous ichor sprays from the wound. Each creature within 5 feet of the barrowghast must make a DC 16 Dexterity saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.


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