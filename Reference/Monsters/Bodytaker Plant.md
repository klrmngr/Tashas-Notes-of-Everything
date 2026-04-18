---
type: pc
race: "Plant"
class:
 - "Bodytaker Plant"
subClass:
 - "CR 7"
cover: "Bodytaker Plant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/7
  - source/vrgr
---
###### Bodytaker Plant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Bodytaker Plant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 92 (8d12 + 40) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 20 | 14 | 14 | 18 |
| **Mod** | +4 | -1 | +5 | +2 | +2 | +4 |

**Speed:** 10 ft., climb 10 ft., swim 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 12
**Languages:** Deep Speech, telepathy 120 ft.
**Damage Vulnerabilities:** poison
**Condition Immunities:** blinded; charmed; frightened; prone

---

### Traits

**Podling Link.** The plant can see through and communicate telepathically with any of its podlings within 10 miles of it.

**Rejuvenation.** When the plant dies, it returns to life in the place where it died 1d12 months later, unless the ground where it took root is sown with salt or soaked with poison.

**Unusual Nature.** The plant doesn't require sleep.


---

### Actions

**Multiattack.** The plant makes three Vine Lash attacks.

**Vine Lash.** Melee Weapon Attack: +7 to hit, reach 20 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage. If the target is a creature, it is grappled (escape DC 15). Until the grapple ends, the target is restrained. The plant has four vines, each of which can grapple one target.

**Entrapping Pod.** Melee Weapon Attack: +7 to hit, reach 5 ft., one Medium or smaller creature grappled by the plant. *Hit:* 22 (4d8 + 4) acid damage, and the target is pulled into the plant's space and enveloped by the pod, and the grapple ends. While enveloped, the target is restrained, and it has 3 against attacks and effects originating outside the pod. The enveloped target must also immediately succeed on a DC 16 Constitution saving throw or be stunned by the plant's sapping enzymes until it is removed from the pod or the plant dies. The enveloped target doesn't require air and gains 1 level of exhaustion for each hour it spends in the pod. If the target dies while enveloped, it immediately emerges from the pod as a living podling, wearing or carrying all of the original creature's equipment.
As an action, a creature within 5 feet of the bodytaker plant that is outside the pod can open the pod and pull the target free with a successful DC 15 Strength check. If the plant dies, the target is no longer restrained and can escape from the pod by spending 10 feet of movement, exiting prone. The plant has one pod, which can envelop one creature at a time.


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