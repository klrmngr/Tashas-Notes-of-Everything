---
type: pc
race: "Aberration"
class:
 - "Belashyrra"
subClass:
 - "CR 22"
cover: "Belashyrra.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/22
  - source/erlw
---
###### Belashyrra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Belashyrra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 304 (32d8 + 160) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 21 | 20 | 25 | 22 | 23 |
| **Mod** | +7 | +5 | +5 | +7 | +6 | +6 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +14, Wis +13, Cha +13
**Skills:** Arcana +14, Perception +13
**Damage Resistances:** poison; psychic
**Condition Immunities:** blinded; charmed; exhaustion; frightened; poisoned; prone

---

### Traits

**Alien Mind.** If a creature tries to read Belashyrra's thoughts or deals psychic damage to it, that creature must succeed on a DC 22 Intelligence saving throw or be stunned for 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Eye Thief.** Belashyrra can see through the eyes of all creatures within 120 feet of it. It can use its Eye Ray through any creature within 120 feet of it, as though it were in that creature's space.

**Legendary Resistance (3/Day).** If Belashyrra fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Belashyrra has advantage on saving throws against spells and other magical effects.

**Regeneration.** Belashyrra regains 20 hit points at the start of its turn. If it takes radiant damage, this trait doesn't function at the start of its next turn. Belashyrra dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Teleport.** As a bonus action, Belashyrra can teleport up to 30 feet to an unoccupied space it can see.


---

### Actions

**Multiattack.** Belashyrra makes two attacks with its claws and uses its Eye Ray once.

**Claw.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 17 (3d6 + 7) slashing damage.

**Eye Ray.** Belashyrra shoots one of the following magical eye rays of its choice, targeting one creature it can see within 120 feet of it:
- The target must make a DC 22 Wisdom saving throw, taking 49 (9d10) psychic damage on a failed save, or half as much damage on a successful one. If this damage reduces a creature to 0 hit points, it dies and transforms into a spectator under Belashyrra's control and acts immediately after Belashyrra in the initiative order. The target can't be returned to its original form by any means short of a wish spell.
- The target must succeed on a DC 22 Wisdom saving throw or be charmed by Belashyrra for 1 minute or until the target takes damage. Belashyrra can issue telepathic commands to the charmed creature (no action required), which it does its best to obey.
- The target must succeed on a DC 22 Intelligence saving throw or take 36 (8d8) psychic damage and be unable to cast spells or activate magic items for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The target and each creature within 10 feet of it must succeed on a DC 22 Constitution saving throw or take 19 (3d12) radiant damage and be blinded for 1 minute. Until this blindness ends, Belashyrra can see through the blinded creature's eyes. The blinded creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Claw.** Belashyrra makes one claw attack.

**Implant Fear (Costs 2 Actions).** Belashyrra targets a creature it can see within 60 feet of it. The target must succeed on a DC 22 Wisdom saving throw or take 22 (4d10) psychic damage and immediately use its reaction, if available, to move as far as its speed allows away from Belashyrra.

**Rend Reality (Costs 3 Actions).** Belashyrra rips at the bonds of reality in its immediate area. Each creature within 10 feet of Belashyrra must succeed on a DC 22 Constitution saving throw or take 19 (3d12) force damage and gain one level of exhaustion.


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