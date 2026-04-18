---
type: pc
race: "Fiend (demon)"
class:
 - "Bebilith"
subClass:
 - "CR 12"
cover: "Bebilith.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/12
  - source/mabjov
---
###### Bebilith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Bebilith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 189 (18d12 + 72) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 22 | 18 | 11 | 13 | 8 |
| **Mod** | +3 | +6 | +4 | +0 | +1 | -1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 15
**Languages:** understands Abyssal but only speaks telepathically to its own kind, telepathy 120 ft.
**Saving Throws:** Con +8, Wis +5
**Skills:** Perception +5, Stealth +10
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Dark Sight.** Magical darkness doesn't impede the bebilith's darkvision.

**Spider Climb.** The bebilith can climb difficult surfaces, including upside down, without needing to make an ability check and ignores any movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The bebilith uses Poisoned Web (if available) and then makes one Bite attack and two Foreleg attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 16 (2d12 + 3) piercing damage plus 21 (6d6) poison damage. Any creature that drops to zero hit points because of this attack ignites, suffering 7 (2d6) fire damage at the start of each of its turns until the creature's hit points are above zero.

**Foreleg.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 21 (4d8 + 3) slashing damage.

**Poisoned Web (Recharge 5–6).** Ranged Weapon Attack: +10 to hit, range 30/60 ft., one creature. *Hit:* 51 (10d8 + 6) poison damage, and the target has the restrained condition until free of the web. While restrained, the target takes 9 (2d8) poison damage at the start of each of its turns. The target may use an action to make a DC 17 Strength check and if successful they are freed from the webbing. The webbing can also be attacked and destroyed (AC 12; 10 hit points; immunity to bludgeoning, fire, poison, and psychic damage). If an attack or spell doing fire damage is used on the webbing, the webbing ignites (but is otherwise unharmed). Any creature restrained by the webbing suffers an additional 7 (2d6) fire damage at the start of each of its turn.

**Stalker's Darkness (3/Day).** The bebilith casts darkness.


---

### Bonus Actions

**Relentless Hunter.** The bebilith may use a bonus action to mark prey that it has damaged. Only one creature can be marked at a time. The bebilith always knows the exact location of the marked prey on the current plane of existence, can't be surprised by it, and has advantage on all attack rolls against it.


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