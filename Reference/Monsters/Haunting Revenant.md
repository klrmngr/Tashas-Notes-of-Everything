---
type: pc
race: "Undead"
class:
 - "Haunting Revenant"
subClass:
 - "CR 10"
cover: "Haunting Revenant.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/gargantuan
  - cr/10
  - source/xmm
---
###### Haunting Revenant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Haunting Revenant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Gargantuan Undead |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 203 (14d20 + 56) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 16 | 18 | 20 |
| **Mod** | +5 | +1 | +4 | +3 | +4 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 14
**Languages:** Common plus two other languages
**Saving Throws:** Con +8, Wis +8
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Haunted Zone.** con DC 17, any creature that casts a spell while inside the revenant's space.  The spell fails and is wasted.

**Undead Restoration.** If the revenant dies, it revives 24 hours later unless Dispel Evil and Good is cast on its remains. If it revives, it animates another Gargantuan object or structure elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.


---

### Actions

**Multiattack.** The revenant makes two Object Slam attacks and uses Invitation.

**Object Slam.** m,r +9 (with Advantage if the target is inside the revenant's space), reach 10 ft. or range 30/90 ft. *Hit:* 27 (5d8 + 5) Bludgeoning damage.

**Invitation.** cha DC 17, each creature in a 60-foot Cone.  The target is teleported inside the revenant's space and swallowed. A swallowed creature has Total Cover against attacks and other effects outside the revenant.
While the revenant has Hit Points, a swallowed creature can leave the revenant's space only by using magic that enables planar travel, such as the Plane Shift spell.


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