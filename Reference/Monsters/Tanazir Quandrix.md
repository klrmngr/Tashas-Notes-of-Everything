---
type: pc
race: "Dragon (wizard)"
class:
 - "Tanazir Quandrix"
subClass:
 - "CR 24"
cover: "Tanazir Quandrix.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/24
  - source/scc
---
###### Tanazir Quandrix
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Tanazir Quandrix.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (wizard) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 444 (24d20 + 192) |
> | :FasUserGroup: Race | Dragon (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 14 | 27 | 28 | 18 | 17 |
| **Mod** | +9 | +2 | +8 | +9 | +4 | +3 |

**Speed:** 40 ft., fly 80 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 28
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +15, Wis +11, Cha +10
**Skills:** Arcana +23, Investigation +23, Nature +16, Perception +18
**Damage Immunities:** force; psychic

---

### Traits

**Legendary Resistance (3/Day).** If Tanazir fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Tanazir makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 14 (1d10 + 9) piercing damage plus 7 (2d6) force damage.

**Claw.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 16 (2d6 + 9) slashing damage. If the target is a creature, it is addled by recursive thoughts, reducing its speed to 0 until the start of Tanazir's next turn.

**Diminution Breath (Recharge 5–6).** Tanazir exhales a weakening equation in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw. On a failed save, a creature takes 45 (13d6) force damage and 45 (13d6) psychic damage and is weakened until the start of Tanazir's next turn. While weakened, it has disadvantage on the following rolls that rely on Strength: attack rolls, ability checks, and saving throws. On a successful save, a creature takes half as much damage and isn't weakened.

**Teleport.** Tanazir teleports to an unoccupied space she can see within 100 feet of herself.


---

### Legendary Actions

### 

**Claw.** Tanazir makes one Claw attack.

**Fold Space (Costs 2 Actions).** Tanazir uses Teleport, and each other creature within 20 feet of the space she left must succeed on a DC 24 Strength saving throw or be pulled up to 30 feet closer to the center of that space and take 16 (3d10) force damage.

**Fractal Refraction (Costs 3 Actions).** Tanazir magically summons 1d4 [[Fractal Mascot|fractal mascots]] in unoccupied spaces she can see within 120 feet of herself. The fractals obey her commands and take their turns immediately after hers. While any of these fractals remain, attack rolls made against Tanazir have disadvantage. A summoned fractal disappears after 1 minute, when it or Tanazir dies, or when she uses this action again.


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