---
type: pc
race: "Humanoid"
class:
 - "Performer Legend"
subClass:
 - "CR 10"
cover: "Performer Legend.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/xmm
---
###### Performer Legend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Performer Legend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 162 (25d8 + 50) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 20 | 14 | 15 | 16 | 20 |
| **Mod** | +1 | +5 | +2 | +2 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common plus two other languages
**Saving Throws:** Dex +9, Int +6, Wis +7, Cha +9
**Skills:** Acrobatics +13, Athletics +5, Perception +7, Performance +13, Stealth +9

---

### Actions

**Multiattack.** The performer makes three Bejeweled Baton attacks.

**Bejeweled Baton.** m +9, reach 5 ft. *Hit:* 10 (2d4 + 5) Bludgeoning damage plus 10 (3d6) Psychic damage.

**Majestic Song.** wis DC 17, each creature in a 20-foot-radius Sphere centered on a point within 120 feet.  22 (4d8 + 4) Psychic damage, and the target has the Charmed or Frightened condition (performer's choice) until the end of the performer's next turn.  Half damage only.


---

### Reactions

**Warding Charm.**  A creature hits the performer with an attack roll. dwis DC 17, the triggering creature.  The attack roll misses the performer, and the target has the Charmed condition until the end of the performer's next turn.


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