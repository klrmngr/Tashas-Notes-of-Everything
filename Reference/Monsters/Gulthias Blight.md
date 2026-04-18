---
type: pc
race: "Plant"
class:
 - "Gulthias Blight"
subClass:
 - "CR 16"
cover: "Gulthias Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/gargantuan
  - cr/16
  - source/xmm
---
###### Gulthias Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gulthias Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Plant |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 264 (16d20 + 96) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 22 | 10 | 18 | 12 |
| **Mod** | +7 | +0 | +6 | +0 | +4 | +1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 19
**Languages:** Common, Druidic
**Skills:** Perception +9
**Damage Resistances:** fire; necrotic
**Condition Immunities:** deafened

---

### Traits

**Blight Seeds.** When it finishes a Long Rest, the blight expels 1d6 seeds into unoccupied spaces on the ground within 30 feet of itself. After 24 hours, the seeds become creatures under the blight's control. Roll 1d8 for each seed to determine the creature it becomes: on 1-4, Twig Blight; on 5-6, Needle Blight; on 7-8, Vine Blight.


---

### Actions

**Multiattack.** The blight makes two attacks, using Slam or Thorn Volley in any combination. It also uses Life-Draining Root.

**Slam.** m +12, reach 10 ft. *Hit:* 25 (4d8 + 7) Bludgeoning damage.

**Thorn Volley.** r +12, range 60/180 ft. *Hit:* 20 (3d8 + 7) Piercing damage.

**Life-Draining Root.** con DC 20, one Huge or smaller creature the blight can see within 30 feet.  14 (2d6 + 7) Necrotic damage, and the target has the Grappled condition (escape DC 17) from one of six roots. Until the grapple ends, the target has the Restrained condition and takes 14 (4d6) Necrotic damage at the start of each of its turns. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the blight regains Hit Points equal to that amount.


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