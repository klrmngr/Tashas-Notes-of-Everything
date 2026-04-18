---
type: pc
race: "Aberration"
class:
 - "Elder Brain"
subClass:
 - "CR 14"
cover: "Elder Brain.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/14
  - source/vgm
---
###### Elder Brain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Elder Brain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 210 (20d10 + 100) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 20 | 21 | 19 | 24 |
| **Mod** | +2 | +0 | +5 | +5 | +4 | +7 |

**Speed:** 5 ft., swim 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 14
**Languages:** understands Common, Deep Speech, and Undercommon but can't speak, telepathy 5 miles
**Saving Throws:** Int +10, Wis +9, Cha +12
**Skills:** Arcana +10, Deception +12, Insight +14, Intimidation +12, Persuasion +12

---

### Traits

**Creature Sense.** The elder brain is aware of the presence of creatures within 5 miles of it that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each one's intelligence score, but can't sense anything else about it. A creature protected by a mind blank spell, a nondetection spell, or similar magic can't be perceived in this manner.

**Legendary Resistance (3/Day).** If the elder brain fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The elder brain has advantage on saving throws against spells and other magical effects.

**Telepathic Hub.** The elder brain can use its telepathy to initiate and maintain telepathic conversations with up to ten creatures at a time. The elder brain can let those creatures telepathically hear each other while connected in this way.


---

### Actions

**Tentacle.** Melee Weapon Attack: +7 to hit, reach 30 ft., one target. *Hit:* 20 (4d8 + 2) bludgeoning damage. If the target is a Huge or smaller creature, it is grappled (escape DC 15) and takes 9 (1d8 + 5) psychic damage at the start of each of its turns until the grapple ends. The elder brain can have up to four targets grappled at a time.

**Mind Blast (Recharge 5–6).** The elder brain magically emits psychic energy. Creatures of the elder brain's choice within 60 feet of it must succeed on a DC 18 Intelligence saving throw or take 32 (5d10 + 5) psychic damage and be stunned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Psychic Link.** The elder brain targets one incapacitated creature it can perceive with its Creature Sense trait and establishes a psychic link with that creature. Until the psychic link ends, the elder brain can perceive everything the target senses. The target becomes aware that something is linked to its mind once it is no longer incapacitated, and the elder brain can terminate the link at any time (no action required). The target can use an action on its turn to attempt to break the psychic link, doing so with a successful DC 18 Charisma saving throw. On a successful save, the target takes 10 (3d6) psychic damage. The psychic link also ends if the target and the elder brain are more than 5 miles apart, with no consequences to the target. The elder brain can form psychic links with up to ten creatures at a time.

**Sense Thoughts.** The elder brain targets a creature with which it has a psychic link. The elder brain gains insight into the target's reasoning, its emotional state, and thoughts that loom large in its mind (including things the target worries about, loves, or hates). The elder brain can also make a Charisma (Deception) check with advantage to deceive the target's mind into thinking it believes one idea or feels a particular emotion. The target contests this attempt with a Wisdom (Insight) check. If the elder brain succeeds, the mind believes the deception for 1 hour or until evidence of the lie is presented to the target.


---

### Legendary Actions

### 

**Tentacle.** The elder brain makes a tentacle attack.

**Break Concentration.** The elder brain targets a creature within 120 feet of it with which it has a psychic link. The elder brain breaks the creature's concentration on a spell it has cast. The creature also takes 1d4 psychic damage per level of the spell.

**Psychic Pulse.** The elder brain targets a creature within 120 feet of it with which it has a psychic link. Enemies of the elder brain within 10 feet of that creature take 10 (3d6) psychic damage.

**Sever Psychic Link.** The elder brain targets a creature within 120 feet of it with which it has a psychic link. The elder brain ends the link, causing the creature to have disadvantage on all ability checks, attack rolls, and saving throws until the end of the creature's next turn.


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