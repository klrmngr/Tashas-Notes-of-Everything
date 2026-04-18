---
type: pc
race: "Humanoid (aarakocra)"
class:
 - "Asharra"
subClass:
 - "CR 2"
cover: "Asharra.png"
campaign:
locations:
tags:
  - race/aarakocra
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/toa
---
###### Asharra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Asharra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (aarakocra) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Humanoid (aarakocra) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 10 | 14 | 17 | 11 |
| **Mod** | +0 | +2 | +0 | +2 | +3 | +0 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Auran, Common
**Skills:** History +4, Insight +5, Perception +7

---

### Traits

**Dive Attack.** If the aarakocra is flying and dives at least 30 feet straight toward a target and then hits it with a melee weapon attack, the attack deals an extra 3 (1d6) damage to the target.

**Dance of the Seven Winds.** Asharra knows a ritual called the Dance of the Seven Winds, which temporarily grants magical flight to as many as ten nonflying creatures. The ritual, which takes 10 minutes to complete, can only be performed by an aarakocra elder and requires a black orchid as a material component.
Asharra must grind the orchid to powder, inhale it, and dance in circles around the ritual's beneficiaries uninterrupted while seven other aarakocra chant prayers to the Wind Dukes of Aaqa. When the dance concludes, Asharra's wings disappear and she loses the ability to fly. The ritual's beneficiaries each gain a magical flying speed of 30 feet (allowing them to fly 4 miles per hour). This benefit lasts for 3 days, after which Asharra's wings reappear and she regains the ability to fly.


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