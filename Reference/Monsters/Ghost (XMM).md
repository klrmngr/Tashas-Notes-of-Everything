---
type: pc
race: "Undead"
class:
 - "Ghost"
subClass:
 - "CR 4"
cover: "Ghost.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/xmm
---
###### Ghost
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ghost.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 45 (10d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 13 | 10 | 10 | 12 | 17 |
| **Mod** | -2 | +1 | +0 | +0 | +1 | +3 |

**Speed:** 5 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common plus one other language
**Damage Resistances:** acid; bludgeoning; cold; fire; lightning; piercing; slashing; thunder
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Ethereal Sight.** The ghost can see 60 feet into the Ethereal Plane when it is on the Material Plane.

**Incorporeal Movement.** The ghost can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The ghost makes two Withering Touch attacks.

**Withering Touch.** m +5, reach 5 ft. *Hit:* 19 (3d10 + 3) Necrotic damage.

**Horrific Visage.** wis DC 13, each creature in a 60-foot Cone that can see the ghost and isn't an Undead.  10 (2d6 + 3) Psychic damage, and the target has the Frightened condition until the start of the ghost's next turn.  The target is immune to this ghost's Horrific Visage for 24 hours.

**Possession (Recharge 6).** cha DC 13, one Humanoid the ghost can see within 5 feet.  The target is possessed by the ghost; the ghost disappears, and the target has the Incapacitated condition and loses control of its body. The ghost now controls the body, but the target retains awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that specifically target Undead. The ghost's game statistics are the same, except it uses the possessed target's Speed, as well as the target's Strength, Dexterity, and Constitution modifiers.
The possession lasts until the body drops to 0 Hit Points or the ghost leaves as a Bonus Action. When the possession ends, the ghost appears in an unoccupied space within 5 feet of the target, and the target is immune to this ghost's Possession for 24 hours.  The target is immune to this ghost's Possession for 24 hours.


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