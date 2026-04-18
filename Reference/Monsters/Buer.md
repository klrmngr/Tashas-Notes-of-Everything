---
type: pc
race: "Fiend (devil)"
class:
 - "Buer"
subClass:
 - "CR 21"
cover: "Buer.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/21
  - source/coa
---
###### Buer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Buer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 315 (30d10 + 150) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 22 | 21 | 16 | 18 | 17 |
| **Mod** | +6 | +6 | +5 | +3 | +4 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +15, Dex +13, Con +14
**Skills:** Arcana +10, Athletics +22, Insight +11, Intimidation +17, Perception +11, Survival +11
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Contractually Obligated.** Buer has advantage to hit creatures under an infernal contract and when she hits such creatures she delivers an additional 9 (2d8) damage of a type the target is most vulnerable to. A creature bound under an infernal contract also makes all saving throws against effects originating from Buer with disadvantage.

**Devil's Sight.** Magical darkness doesn't impede Buer's darkvision.

**Magic Resistance.** Buer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Buer makes three attacks using her Claw. She can replace two of the attacks with a Cleansing Bite attack.

**Claw.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 22 (3d10 + 6) slashing damage.

**Cleansing Bite.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 19 (2d12 + 6) bludgeoning damage, healing Buer for an amount equal to the damage dealt.

**Spectral Reaping (Recharge 6).** Buer focuses her ethereal form, dashing up to 50 feet in a straight line through the ethereal plane. Any creatures in the line must make a DC 21 Constitution saving throw, taking 42 (12d6) force damage on a failed save, or half as much damage on a successful one. Buer may reappear at any unoccupied space along the line. For 1 minute after using Spectral Reaping, Buer is empowered by ethereal essence. Her Cleansing Bite attack now deals force damage instead of bludgeoning.


---

### Bonus Actions

**Defensive Trip (Recharge 5–6).** Buer attempts to slow the actions of a creature she can see within 60 feet of her. The target must succeed on a DC 18 Wisdom saving throw or be slowed until the end of its next turn. A slowed creature's speed is halved, it takes a-2 penalty to AC and Dexterity saving throws, and it can't use its reactions. Regardless of the slowed creature's abilities or magic items, it can't make more than one melee or ranged attack during its turn.


---

### Reactions

**Soul Exchange.** When Buer is subjected to a spell targeting only her, she can attempt to swap places with a creature she damaged on her last turn. The creature must make a DC 19 Wisdom saving throw. On a failed save, the creature and Buer swap positions, and the spell now targets the creature instead of Buer.


---

### Legendary Actions

### 

**Teamwork.** Buer or one other devil within 60 feet of Buer makes a melee weapon attack against a target of Buer's choosing.

**Backdoor Clause.** Buer wreathes energy around a creature she can see within 60 feet of her. Until the end of Buer's next turn, the target is covered in fire or cold energy, Buer's choice. Each time the target is struck with a melee attack, the attacker takes 9 (2d8) fire or cold damage.

**Refresh Souls (Costs 2 Actions).** Buer devours a Soul Coin, instantly refreshing one Recharge ability of any devil within 60 feet, including herself.


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