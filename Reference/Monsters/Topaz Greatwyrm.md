---
type: pc
race: "Dragon (gem)"
class:
 - "Topaz Greatwyrm"
subClass:
 - "CR 26"
cover: "Topaz Greatwyrm.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/26
  - source/ftd
---
###### Topaz Greatwyrm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Topaz Greatwyrm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (gem) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 507 (26d20 + 234) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 14 | 29 | 30 | 24 | 25 |
| **Mod** | +9 | +2 | +9 | +10 | +7 | +7 |

**Speed:** 60 ft., burrow 60 ft., fly 120 ft. ((hover)), swim 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 25
**Languages:** Common, Draconic
**Saving Throws:** Dex +10, Con +17, Wis +15, Cha +15
**Skills:** Arcana +26, History +18, Perception +15
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; frightened; poisoned; prone

---

### Traits

**Gem Awakening (Recharges after a Short or Long Rest).** If the greatwyrm would be reduced to 0 hit points, its current hit point total instead resets to 400 hit points, it recharges its Breath Weapon, and it regains any expended uses of Legendary Resistance. Additionally, the greatwyrm can now use its Mass Telekinesis action during the next hour. Award a party an additional 90,000 XP (180,000 XP total) for defeating the greatwyrm after its Gem Awakening activates.

**Legendary Resistance (4/Day).** If the greatwyrm fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The greatwyrm doesn't require food or drink.


---

### Actions

**Multiattack.** The greatwyrm makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +17 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) piercing damage plus 16 (3d10) force damage.

**Claw.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 18 (2d8 + 9) slashing damage. If the target is a Huge or smaller creature, it is grappled (escape DC 19) and is restrained until this grapple ends. The greatwyrm can have only one creature grappled in this way at a time.

**Breath Weapon (Recharge 5–6).** The greatwyrm exhales crushing force in a 300-foot cone. Each creature in that area must make a DC 25 Dexterity saving throw. On a failed save, the creature takes 71 (11d12) force damage and is knocked prone. On a successful save, it takes half as much damage and isn't knocked prone. On a success or failure, the creature's speed becomes 0 until the end of its next turn.

**Mass Telekinesis (Gem Awakening Only; Recharges after a Short or Long Rest).** The greatwyrm targets any number of creatures and objects it can see within 120 feet of it. No one target can weigh more than 4,000 pounds, and objects can't be targeted if they're being worn or carried. Each targeted creature must succeed on a DC 26 Strength saving throw or be restrained in the greatwyrm's telekinetic grip. At the end of a creature's turn, it can repeat the saving throw, ending the effect on itself on a success.
At the end of the greatwyrm's turn, it can move each creature or object it has in its telekinetic grip up to 60 feet in any direction, but not beyond 120 feet of itself. In addition, it can choose any number of creatures restrained in this way and deal 45 (7d12) force damage to each of them.


---

### Bonus Actions

**Change Shape.** The greatwyrm magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the greatwyrm is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The greatwyrm magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The greatwyrm makes one Claw attack.

**Psionics (Costs 2 Actions).** The greatwyrm uses Psychic Step or Spellcasting.

**Psychic Beam (Costs 3 Actions).** The greatwyrm emits a beam of psychic energy in a 90-foot line that is 10 feet wide. Each creature in that area must make a DC 26 Intelligence saving throw, taking 27 (5d10) psychic damage on a failed save, or half as much damage on a successful one.


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