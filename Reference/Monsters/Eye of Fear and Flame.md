---
type: pc
race: "Undead"
class:
 - "Eye of Fear and Flame"
subClass:
 - "CR 9"
cover: "Eye of Fear and Flame.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/9
  - source/mff
---
###### Eye of Fear and Flame
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Eye of Fear and Flame.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 18 | 18 | 17 | 18 |
| **Mod** | +3 | +2 | +4 | +4 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, all languages known by any creature within 30 feet of it
**Saving Throws:** Str +7, Con +8, Wis +7, Cha +8
**Skills:** Perception +7
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Turn Immunity.** The eye of fear and flame is immune to effects that turn undead.


---

### Actions

**Multiattack.** The eye of fear and flame makes two claw attacks and uses its Gemstone Eyes.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d12 + 3) slashing damage.

**Gemstone Eyes.** The eye of fear and flame shoots one of the following magical eye rays, choosing one target it can see within 90 feet of it.
- **Eye of Fear.** The target and up to four other creatures of the eye of fear and flame's choice within 10 feet of the target must each succeed on a DC 16 Wisdom saving throw or be frightened for 1 minute. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- **Eye of Flame.** The target must make a DC 16 Dexterity saving throw. On a failed save, the target takes 44 (8d10) fire damage, and if it is a creature or a flammable object, it ignites. On a successful save, the target takes half as much damage and does not ignite. A target that ignites takes 5 (1d10) fire damage at the start of each of its turns until a creature takes an action to douse the fire.


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