---
type: pc
race: "Dragon"
class:
 - "Jabberwock"
subClass:
 - "CR 13"
cover: "Jabberwock.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/13
  - source/wbtw
---
###### Jabberwock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Jabberwock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 115 (10d12 + 50) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 4 | 7 | 11 |
| **Mod** | +5 | +1 | +5 | -3 | -2 | +0 |

**Speed:** 30 ft., climb 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** —
**Saving Throws:** Str +10, Dex +6, Con +10, Int +2, Wis +3, Cha +5
**Skills:** Perception +8
**Damage Vulnerabilities:** slashing from a vorpal sword
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Confusing Burble.** The jabberwock burbles to itself unless it is incapacitated. Any creature that starts its turn within 30 feet of the jabberwock and is able to hear its burbling must make a DC 18 Charisma saving throw. On a failed saving throw, the creature can't take reactions until the start of its next turn, and it rolls a d4 to determine what it does during its current turn:
- **1-2.** The creature does nothing.
- **3.** The creature does nothing except use all its movement to move in a random direction.
- **4.** The creature either makes one melee attack against a random creature it can see or does nothing if no visible creature is within its reach.

**Legendary Resistance (3/Day).** If the jabberwock fails a saving throw, it can choose to succeed instead.

**Regeneration.** The jabberwock regains 10 hit points at the start of its turn. If the jabberwock takes slashing damage, this trait doesn't function at the start of its next turn. The jabberwock dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Uncanny Tracker.** The jabberwock can unerringly track any creature it has wounded in the last 24 hours, and it knows the distance and direction to its quarry as long as the two of them are on the same plane of existence.


---

### Actions

**Multiattack.** The jabberwock makes two Rend attacks.

**Rend.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) slashing damage.

**Tail.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage.

**Fiery Gaze (Recharge 5–6).** Unless it is blinded, the jabberwock emits a 120-foot-long, 5-foot-wide line of fire from its eyes. Each creature in that line must make a DC 18 Dexterity saving throw, taking 31 (7d8) fire damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tail Attack.** The jabberwock makes one Tail attack.

**Rend Attack (2 Actions).** The jabberwock makes one Rend attack.

**Wing Attack (3 Actions).** The jabberwock beats its wings. Each creature within 10 feet of the jabberwock must succeed on a DC 18 Dexterity saving throw or take 8 (1d6 + 5) bludgeoning damage and be knocked prone.


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