---
type: pc
race: "Aberration (warlock)"
class:
 - "Neogi Void Hunter"
subClass:
 - "CR 4"
cover: "Neogi Void Hunter.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/4
  - source/bam
---
###### Neogi Void Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Neogi Void Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Aberration (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Aberration (warlock) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 14 | 16 | 12 | 18 |
| **Mod** | -2 | +3 | +2 | +3 | +1 | +4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Common, Deep Speech, telepathy 30 ft., Undercommon
**Saving Throws:** Wis +3, Cha +6
**Skills:** Arcana +5, Deception +6, Intimidation +6, Perception +3, Persuasion +6

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the neogi's darkvision.

**Mental Fortitude.** The neogi has advantage on saving throws against being charmed or frightened, and magic can't put the neogi to sleep.

**Spider Climb.** The neogi can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The neogi makes one Bite attack and two Claw attacks, or it makes two Eldritch Bolt attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 14 (4d6) poison damage, and the target must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Eldritch Bolt.** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 20 (3d10 + 4) force damage.


---

### Bonus Actions

**Enslave (Recharges after a Short or Long Rest).** The neogi targets one creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be magically charmed by the neogi for 1 day, or until the neogi dies or is more than 1 mile from the target. The charmed target obeys the neogi's commands and can't take reactions, and the neogi and the target can communicate telepathically with each other at a distance of up to 1 mile. Whenever the charmed target takes damage, it can repeat the saving throw, ending the effect on itself on a success.


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