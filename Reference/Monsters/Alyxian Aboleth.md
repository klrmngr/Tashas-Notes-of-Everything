---
type: pc
race: "Aberration"
class:
 - "Alyxian Aboleth"
subClass:
 - "CR 12"
cover: "Alyxian Aboleth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/12
  - source/crcotn
---
###### Alyxian Aboleth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian Aboleth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 15 | 18 | 18 | 18 |
| **Mod** | +5 | -1 | +2 | +4 | +4 | +4 |

**Speed:** 10 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 22
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Con +6, Int +8, Wis +8
**Skills:** History +12, Perception +12

---

### Traits

**Amphibious.** The aboleth can breathe air and water.

**Mucous Cloud.** While underwater, the aboleth is surrounded by a cloud of sticky mucus. A creature that touches the aboleth or hits it with a melee attack while within 5 feet of it must succeed on a DC 14 Strength saving throw or be restrained until the end of the aboleth's next turn.

**Probing Telepathy.** If a creature the aboleth can see communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires.


---

### Actions

**Multiattack.** The aboleth makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage plus 3 (1d6) psychic damage.

**Tail.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage.


---

### Bonus Actions

**Enslave (Recharge 4–6).** The aboleth targets one creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be magically charmed by the aboleth until the aboleth dies or until it is on a different plane of existence from the target. The charmed target is under the aboleth's control and can't take reactions, and the aboleth and the target can communicate telepathically with each other over any distance.
The charmed target can repeat the saving throw whenever it takes damage, ending the effect on itself on a success. No more than once every 24 hours, the target can repeat the saving throw when it is at least 1 mile away from the aboleth.


---

### Legendary Actions

### 

**Tail Swipe.** The aboleth makes one Tail attack.

**Psychic Drain (Costs 2 Actions).** One creature charmed by the aboleth takes 10 (3d6) psychic damage, and the aboleth regains hit points equal to the damage dealt.


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