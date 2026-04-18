---
type: pc
race: "Fiend (demon)"
class:
 - "Raklupis Spyder-Fiend"
subClass:
 - "CR 19"
cover: "Raklupis Spyder-Fiend.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/19
  - source/veor
---
###### Raklupis Spyder-Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Raklupis Spyder-Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 210 (28d10 + 56) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 20 | 14 | 18 | 16 | 23 |
| **Mod** | +3 | +5 | +2 | +4 | +3 | +6 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Dex +11, Con +8, Wis +9
**Skills:** Perception +9, Stealth +11
**Damage Immunities:** cold; fire; lightning; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The raklupis has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The raklupis can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** When in contact with a web, the raklupis knows the exact location of any other creature in contact with the same web.

**Web Walker.** The raklupis ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The raklupis makes a Bite attack and two Serrated Sword attacks. It can use Venom Globe in place of one of these attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 18 (4d8) poison damage. If the target is a creature, it must succeed on a DC 20 Constitution saving throw or have the poisoned condition for 1 minute. While poisoned in this way, a creature has the incapacitated condition and can't regain hit points. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Serrated Sword.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 19 (4d6 + 5) slashing damage plus 18 (4d8) poison damage.

**Venom Globe.** Ranged Weapon Attack: +11 to hit, range 60/180 ft., one target. *Hit:* 45 (10d8) poison damage.


---

### Bonus Actions

**Demand Loyalty.** The raklupis magically ends the charmed and frightened conditions on itself and on any number of allies within 60 feet of itself.


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