---
type: pc
race: "Humanoid (human)"
class:
 - "Sarevok"
subClass:
 - "CR 15"
cover: "Sarevok.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/mabjov
---
###### Sarevok
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Sarevok.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 21 (plate armor of Bhaal) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 18 | 11 | 16 | 14 |
| **Mod** | +5 | +0 | +4 | +0 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +9, Wis +8
**Skills:** History +5, Intimidation +12, Religion +5
**Damage Immunities:** acid; necrotic; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Magic Resistance.** Sarevok has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** If Sarevok is killed he gains a new body in 24 hours, regaining all his hit points and becoming active again. The new body appears on the altar of the temple of Bhaal beneath Baldur's Gate. This ability ceases to function if a cleric of good alignment casts Hallow on the altar in the temple of Bhaal.


---

### Actions

**Multiattack.** Sarevok makes two Longsword attacks. He may replace one of the attacks with a use of Spellcasting.

**Longsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage or 10 (1d10 + 5) if wielded in two hands. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed by Bhaal. The cursed target can't regain hit points. The curse lasts until removed by the remove curse spell or other magic.

**Assassin's Strike.** Sarevok makes a Longsword attack. If he hits the target and has advantage on the attack roll, then he deals an additional 21 (6d6) poison damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the poisoned condition for 10 minutes.


---

### Legendary Actions

### 

**Attack.** Sarevok makes a Longsword attack.

**Unholy Flame.** Sarevok casts sacred flame.

**Channel Bhaal's Hate (Costs 2 Actions).** Sarevok unleashes Bhaal's power. Creatures within 30 feet of Sarevok, including ones behind barriers and around corners, can't regain hit points until the end of Sarevok's next turn.


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