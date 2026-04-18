---
type: pc
race: "Fiend (devil)"
class:
 - "Red Abishai"
subClass:
 - "CR 19"
cover: "Red Abishai.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/19
  - source/mpmm
---
###### Red Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Red Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 289 (34d8 + 136) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 19 | 14 | 15 | 19 |
| **Mod** | +6 | +3 | +4 | +2 | +2 | +4 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +12, Con +10, Wis +8
**Skills:** Intimidation +10, Perception +8
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the abishai's darkvision.

**Magic Resistance.** The abishai has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The abishai makes one Bite attack and one Claw attack, and it can use Frightful Presence or Incite Fanaticism.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage plus 38 (7d10) fire damage.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) force damage plus 11 (2d10) fire damage.

**Frightful Presence.** Each creature of the abishai's choice that is within 120 feet and aware of the abishai must succeed on a DC 18 Wisdom saving throw or become frightened of it for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the abishai's Frightful Presence for the next 24 hours.

**Incite Fanaticism.** The abishai chooses up to four other creatures within 60 feet of it that can see it. Until the start of the abishai's next turn, each of those creatures makes attack rolls with advantage and can't be frightened.

**Power of the Dragon Queen.** The abishai targets one Dragon it can see within 120 feet of it. The Dragon must make a DC 18 Charisma saving throw. A chromatic dragon makes this save with disadvantage. On a successful save, the target is immune to the abishai's Power of the Dragon Queen for 1 hour. On a failed save, the target is charmed by the abishai for 1 hour. While charmed in this way, the target regards the abishai as a trusted friend to be heeded and protected. This effect ends if the abishai or its companions deal damage to the target.


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