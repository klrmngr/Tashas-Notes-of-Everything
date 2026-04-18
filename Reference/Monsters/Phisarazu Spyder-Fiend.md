---
type: pc
race: "Fiend (demon)"
class:
 - "Phisarazu Spyder-Fiend"
subClass:
 - "CR 13"
cover: "Phisarazu Spyder-Fiend.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/13
  - source/veor
---
###### Phisarazu Spyder-Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Phisarazu Spyder-Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 170 (20d10 + 60) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 17 | 11 | 14 | 13 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +8, Wis +7
**Skills:** Perception +7, Stealth +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The phisarazu has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The phisarazu can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** When in contact with a web, the phisarazu knows the exact location of any other creature in contact with the same web.

**Web Walker.** The phisarazu ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The phisarazu makes one Bite attack and two Claw attacks. It can replace one of these attacks with Scintillating Spray if available.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage plus 9 (2d8) poison damage, and the target has the poisoned condition until the start of the phisarazu's next turn.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 22 (4d8 + 4) slashing damage.

**Scintillating Spray (Recharge 5–6).** The phisarazu expels shimmering webs in a 60-foot cone. Creatures and objects in that area are outlined by the glittering webs for 1 minute, during which time they emit dim light for 10 feet and can't benefit from the invisible condition. Additionally, creatures in that area must succeed on a DC 16 Wisdom saving throw or have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Change Shape.** The phisarazu transforms into a crab, drider, or giant crab, or returns to its true form. Its game statistics, except for its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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