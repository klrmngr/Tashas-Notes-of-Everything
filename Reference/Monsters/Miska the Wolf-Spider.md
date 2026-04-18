---
type: pc
race: "Fiend (demon)"
class:
 - "Miska the Wolf-Spider"
subClass:
 - "CR 24"
cover: "Miska the Wolf-Spider.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/24
  - source/veor
---
###### Miska the Wolf-Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Miska the Wolf-Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 399 (38d12 + 152) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 18 | 19 | 18 | 21 | 22 |
| **Mod** | +6 | +4 | +4 | +4 | +5 | +6 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Dex +11, Con +11, Wis +12
**Skills:** Insight +12, Perception +12, Stealth +11
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** poisoned

---

### Traits

**Foul Ichor.** A creature that hits Miska with a melee weapon attack takes 7 (2d6) poison damage.

**Legendary Resistance (3/Day).** If Miska fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Miska has advantage on saving throws against spells and other magical effects.

**Spider Climb.** Miska can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** When in contact with a web, Miska knows the exact location of any other creature in contact with the same web.

**Web Walker.** Miska ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** Miska makes one Lupine Bite attack and two Trident of Chaos attacks.

**Lupine Bite.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 27 (6d8) poison damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have the poisoned condition for 1 minute. While poisoned in this way, a creature has the incapacitated condition and can't regain hit points. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Trident of Chaos.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage plus 9 (2d8) force damage.


---

### Bonus Actions

**Demand Loyalty.** Miska magically ends the charmed and frightened conditions on himself and on any of his allies within 120 feet of himself.


---

### Legendary Actions

### 

**Howl.** Miska utters a bloodthirsty howl at one creature within 120 feet of himself that isn't a Fiend. The target must succeed on a DC 20 Wisdom saving throw or take 13 (2d12) psychic damage.

**Skitter.** Miska moves up to his speed without provoking opportunity attacks.

**Cast a Spell (Costs 2 Actions).** Miska uses Spellcasting.


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