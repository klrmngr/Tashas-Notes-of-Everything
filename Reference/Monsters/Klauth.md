---
type: pc
race: "Dragon"
class:
 - "Klauth"
subClass:
 - "CR 25"
cover: "Klauth.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/25
  - source/skt
---
###### Klauth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Klauth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 546 (28d20 + 252) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 10 | 29 | 18 | 15 | 23 |
| **Mod** | +10 | +0 | +9 | +4 | +2 | +6 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic
**Saving Throws:** Dex +8, Con +17, Wis +10, Cha +14
**Skills:** Perception +16, Stealth +8
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (3/Day).** If Klauth fails a saving throw, he can choose to succeed instead.

**Dual Wand Wielder.** If Klauth is carrying two wands, he can use an action to expend 1 charge from each wand, triggering the effects of both wands simultaneously.

**Special Equipment.** Klauth carries a wand of fireballs and a wand of lightning bolts, and he wears a ring of cold resistance.


---

### Actions

**Multiattack.** Klauth can use his Frightful Presence. He then makes three attacks: one with his bite and two with his claws.

**Bite.** Melee Weapon Attack: +17 to hit, reach 15 ft., one target. *Hit:* 21 (2d10 + 10) piercing damage plus 14 (4d6) fire damage.

**Claw.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 17 (2d6 + 10) slashing damage.

**Tail.** Melee Weapon Attack: +17 to hit, reach 20 ft., one target. *Hit:* 19 (2d8 + 10) bludgeoning damage.

**Frightful Presence.** Each creature of Klauth's choice that is within 120 feet of Klauth and aware of him must succeed on a DC 21 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Klauth's Frightful Presence for the next 24 hours.

**Fire Breath (Recharge 5–6).** Klauth exhales fire in a 90-foot cone. Each creature in that area must make a DC 24 Dexterity saving throw, taking 91 (26d6) fire damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Detect.** Klauth makes a Wisdom (Perception) check.

**Tail Attack.** Klauth makes a tail attack.

**Wing Attack (Costs 2 Actions).** Klauth beats his wings. Each creature within 15 feet of Klauth must succeed on a DC 25 Dexterity saving throw or take 17 (2d6 + 10) bludgeoning damage and be knocked prone. Klauth can then fly up to half his flying speed.


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