---
type: pc
race: "Undead"
class:
 - "Geist"
subClass:
 - "CR 4"
cover: "Geist.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/psi
---
###### Geist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSI
___

> [!infobox|no-t right]
> ![[Geist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 45 (10d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | PSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 13 | 10 | 10 | 12 | 17 |
| **Mod** | -2 | +1 | +0 | +0 | +1 | +3 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** any languages it knew in life
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled

---

### Traits

**Ethereal Sight.** The geist can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

**Incorporeal Movement.** The geist can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Withering Touch.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target *Hit:* 17 (4d6 + 3) necrotic damage.

**Etherealness.** The geist enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

**Possession (Recharge 6).** One creature that the geist can see within 5 feet of it must succeed on a DC 13 Charisma saving throw or be possessed by the geist; the geist then disappears, and the target is incapacitated and loses control of its body. The geist now controls the body but doesn't deprive the target of awareness. The geist can't be targeted by any attack, spell, or other effect, except ones that turn undead, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, the geist ends it as a bonus action, or the geist is turned or forced out by an effect like the dispel evil and good spell. When the possession ends, the geist reappears in an unoccupied space within 5 feet of the body. The target is immune to this geist's Possession for 24 hours after succeeding on the saving throw or after the possession ends. The geist can instead target the corpse of a creature, effectively using its own life force to animate the corpse as a zombie. The animated corpse uses zombie statistics and returns to death if the geist ends the possession.


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