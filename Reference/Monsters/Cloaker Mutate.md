---
type: pc
race: "Aberration"
class:
 - "Cloaker Mutate"
subClass:
 - "CR 10"
cover: "Cloaker Mutate.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/10
  - source/pabtso
---
###### Cloaker Mutate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Cloaker Mutate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 143 (22d10 + 22) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 12 | 18 | 13 | 11 |
| **Mod** | +4 | +2 | +1 | +4 | +1 | +0 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Deep Speech, telepathy 60 ft., Undercommon
**Skills:** Stealth +6
**Damage Resistances:** necrotic; poison; psychic
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Avoidance.** If the mutate is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Light Sensitivity.** While in bright light, the mutate has disadvantage on attack rolls.


---

### Actions

**Multiattack.** The mutate makes one Corpse Swipe attack and two Tail attacks, or it makes four Tail attacks.

**Corpse Swipe.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 20 (3d10 + 4) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the poisoned condition for 1 minute. While poisoned in this way, a creature can't regain hit points.

**Tail.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.


---

### Bonus Actions

**Phantasmal Duplicates.** The mutate magically projects up to four illusory copies of itself. These duplicates make it difficult to ascertain the mutate's true location and last until the end of the mutate's next turn. While the copies exist, attack rolls against the mutate are made with disadvantage.

**Psychic Moan (Recharge 6).** The mutate lets out a moan charged with psychic energy. Each creature within 60 feet of the mutate that isn't an Aberration must succeed on a DC 16 Wisdom saving throw or take 17 (5d6) psychic damage and have the frightened condition until the end of the mutate's next turn.


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