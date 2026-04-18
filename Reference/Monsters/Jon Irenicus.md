---
type: pc
race: "Undead"
class:
 - "Jon Irenicus"
subClass:
 - "CR 22"
cover: "Jon Irenicus.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/22
  - source/mabjov
---
###### Jon Irenicus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Jon Irenicus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 217 (29d8 + 87) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 16 | 22 | 14 | 16 |
| **Mod** | +4 | +3 | +3 | +6 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Abyssal, Celestial, Common, Elvish, Infernal, Sylvan
**Saving Throws:** Con +10, Int +13, Wis +9
**Skills:** Arcana +20, History +13, Insight +9, Perception +9
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Jon Irenicus fails a saving throw, he can choose to succeed instead.

**Rejuvenation.** If he has a phylactery and he is destroyed, Jon Irenicus gains a new body in 1d10 days, regaining all his hit points and becoming active again. The new body appears within 5 feet of the phylactery.

**Special Equipment.** Jon Irenicus carries a rod of lordly might. He can use a bonus action to switch it between its Mace and Flame Tongue attacks.

**Turn Resistance.** Jon Irenicus has advantage on saving throws against any effect that turns Undead.


---

### Actions

**Multiattack (only useable with Transformation).** Jon Irenicus makes two Flame Tongue attacks or two Mace attacks. Each attack is made with advantage and does an additional 13 (2d12) force damage if it hits.

**Flame Tongue (Rod of Lordly Might).** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 11 (1d8 + 7) slashing damage and 7 (2d6) fire damage.

**Mace (Rod of Lordly Might).** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 10 (1d6 + 7) bludgeoning damage.

**Breath of Death (1/Day).** Jon Irenicus emits a 90-foot cone of necrotic energy. Each creature in the effects area must make a DC 21 saving throw, taking 55 (10d10) necrotic damage on a failed save, half as much damage on a successful one.


---

### Reactions

**Draining Counterspell.** Jon Irenicus interrupts a creature he can see that is casting a spell. If the spell is 3rd level or lower, it fails and has no effect. If the spell is 4th level or higher, Jon Irenicus makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect. Whatever the spell's level, the caster takes 10 (3d6) necrotic damage if the spell fails.


---

### Legendary Actions

### 

**Drain Life (1/Day).** Jon Irenicus makes a drain life attack with his rod of lordly might. If he hits a creature with his rod, the creature must make a DC 17 Constitution saving throw. On a failed save, the creature takes an extra 14 (4d6) necrotic damage, and Jon regains a number of hit points equal to half that necrotic damage.

**Paralyze (1/Day).** Jon Irenicus makes a paralyze attack with his rod of lordly might. If he hits a creature with his rod, the creature must make a DC 17 Strength saving throw. On a failed save, the creature has the paralyzed condition for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.

**Cast a Spell (Costs 2 Actions).** Jon Irenicus uses Spellcasting.

**Transformation (Costs 3 Actions).** Jon Irenicus becomes endowed with endurance and martial prowess for 1 minute or until he ends this effect by using a bonus action. While transformed, he gains 50 temporary hit points, proficiency in Strength and Constitution saving throw, adds his Multiattack feature, and loses his Draining Counterspell reaction and Spellcasting action.


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