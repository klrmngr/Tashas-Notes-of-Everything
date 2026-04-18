---
type: pc
race: "Monstrosity"
class:
 - "Ironscale Hydra"
subClass:
 - "CR 12"
cover: "Ironscale Hydra.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/12
  - source/mot
---
###### Ironscale Hydra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Ironscale Hydra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 181 (11d20 + 66) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 22 | 2 | 10 | 7 |
| **Mod** | +6 | +0 | +6 | -4 | +0 | -2 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** —
**Skills:** Perception +8
**Damage Immunities:** acid

---

### Traits

**Acidic Blood.** When the hydra takes piercing or slashing damage, each creature within 5 feet of the hydra takes 9 (2d8) acid damage.

**Hold Breath.** The hydra can hold its breath for 1 hour.

**Multiple Heads.** The hydra has five heads. While it has more than one head, the hydra has advantage on saving throws against being blinded, charmed, deafened, frightened, stunned, or knocked unconscious. Whenever the hydra takes 35 or more damage in a single turn, one of its heads dies. If all its heads die, the hydra dies. At the end of its turn, it grows two heads for each of its heads that died since its last turn, unless it has taken fire damage since its last turn. The hydra regains 10 hit points for each head regrown in this way.

**Reactive Heads.** For each head the hydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

**Wakeful.** While the hydra sleeps, at least one of its heads is awake.


---

### Actions

**Multiattack.** The hydra makes as many bite attacks as it has heads.

**Bite.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage.


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