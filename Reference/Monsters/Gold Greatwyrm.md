---
type: pc
race: "Dragon (metallic)"
class:
 - "Gold Greatwyrm"
subClass:
 - "CR 28"
cover: "Gold Greatwyrm.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/28
  - source/ftd
---
###### Gold Greatwyrm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Gold Greatwyrm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 28 (120,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 565 (29d20 + 261) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 16 | 29 | 21 | 22 | 30 |
| **Mod** | +10 | +3 | +9 | +5 | +6 | +10 |

**Speed:** 60 ft., burrow 60 ft., fly 120 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 32
**Languages:** Common, Draconic
**Saving Throws:** Dex +11, Con +17, Int +13, Wis +14, Cha +18
**Skills:** Insight +14, Perception +22, Persuasion +18
**Damage Immunities:** fire
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (4/Day).** If the greatwyrm fails a saving throw, it can choose to succeed instead.

**Metallic Awakening (Recharges after a Short or Long Rest).** If the greatwyrm would be reduced to 0 hit points, its current hit point total instead resets to 450 hit points, it recharges its Breath Weapon, and it regains any expended uses of Legendary Resistance. Additionally, the greatwyrm can now use the options in the "Mythic Actions" section for 1 hour. Award a party an additional 120,000 XP (240,000 XP total) for defeating the greatwyrm after its Metallic Awakening activates.

**Unusual Nature.** The greatwyrm doesn't require food or drink.


---

### Actions

**Multiattack.** The greatwyrm makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +18 to hit, reach 15 ft., one target. *Hit:* 21 (2d10 + 10) piercing damage plus 13 (2d12) force damage.

**Claw.** Melee Weapon Attack: +18 to hit, reach 10 ft., one target. *Hit:* 19 (2d8 + 10) slashing damage. If the target is a Huge or smaller creature, it is grappled (escape DC 20) and is restrained until this grapple ends. The greatwyrm can have only one creature grappled in this way at a time.

**Tail.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 21 (2d10 + 10) bludgeoning damage. If the target is a creature, it must succeed on a DC 26 Strength saving throw or be knocked prone.

**Breath Weapon (Recharge 5–6).** The greatwyrm uses one of the following breath weapons:
- **Elemental Breath.** The greatwyrm exhales elemental energy in a 300-foot cone. Each creature in that area must make a DC 25 Dexterity saving throw, taking 84 (13d12) fire damage on a failed save, or half as much damage on a successful one.
- **Sapping Breath.** The greatwyrm exhales gas in a 300-foot cone. Each creature in that area must make a DC 25 Constitution saving throw. On a failed save, the creature falls unconscious for 1 minute. On a successful save, the creature has disadvantage on attack rolls and saving throws until the end of the greatwyrm's next turn. An unconscious creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Change Shape.** The greatwyrm magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses its action to end it.


---

### Legendary Actions

### 

**Attack.** The greatwyrm makes one Claw or Tail attack.

**Wing Attack (Costs 2 Actions).** The greatwyrm beats its wings. Each creature within 30 feet of it must succeed on a DC 26 Dexterity saving throw or take 17 (2d6 + 10) bludgeoning damage and be knocked prone. The greatwyrm can then fly up to half its flying speed.


---

### Mythic Actions

If the greatwyrm's Metallic Awakening trait has activated in the last hour, it can use the options below as legendary actions.

### 

**Bite.** The greatwyrm makes one Bite attack.

**Shattering Roar (Costs 2 Actions).** The greatwyrm unleashes a magical roar. Each creature in a 120-foot-radius sphere centered on the greatwyrm must succeed on a DC 26 Constitution saving throw or take 19 (3d12) thunder damage and be incapacitated until the end of its next turn.


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