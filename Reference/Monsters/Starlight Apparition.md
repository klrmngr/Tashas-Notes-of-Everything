---
type: pc
race: "Celestial"
class:
 - "Starlight Apparition"
subClass:
 - "CR 5"
cover: "Starlight Apparition.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/5
  - source/bam
---
###### Starlight Apparition
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Starlight Apparition.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 72 (16d8) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 11 | 10 | 18 | 16 | 16 |
| **Mod** | -5 | +0 | +0 | +4 | +3 | +3 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** the languages it knew in life
**Damage Resistances:** acid; cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; radiant
**Condition Immunities:** blinded; charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Astral Existence.** The apparition can exist only on the Astral Plane. If it is sent to a location not on the Astral Plane, the apparition is destroyed.

**Illumination.** While it has at least 1 hit point, the apparition sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

**Incorporeal Movement.** The apparition can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Unusual Nature.** The apparition doesn't require air, drink, food, or sleep.


---

### Actions

**Radiant Eruption.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 20 (5d6 + 3) radiant damage, and if the target is a creature, it must succeed on a DC 14 Wisdom saving throw or be blinded for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Possession (Recharge 6).** One Humanoid that the apparition can see within 5 feet of itself must succeed on a DC 14 Charisma saving throw or be possessed by the apparition; the apparition then disappears, and the target is incapacitated and loses control of its body. The apparition now controls the body but doesn't deprive the target of awareness. The apparition can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
The possession lasts until the body drops to 0 hit points, the apparition ends it as a bonus action, the body leaves the Astral Plane, or the apparition is forced out by an effect like the dispel evil and good spell. When the possession ends, the apparition reappears in an unoccupied space within 5 feet of the body. If it reappears in a location not on the Astral Plane, the apparition is destroyed. The target is immune to this apparition's Possession for 24 hours after succeeding on the saving throw or after the possession ends.


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