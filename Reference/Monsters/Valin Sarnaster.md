---
type: pc
race: "Undead"
class:
 - "Valin Sarnaster"
subClass:
 - "CR 16"
cover: "Valin Sarnaster.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/16
  - source/cm
---
###### Valin Sarnaster
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Valin Sarnaster.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 97 (13d8 + 39) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 17 | 11 | 18 | 16 |
| **Mod** | +4 | +0 | +3 | +0 | +4 | +3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** The languages it knew in life
**Saving Throws:** Con +8, Int +5, Wis +9, Cha +8
**Skills:** History +5, Religion +5
**Damage Vulnerabilities:** fire
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Magic Resistance.** Valin has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** While her heart remains in Alessia's body, Valin re-forms inside her sarcophagus, regaining all her hit points and becoming active again.


---

### Actions

**Multiattack.** Valin can use her Dreadful Glare and makes one attack with her rotting fist.

**Rotting Fist.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the remove curse spell or other magic.

**Dreadful Glare.** Valin targets one creature she can see within 60 feet of her. If the target can see Valin, it must succeed on a DC 16 Wisdom saving throw against this magic or become frightened until the end of Valin's next turn. If the target fails the saving throw by 5 or more, it is also paralyzed for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies and mummy lords for the next 24 hours.


---

### Legendary Actions

### 

**Attack.** Valin makes one attack with her rotting fist or uses her Dreadful Glare.

**Blinding Dust.** Blinding dust and sand swirls magically around Valin. Each creature within 5 feet of Valin must succeed on a DC 16 Constitution saving throw or be blinded until the end of her next turn.

**Blasphemous Word (Costs 2 Actions).** Valin utters a blasphemous word. Each non-undead creature within 10 feet of Valin that can hear the magical utterance must succeed on a DC 16 Constitution saving throw or be stunned until the end of Valin's next turn.

**Channel Negative Energy (Costs 2 Actions).** Valin magically unleashes negative energy. Creatures within 60 feet of Valin, including ones behind barriers and around corners, can't regain hit points until the end of Valin's next turn.

**Whirlwind of Sand (Costs 2 Actions).** Valin magically transforms into a whirlwind of sand, moves up to 60 feet, and reverts to her normal form. While in whirlwind form, Valin is immune to all damage, and it can't be grappled, petrified, knocked prone, restrained, or stunned. Equipment worn or carried by Valin remain in her possession.


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