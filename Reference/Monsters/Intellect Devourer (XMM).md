---
type: pc
race: "Aberration"
class:
 - "Intellect Devourer"
subClass:
 - "CR 2"
cover: "Intellect Devourer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/2
  - source/xmm
---
###### Intellect Devourer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Intellect Devourer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 28 (8d4 + 8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 13 | 14 | 11 | 10 |
| **Mod** | -2 | +2 | +1 | +2 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 12
**Languages:** understands Deep Speech but can't speak; telepathy 60 ft.
**Skills:** Perception +2, Stealth +4
**Damage Resistances:** psychic

---

### Traits

**Detect Intelligence.** The intellect devourer magically senses the location of any creature within 300 feet of itself that has an Intelligence score of 3 or higher, regardless of interposing barriers.


---

### Actions

**Multiattack.** The intellect devourer makes one Claw attack and uses Devour Intellect.

**Claw.** m +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Slashing damage.

**Devour Intellect.** int DC 12, one creature the intellect devourer can see within 5 feet.  11 (2d10) Psychic damage, and the target has the Stunned condition until the end of the intellect devourer's next turn.

**Steal Body.** int DC 12, one Small or Medium creature within 5 feet that has the Incapacitated condition, is a Humanoid or Beast, and has 10 Hit Points or fewer.  The intellect devourer possesses the target, consumes its brain, and teleports inside its skull. While there, the intellect devourer has Total Cover against attacks and other effects originating outside its host. The intellect devourer retains its Intelligence, Wisdom, and Charisma scores; its understanding of Deep Speech; its telepathy; and its Detect Intelligence trait. It otherwise adopts the target's game statistics. It knows everything the target knew, including spells and languages.
If the host body dies, the intellect devourer must leave it. The intellect devourer is also forced out if the target regains its devoured brain by means of a Wish spell. By spending 5 feet of its movement, the intellect devourer can voluntarily leave the body, teleporting to the nearest unoccupied space within 5 feet of it. The body then dies unless its brain is restored before the end of the intellect devourer's next turn.


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