---
type: pc
race: "Aberration"
class:
 - "Encephalon Cluster"
subClass:
 - "CR 10"
cover: "Encephalon Cluster.png"
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
###### Encephalon Cluster
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Encephalon Cluster.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 110 (17d10 + 17) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 13 | 5 | 17 | 7 |
| **Mod** | +6 | +0 | +1 | -3 | +3 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 13
**Languages:** —
**Damage Resistances:** psychic
**Condition Immunities:** blinded

---

### Traits

**Legendary Resistance (3/Day).** If the cluster fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cluster has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The cluster makes two Slam attacks. It can replace one of these attacks with Spawn Progeny if available.

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) bludgeoning damage plus 10 (3d6) psychic damage, and if the target is a creature, the target must succeed on a DC 18 Strength saving throw or have the prone condition. If this attack reduces the target to 0 hit points, the target immediately dies and is consumed by the cluster.

**Spawn Progeny (Recharges after a Short or Long Rest).** The cluster bulges and spews 1d4 mature eggs. Each egg lands in an unoccupied space of the cluster's choice within 30 feet of itself and immediately transforms into an encephalon gemmule. The gemmules obey the cluster's commands and take their turns immediately after it.


---

### Reactions

**Aggressive Hunger.** Immediately after being hit by an attack, the cluster moves up to its speed toward the attacker. This movement doesn't provoke opportunity attacks. If the cluster ends this movement within 5 feet of the attacker, it then makes one Slam attack against that attacker.


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