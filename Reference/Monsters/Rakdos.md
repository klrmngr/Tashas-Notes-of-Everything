---
type: pc
race: "Fiend (demon)"
class:
 - "Rakdos"
subClass:
 - "CR 24"
cover: "Rakdos.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/24
  - source/ggr
---
###### Rakdos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Rakdos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 300 (24d12 + 144) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 15 | 22 | 14 | 18 | 30 |
| **Mod** | +8 | +2 | +6 | +2 | +4 | +10 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Abyssal, Common
**Saving Throws:** Str +15, Con +13, Wis +11, Cha +17
**Skills:** Intimidation +17, Performance +17, Persuasion +17
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Captivating Presence.** Any creature that starts its turn within 30 feet of Rakdos must make a DC 25 Wisdom saving throw. On a failed save, the creature becomes charmed by Rakdos for 1 minute or until the creature is farther than 30 feet away from him. On a successful save, the creature becomes immune to Rakdos's Captivating Presence for 24 hours.

**Cruel Entertainment.** When a creature Rakdos can see within 60 feet of him is reduced to 0 hit points, Rakdos gains 25 temporary hit points.

**Legendary Resistance (3/Day).** If Rakdos fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Rakdos has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Rakdos's weapon attacks are magical.


---

### Actions

**Multiattack.** Rakdos makes two attacks with his Curtain-Call Scythe or his claws.

**Curtain-Call Scythe.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 24 (3d10 + 8) slashing damage plus 13 (3d8) fire damage.

**Claw.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) slashing damage.


---

### Legendary Actions

### 

**Sadistic Revelry.** Each creature within 60 feet of Rakdos that is his ally or is charmed by him must use its reaction to move up to half its speed toward the creature closest to it that it can see, provided it isn't already within 5 feet of that creature. It then must make one melee attack against that creature if it is able to do so.

**Scythe (Costs 2 Actions).** Rakdos uses Curtain-Call Scythe.

**Touch of Pain (Costs 3 Actions).** Rakdos makes a claw attack against one creature within 10 feet of him. The target must succeed on a DC 25 Constitution saving throw or be poisoned for 1 minute. While poisoned in this way, the creature can't maintain concentration on a spell or any other effect that requires concentration. The poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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