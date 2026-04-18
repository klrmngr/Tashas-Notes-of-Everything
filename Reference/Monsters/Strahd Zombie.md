---
type: pc
race: "Undead"
class:
 - "Strahd Zombie"
subClass:
 - "CR 1"
cover: "Strahd Zombie.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/cos
---
###### Strahd Zombie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Strahd Zombie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 6 | 16 | 3 | 6 | 5 |
| **Mod** | +1 | -2 | +3 | -4 | -2 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Wis +0
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Loathsome Limbs.** Whenever the zombie takes at least 5 bludgeoning or slashing damage at one time, roll a d20 to determine what else happens to it:
1–8: One leg is severed from the zombie if it has any legs left.
9–16: One arm is severed from the zombie if it has any arms left.
17–20: The zombie is decapitated.
If the zombie is reduced to 0 hit points, all parts of it die. Until then, a severed part acts on the zombie's initiative and has its own action and movement. A severed part has AC 8. Any damage it takes is subtracted from the zombie's hit points.
A severed leg is unable to attack and has a speed of 5 feet.
A severed arm has a speed of 5 feet and can make one claw attack on its turn, with disadvantage on the attack roll. Each time the zombie loses an arm, it loses a claw attack.
If its head is severed, the zombie loses its bite attack and its body is blinded unless the head can see it. The severed head has a speed of 0 feet. It can make a bite attack, but only against a target in its space.
The zombie's speed is halved if it's missing a leg. If it loses both legs, it falls prone. If it has both arms, it can crawl. With only one arm, it can still crawl, but its speed is halved. With no arms or legs, its speed is 0 feet, and it can't benefit from bonuses to speed.


---

### Actions

**Multiattack.** The zombie makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.


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