---
type: pc
race: "Aberration"
class:
 - "Aboleth"
subClass:
 - "CR 10"
cover: "Aboleth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/10
  - source/mm
---
###### Aboleth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Aboleth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 15 | 18 | 15 | 18 |
| **Mod** | +5 | -1 | +2 | +4 | +2 | +4 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Con +6, Int +8, Wis +6
**Skills:** History +12, Perception +10

---

### Traits

**Amphibious.** The aboleth can breathe air and water.

**Mucous Cloud.** While underwater, the aboleth is surrounded by transformative mucus. A creature that touches the aboleth or that hits it with a melee attack while within 5 feet of it must make a DC 14 Constitution saving throw. On a failure, the creature is diseased for 1d4 hours. The diseased creature can breathe only underwater.

**Probing Telepathy.** If a creature communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires if the aboleth can see the creature.


---

### Actions

**Multiattack.** The aboleth makes three tentacle attacks.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or become diseased. The disease has no effect for 1 minute and can be removed by any magic that cures disease. After 1 minute, the diseased creature's skin becomes translucent and slimy, the creature can't regain hit points unless it is underwater, and the disease can be removed only by heal or another disease-curing spell of 6th level or higher. When the creature is outside a body of water, it takes 6 (1d12) acid damage every 10 minutes unless moisture is applied to the skin before 10 minutes have passed.

**Tail.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 15 (3d6 + 5) bludgeoning damage.

**Enslave (3/Day).** The aboleth targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom saving throw or be magically charmed by the aboleth until the aboleth dies or until it is on a different plane of existence from the target. The charmed target is under the aboleth's control and can't take reactions, and the aboleth and the target can communicate telepathically with each other over any distance.
Whenever the charmed target takes damage, the target can repeat the saving throw. On a success, the effect ends. No more than once every 24 hours, the target can also repeat the saving throw when it is at least 1 mile away from the aboleth.


---

### Legendary Actions

### 

**Detect.** The aboleth makes a Wisdom (Perception) check.

**Tail Swipe.** The aboleth makes one tail attack.

**Psychic Drain (Costs 2 Actions).** One creature charmed by the aboleth takes 10 (3d6) psychic damage, and the aboleth regains hit points equal to the damage the creature takes.


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