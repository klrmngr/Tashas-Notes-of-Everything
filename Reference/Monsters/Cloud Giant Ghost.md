---
type: pc
race: "Undead"
class:
 - "Cloud Giant Ghost"
subClass:
 - "CR 9"
cover: "Cloud Giant Ghost.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/9
  - source/cm
---
###### Cloud Giant Ghost
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Cloud Giant Ghost.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 104 (16d12) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 11 | 10 | 12 | 16 | 17 |
| **Mod** | +8 | +0 | +0 | +1 | +3 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Common, Giant
**Saving Throws:** Wis +7, Cha +7
**Skills:** Perception +7
**Damage Resistances:** cold
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Ethereal Sight.** The ghost can see 120 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

**Incorporeal Movement.** The ghost can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Regeneration.** The ghost regains 10 hit points at the start of its turn. If the ghost takes radiant damage or damage from a magic weapon, this trait doesn't function at the start of the ghost's next turn. The ghost dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The ghost makes two melee attacks.

**Spectral Weapon.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) force damage.

**Etherealness.** The ghost enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

**Wind Howl (Recharge 6).** The ghost emits a dreadful howl that summons a cold, biting wind. This wind engulfs up to three creatures of the ghost's choice that it can see within 60 feet of it. Each target is pulled up to 20 feet toward the ghost and must make a DC 15 Constitution saving throw, taking 16 (3d10) cold damage on a failed save, or half as much damage on a successful one.


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