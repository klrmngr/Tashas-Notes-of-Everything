---
type: pc
race: "Plant"
class:
 - "Myconid Sovereign"
subClass:
 - "CR 2"
cover: "Myconid Sovereign.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/2
  - source/xmm
---
###### Myconid Sovereign
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Myconid Sovereign.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 14 | 13 | 15 | 10 |
| **Mod** | +1 | +0 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** telepathy 240 ft.

---

### Traits

**Sun Sickness.** While in sunlight, the myconid has Disadvantage on D20 Tests. The myconid dies if it spends more than 1 hour in sunlight.


---

### Actions

**Multiattack.** The myconid makes one Slam attack and uses Pacifying Spores.

**Slam.** m +3, reach 5 ft. *Hit:* 6 (2d4 + 1) Bludgeoning damage plus 5 (2d4) Poison damage.

**Animating Spores (3/Day).** The myconid releases spores at a Medium or Small corpse within 5 feet of it that wasn't a Construct or an Undead. In 24 hours, the corpse rises as a [[Myconid Spore Servant]]. The corpse stays animate for 1d4 + 1 weeks or until destroyed, and it can't be animated again in this way.

**Pacifying Spores.** con DC 12, one creature the myconid can see within 10 feet.  The target has the Stunned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

**Rapport Spores.** The myconid expels spores in a 30-foot Emanation originating from itself. Creatures in that area with an Intelligence score of 2 or higher that aren't Constructs, Elementals, or Undead gain telepathy with a range of 30 feet for 1 hour.


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