---
type: pc
race: "Humanoid (human)"
class:
 - "Fathomer"
subClass:
 - "CR 2"
cover: "Fathomer.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/pota
---
###### Fathomer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Fathomer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 14 | 11 | 11 | 15 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Aquan, Common
**Skills:** Arcana +2, Perception +4, Stealth +4

---

### Traits

**Shapechanger (2/Day).** The fathomer can use its action to polymorph into a Medium serpent composed of water, or back into its true form. Anything the fathomer is wearing or carrying is subsumed into the serpent form during the change, inaccessible until the fathomer returns to its true form. The fathomer reverts to its true form after 4 hours, unless it can expend another use of this trait. If the fathomer is knocked unconscious or dies, it also reverts to its true form.
While in serpent form, the fathomer gains a swimming speed of 40 feet, the ability to breathe underwater, immunity to poison damage, as well as resistance to fire damage and bludgeoning, piercing, and slashing damage from nonmagical attacks. It also has immunity to the following conditions: exhaustion, grappled, paralyzed, poisoned, restrained, prone, unconscious. The serpent form can enter a hostile creature's space and stop there. In addition, if water can pass through a space, the serpent can do so without squeezing.

**Olhydra's Armor (Human Form Only).** The fathomer can cast mage armor at will, without expending material components.


---

### Actions

**Constrict (Serpent Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage. If the target is Medium or smaller, it is grappled (escape DC 12). Until the grapple ends, the target is restrained, and the fathomer can't constrict another target.

**Dagger (Human Form Only).** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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