---
type: pc
race: "Fiend (devil)"
class:
 - "Abigor"
subClass:
 - "CR 22"
cover: "Abigor.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/22
  - source/coa
---
###### Abigor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Abigor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 337 (27d10 + 189) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 20 | 16 | 16 |
| **Mod** | +8 | +2 | +7 | +5 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +15, Int +12
**Skills:** Athletics +22, History +12, Insight +10, Intimidation +17, Perception +10, Survival +10
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Abigor's darkvision.

**Magic Resistance.** Abigor has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Abigor makes four attacks using its Warhammer, Throwing Hammer, or a combination of the two.

**Warhammer.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 17 (2d8 + 8) bludgeoning damage plus 3 (1d6) thunder damage.

**Throwing Hammer.** Ranged Weapon Attack: +15 to hit, range 30/60 ft., one target. *Hit:* 17 (2d8 + 8) bludgeoning damage plus 3 (1d6) thunder damage. Hammers thrown this way fall and stick into the ground after hitting their target and a new hammer appears in Abigor's hand.

**Thunderous Slam (Recharge 5–6).** Abigor causes all its hammers left on the battlefield to bristle with thunderous energy, exploding outwards with a roar. All creatures within a 10-foot-radius sphere centered on each hammer must make a DC 22 Constitution saving throw. Targets take 26 (4d12) thunder damage on a failed save, or half as much damage on a successful one. If a creature is within multiple spheres, it must make the save multiple times, taking damage from each source.


---

### Legendary Actions

### 

**Throw Hammer.** Abigor makes a Throwing Hammer attack.

**Call Thunder (Costs 2 Actions).** Abigor targets a hammer that it can see within 60 feet to let out a thunderous roar. Creatures within a 10-foot-radius sphere centered on the hammer must make a DC 22 Constitution saving throw, taking 26 (4d12) thunder damage on a failed save, or half as much damage on a successful one.


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