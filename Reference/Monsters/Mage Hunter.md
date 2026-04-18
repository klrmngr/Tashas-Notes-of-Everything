---
type: pc
race: "Monstrosity"
class:
 - "Mage Hunter"
subClass:
 - "CR 5"
cover: "Mage Hunter.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/scc
---
###### Mage Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Mage Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 11 | 17 | 10 |
| **Mod** | +4 | +2 | +3 | +0 | +3 | +0 |

**Speed:** 40 ft., climb 40 ft. ((hunter form only)), fly 10 ft. ((hover sentry form only)) (hover) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 19
**Languages:** understands Common but can't speak
**Saving Throws:** Int +3, Wis +6, Cha +3
**Skills:** Perception +9, Stealth +5
**Condition Immunities:** blinded; charmed; deafened; frightened; prone

---

### Traits

**Magic Sense.** The hunter knows the location of every spellcaster, active spell, and magic item within 120 feet of itself.

**Spider Climb (Hunter Form Only).** The hunter can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack (Hunter Form Only).** The hunter makes two Claw attacks.

**Claw (Hunter Form Only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) slashing damage.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 22 (4d8 + 4) piercing damage, and the target is grappled (escape DC 15). Until this grapple ends, the target is restrained, and the hunter can't make a Tail attack against another target.

**Mage Tracker (Sentry Form Only).** The hunter emits a pulse of energy that helps it better locate its magical quarry. Each creature within 120 feet of the hunter that has the ability to cast spells must succeed on a DC 14 Wisdom saving throw or be mystically marked by the hunter for 1 hour.
While marked, a creature can't become hidden from the hunter and gains no benefit from the invisible condition against the hunter. Additionally, while a marked creature is on the same plane of existence as the hunter, the hunter always knows the distance and direction to the creature.


---

### Bonus Actions

**Shift Form.** The hunter folds into its drone-like sentry form or unfolds into its hunter form. Its game statistics are the same in each form.


---

### Reactions

**Consume and Destroy.** When the hunter takes damage from a spell, it takes only half the triggering damage (rounded down). If the creature that cast the spell is within 60 feet of the hunter, that creature must succeed on a DC 14 Dexterity saving throw or take the other half of the damage.


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