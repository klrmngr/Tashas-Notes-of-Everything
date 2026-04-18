---
type: pc
race: "Humanoid (human, warlock)"
class:
 - "Y'demi"
subClass:
 - "CR 9"
cover: "Y'demi.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/scc
---
###### Y'demi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Y'demi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (blood aegis) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Humanoid (human, warlock) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 18 | 20 | 12 | 12 |
| **Mod** | +0 | +2 | +4 | +5 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any four languages
**Saving Throws:** Con +8, Int +9, Wis +5, Cha +5
**Skills:** Deception +9, Medicine +5, Survival +5
**Damage Resistances:** necrotic
**Condition Immunities:** exhaustion

---

### Traits

**Blood Aegis.** The AC of Y'demi includes her Constitution modifier while she isn't wearing armor or wielding a shield.

**Oriq Mask.** Y'demi wears an Oriq mask. While wearing the mask, Y'demi can't be targeted by any divination magic or perceived through magical scrying sensors, and she adds double her proficiency bonus to Charisma (Deception) checks (included above).

**Sanguine Sense.** While Y'demi isn't blinded, she can see any creature that isn't an Undead or a Construct within 60 feet of itself, even through 3, heavily obscured areas, invisibility, or any other phenomena that would prevent sight.


---

### Actions

**Multiattack.** Y'demi makes two Blood Lash attacks.

**Blood Lash.** Melee Spell Attack: +9 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) necrotic damage. If the target is a creature, it can't regain hit points until the start of the Y'demi's next turn.

**Blood Boil (Recharge 4–6).** Y'demi chooses a point within 150 feet of itself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of Y'demi's choice that she can see in that area must make a DC 17 Constitution saving throw. On a failed save, a creature takes 38 (7d10) necrotic damage and is incapacitated until the end of its next turn. On a success, a creature takes half as much damage and isn't incapacitated. A creature dies if reduced to 0 hit points by this necrotic damage.


---

### Bonus Actions

**Sanguine Tentacles (1/Day).** The blood in the copper basin disappears as tentacles of congealed blood fill a 10-foot cube centered at a point on the ground that Y'demi can see within 15 feet of her. The effect lasts for 1 minute, during which time that area is 3. Any creature entering that area for the first time on a turn or starting its turn there must succeed on a DC 13 Dexterity saving throw or be restrained by the tentacles. A creature that starts its turn restrained by the tentacles takes 10 (3d6) bludgeoning damage. A creature restrained by the tentacles can use its action to make either a DC 13 Strength (Athletics) check or a DC 13 Dexterity (Acrobatics) check, ending the restrained condition on itself on a success.


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