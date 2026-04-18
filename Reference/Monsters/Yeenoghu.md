---
type: pc
race: "Fiend (demon)"
class:
 - "Yeenoghu"
subClass:
 - "CR 24"
cover: "Yeenoghu.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/24
  - source/mpmm
---
###### Yeenoghu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Yeenoghu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 333 (23d12 + 184) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 16 | 26 | 16 | 24 | 15 |
| **Mod** | +9 | +3 | +8 | +3 | +7 | +2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +10, Con +15, Wis +14
**Skills:** Intimidation +9, Perception +14
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Yeenoghu fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Yeenoghu has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Yeenoghu makes three Flail attacks.

**Flail.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 22 (2d12 + 9) force damage. If it's his turn, Yeenoghu can cause the target to suffer one of the following additional effects, each of which he can apply only once per turn
- **Confusion.** The target must succeed on a DC 17 Wisdom saving throw or be affected by the confusion spell until the start of Yeenoghu's next turn.
- **Force.** The target takes an extra 13 (2d12) force damage.
- **Paralysis.** The target must succeed on a DC 17 Constitution saving throw or be paralyzed until the start of Yeenoghu's next turn.

**Bite.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 20 (2d10 + 9) acid damage.


---

### Bonus Actions

**Rampage.** When Yeenoghu reduces a creature to 0 hit points with a melee attack, he moves up to half his speed and makes one Bite attack.


---

### Legendary Actions

### 

**Charge.** Yeenoghu moves up to his speed.

**Swat Away.** Yeenoghu makes one Flail attack. If the attack hits, the target must succeed on a DC 24 Strength saving throw or be pushed up to 15 feet in a straight line away from Yeenoghu. If the saving throw fails by 5 or more, the target is also knocked prone.

**Savage (Costs 2 Actions).** Yeenoghu makes a separate Bite attack against each creature within 10 feet of him.


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