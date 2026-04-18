---
type: pc
race: "Humanoid (aarakocra)"
class:
 - "Aarakocra Simulacrum"
subClass:
 - "CR 1/8"
cover: "Aarakocra Simulacrum.png"
campaign:
locations:
tags:
  - race/aarakocra
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/skt
---
###### Aarakocra Simulacrum
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Aarakocra Simulacrum.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (aarakocra) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 6 (3d4) |
> | :FasUserGroup: Race | Humanoid (aarakocra) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 10 | 11 | 12 | 11 |
| **Mod** | +0 | +2 | +0 | +0 | +1 | +0 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Auran, Aarakocra
**Skills:** Perception +5

---

### Traits

**Dive Attack.** If the aarakocra is flying and dives at least 30 feet straight toward a target and then hits it with a melee weapon attack, the attack deals an extra 3 (1d6) damage to the target.

**Simulacra.** When a simulacrum drops to 0 hit points or is subjected to a successful dispel magic spell (DC 17), it reverts to ice and snow and is destroyed.


---

### Actions

**Talon.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Summon Air Elemental.** Five aarakocra within 30 feet of each other can magically summon an air elemental. Each of the five must use its action and movement on three consecutive turns to perform an aerial dance and must maintain concentration while doing so (as if concentrating on a spell). When all five have finished their third turn of the dance, the elemental appears in an unoccupied space within 60 feet of them. It is friendly toward them and obeys their spoken commands. It remains for 1 hour, until it or all its summoners die, or until any of its summoners dismisses it as a bonus action. A summoner can't perform the dance again until it finishes a short rest. When the elemental returns to the Elemental Plane of Air, any aarakocra within 5 feet of it can return with it.


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