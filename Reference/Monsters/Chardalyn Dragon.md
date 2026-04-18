---
type: pc
race: "Construct"
class:
 - "Chardalyn Dragon"
subClass:
 - "CR 11"
cover: "Chardalyn Dragon.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/11
  - source/idrotf
---
###### Chardalyn Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Chardalyn Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 147 (14d12 + 56) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 11 | 19 | 10 | 10 | 3 |
| **Mod** | +7 | +0 | +4 | +0 | +0 | -4 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** the languages known by its creator
**Saving Throws:** Str +11, Con +8
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The dragon is immune to any spell or effect that would alter its form.

**Magic Resistance.** The dragon has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The dragon deals double damage to objects and structures.

**Unusual Nature.** The dragon doesn't require air, food, drink, or sleep, and it gains no benefit from finishing a short or long rest.


---

### Actions

**Multiattack.** The dragon uses its Malevolent Presence. It then makes three attacks: two with its claws and one with its tail. If the dragon isn't flying, it can also make one attack with its wings.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Tail.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) bludgeoning damage.

**Wings.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 12 (2d4 + 7) bludgeoning damage.

**Malevolent Presence.** Any creature with an Intelligence of 4 or more that is within 30 feet of the dragon must succeed on a DC 16 Wisdom saving throw or be charmed by it for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Malevolent Presence for the next 24 hours. A creature charmed in this way fixates on another creature or object that the dragon mentally chooses and must, on each of its turns, move as close as it can to that target and use its action to make a melee attack against it. If the dragon doesn't choose a target, the charmed creature can act normally on its turn.

**Radiant Breath (Recharge 5–6).** The dragon exhales a ray of radiant energy in a 120-foot line that is 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking 31 (7d8) radiant damage on a failed save, or half as much damage on a successful one.


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