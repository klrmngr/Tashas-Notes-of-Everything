---
type: pc
race: "Monstrosity"
class:
 - "Creeper"
subClass:
 - "CR 1/2"
cover: "Creeper.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/mcv3mc
---
###### Creeper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV3MC
___

> [!infobox|no-t right]
> ![[Creeper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV3MC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 14 | 6 | 8 | 3 |
| **Mod** | +0 | +0 | +2 | -2 | -1 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4
**Damage Immunities:** lightning
**Condition Immunities:** exhaustion

---

### Traits

**Bizarre Physiology.** The creeper can't take actions except for Dash, Disengage, Hide, and Search. It can't take bonus actions or reactions.

**Creeper Head.** When a creeper drops to 0 hit points from a charged creeper's explosion (see the Destruction trait), it dies and its head falls off. A creeper's fallen head is hollow and can be worn as a mask with eye and mouth openings.

**Destruction.** When it ends its turn within 10 feet of a Humanoid that it can see, the creeper stops moving and emits a hiss loud enough to be heard by creatures within 30 feet of itself.
If the creeper drops to 0 hit points before the start of its next turn, the hissing stops, and the creeper dies. Otherwise, at the start of the creeper's next turn, one of following things happens:
- If there are no Humanoids within 10 feet of the hissing creeper, it stops hissing. It then uses any available movement to approach the nearest Humanoid it can see.
- If there are one or more Humanoids within 10 feet of the hissing creeper, the creeper explodes in a ball of energy that fills a 20-foot-radius sphere centered on itself. This energy spreads around corners. The creeper is destroyed, and every other creature in the explosion's area must make a DC 12 Dexterity saving throw, taking 14 (4d6) lightning damage on a failed save, or half as much damage on a successful one. Increase this damage by 7 (2d6) if the creeper is charged (see "Electrical Charge" below). Objects in the area that aren't being worn or carried take 14 (4d6) lightning damage, or 21 (6d6) lightning damage if the creeper is charged.

**Electrical Charge.** Whenever the creeper is subjected to lightning damage, it takes no damage and instead becomes charged for 1 minute. While charged, the creeper emits dim blue light in a 5-foot radius.

**Fear of Felines.** The creeper has the frightened condition whenever it starts its turn within 60 feet of a feline creature it can see. The condition lasts until the start of the creeper's next turn.


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