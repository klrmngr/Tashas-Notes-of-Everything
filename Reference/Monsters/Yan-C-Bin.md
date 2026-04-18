---
type: pc
race: "Elemental"
class:
 - "Yan-C-Bin"
subClass:
 - "CR 18"
cover: "Yan-C-Bin.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/18
  - source/pota
---
###### Yan-C-Bin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Yan-C-Bin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 283 (21d12 + 147) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 24 | 24 | 16 | 21 | 23 |
| **Mod** | +4 | +7 | +7 | +3 | +5 | +6 |

**Speed:** 50 ft., fly 150 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 15
**Languages:** Auran
**Saving Throws:** Dex +13, Wis +11, Cha +12
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; poison; thunder
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Air Form.** Yan-C-Bin can enter a hostile creature's space and stop there. He can move through a space as narrow as 1 inch wide without squeezing if air could pass through that space.

**Empowered Attacks.** Yan-C-Bin's slam attacks are treated as magical for the purpose of bypassing resistance and immunity to nonmagical attacks.

**Legendary Resistance (3/Day).** If Yan-C-Bin fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Yan-C-Bin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Yan-C-Bin makes two slam attacks.

**Slam.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) force damage plus 10 (3d6) lightning damage.

**Thundercrack (Recharges after a Short or Long Rest).** Yan-C-Bin unleashes a terrible thundercrack in a 100-foot-radius sphere centered on himself. All other creatures in the area must succeed on a DC 24 Constitution saving throw or take 31 (9d6) thunder damage and be deafened for 1 minute. On a successful save, a creature takes half as much damage and is deafened until the start of Yan-C-Bin's next turn.

**Change Shape.** Yan-C-Bin polymorphs into a Medium humanoid. While in polymorphed form, a swirling breeze surrounds him, his eyes are pale and cloudy, and he loses the Air Form trait. He can remain in polymorphed form for up to 1 hour. Reverting to his true form requires an action.

**Summon Elementals (1/Day).** Yan-C-Bin summons up to three air elementals and loses 30 hit points for each elemental he summons. Summoned elementals have maximum hit points, appear within 100 feet of Yan-C-Bin, and disappear if Yan-C-Bin is reduced to 0 hit points.


---

### Legendary Actions

### 

**Peal of Thunder.** Yan-C-Bin unleashes a peal of thunder that can be heard out to a range of 300 feet. Each creature within 30 feet of Yan-C-Bin takes 5 (1d10) thunder damage.

**Teleport (Costs 2 Actions).** Yan-C-Bin magically teleports up to 120 feet to an unoccupied space he can see. Anything Yan-C-Bin is wearing or carrying is teleported with him.

**Suffocate (Costs 3 Actions).** Yan-C-Bin steals the air of one breathing creature he can see within 60 feet of him. The target must make a DC 21 Constitution saving throw. On a failed save, the target drops to 0 hit points and is dying. On a successful save, the target can't breathe or speak until the start of its next turn.


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