---
type: pc
race: "Monstrosity"
class:
 - "Arasta"
subClass:
 - "CR 21"
cover: "Arasta.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/21
  - source/mot
---
###### Arasta
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Arasta.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 300 (24d12 + 144) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 16 | 23 | 15 | 22 | 17 |
| **Mod** | +7 | +3 | +6 | +2 | +6 | +3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** Celestial, Common, Sylvan
**Saving Throws:** Dex +10, Con +13, Wis +13
**Skills:** Arcana +9, Deception +10, Intimidation +10, Nature +9, Perception +13, Stealth +10
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Armor of Spiders (Mythic Trait; Recharges after a Short or Long Rest).** If Arasta is reduced to 0 hit points, she doesn't die or fall unconscious. Instead, she regains 200 hit points. In addition, Arasta's children immediately swarm over her body to protect her, granting her 100 temporary hit points.

**Legendary Resistance (3/Day).** If Arasta fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Arasta has advantage on saving throws against spells and other magical effects.

**Spider Climb.** Arasta can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Walker.** Arasta ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** Arasta makes three attacks: one with her bite and two with her claws.

**Bite.** Melee Weapon Attack: +14 to hit, reach 5 ft., one creature. *Hit:* 20 (3d8 + 7) piercing damage, and the target must make a DC 21 Constitution saving throw, taking 32 (5d12) poison damage on a failed save, or half as much damage on a successful one. If the damage reduces the target to 0 hit points, the target is stable but poisoned for 1 hour, even after regaining hit points, and is paralyzed while poisoned in this way.

**Claws.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 17 (3d6 + 7) slashing damage.

**Web of Hair (Recharge 4–6).** Arasta unleashes her hair in the form of webbing that fills a 30-foot cube next to her. The web is 3, its area is lightly obscured, and it lasts for 1 minute. Any creature that moves into the web or that starts its turn there must make a DC 21 Dexterity saving throw. On a failed save, the creature is restrained while in the web. A creature can use an action to make a DC 21 Strength check. On a success, it can free itself or a creature within 5 feet of it that is restrained by the web. This webbing is immune to all damage except magical fire. A 5-foot cube of the web is destroyed if it takes at least 20 fire damage from a spell or other magical source on a single turn.


---

### Legendary Actions

### 

**Claws.** Arasta makes one attack with her claws.

**Swarm (Costs 2 Actions).** Arasta causes two [[Swarm Of Spiders|swarms of spiders]] to appear in unoccupied spaces within 5 feet of her.

**Toxic Web (Costs 3 Actions).** Each creature restrained by Arasta's Web of Hair takes 18 (4d8) poison damage.


---

### Mythic Actions

If Arasta's mythic trait is active, she can use the options below as legendary actions, as long as she has temporary hit points from her Armor of Spiders.

### 

**Swipe.** Arasta makes two attacks with her claws.

**Web of Hair (Costs 2 Actions).** Arasta recharges Web of Hair and uses it.

**Nyx Weave (Costs 2 Actions).** Each creature restrained by Arasta's Web of Hair must succeed on a DC 21 Constitution saving throw, or the creature takes 26 (4d12) force damage and any spell of 6th level or lower on it ends.


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