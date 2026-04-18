---
type: pc
race: "Aberration (shapechanger)"
class:
 - "Gingwatzim"
subClass:
 - "CR 2"
cover: "Gingwatzim.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/2
  - source/cm
---
###### Gingwatzim
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Gingwatzim.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Aberration (shapechanger) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 39 (6d6 + 18) |
> | :FasUserGroup: Race | Aberration (shapechanger) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 15 | 16 | 4 | 11 | 6 |
| **Mod** | -4 | +2 | +3 | -3 | +0 | -2 |

**Speed:** 30 ft., fly 30 ft. ((hover) in its true form only) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** telepathy 60 ft.
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Alternate Forms.** The gingwatzim has two alternate forms, both of which are chosen by its creator when the gingwatzim comes into being. One form is an exact duplicate of a Tiny nonmagical object (such as a book, dagger, or gemstone) that its creator is carrying or wearing when the gingwatzim is conjured. The other form can be any Tiny beast. Once these alternate forms are chosen, they can't be changed.


---

### Actions

**Energy Drain (True Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 16 (4d6 + 2) necrotic damage, and the target must succeed on a DC 12 Constitution saving throw or gain 1 level of exhaustion. When the target finishes a short or long rest, the target loses every level of exhaustion gained from this attack.

**Change Shape.** The gingwatzim changes from its true form—a 3-foot-diameter sphere of luminous ectoplasm—into one of its two alternate forms, or from one of those forms back into its true form. In object form, it can't move or make attacks but otherwise retains its statistics, and it is indistinguishable from the thing it is imitating. In beast form, it retains its hit points but otherwise uses the stat block of the beast it is imitating. When it dies, the gingwatzim reverts to its true form and then vanishes.


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