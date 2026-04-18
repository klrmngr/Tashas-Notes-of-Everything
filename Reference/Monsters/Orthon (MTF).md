---
type: pc
race: "Fiend (devil)"
class:
 - "Orthon"
subClass:
 - "CR 10"
cover: "Orthon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/10
  - source/mtf
---
###### Orthon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Orthon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 105 (10d10 + 50) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 21 | 15 | 15 | 16 |
| **Mod** | +6 | +3 | +5 | +2 | +2 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 30 ft., passive Perception 20
**Languages:** Common, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +9, Wis +6
**Skills:** Perception +10, Stealth +11, Survival +10
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Invisibility Field.** The orthon can use a bonus action to become invisible. Any equipment the orthon wears or carries is also invisible as long as the equipment is on its person. This invisibility ends immediately after the orthon makes an attack roll or is hit by an attack.

**Magic Resistance.** The orthon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Infernal Dagger.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 11 (2d4 + 6) slashing damage, and the target must make a DC 17 Constitution saving throw, taking 22 (4d10) poison damage on a failed save, or half as much damage on a successful one. On a failure, the target is poisoned for 1 minute. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Brass Crossbow.** Ranged Weapon Attack: +7 to hit, range 100/400 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage, plus one of the following effects:
- **1. Acid.** The target must make a DC 17 Constitution saving throw, taking an additional 17 (5d6) acid damage on a failed save, or half as much damage on a successful one.
- **2. Blindness (1/Day).** The target takes 5 (1d10) radiant damage. In addition, the target and all other creatures within 20 feet of it must each make a successful DC 17 Dexterity saving throw or be blinded until the end of the orthon's next turn.
- **3. Concussion.** The target and each creature within 20 feet of it must make a DC 17 Constitution saving throw, taking 13 (2d12) thunder damage on a failed save, or half as much damage on a successful one.
- **4. Entanglement.** The target must make a successful DC 17 Dexterity saving throw or be restrained for 1 hour by strands of sticky webbing. A restrained creature can escape by using an action to make a successful DC 17 Dexterity or Strength check. Any creature other than an orthon that touches the restrained creature must make a successful DC 17 Dexterity saving throw or become similarly restrained.
- **5. Paralysis (1/Day).** The target takes 22 (4d10) lightning damage and must make a successful DC 17 Constitution saving throw or be paralyzed for 1 minute. The paralyzed target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- **6. Tracking.** For the next 24 hours, the orthon knows the direction and distance to the target, as long as it's on the same plane of existence. If the target is on a different plane, the orthon knows which one, but not the exact location there.


---

### Reactions

**Explosive Retribution.** When it is reduced to 15 hit points or fewer, the orthon causes itself to explode. All other creatures within 30 feet of it must each make a DC 17 Dexterity saving throw, taking 9 (2d8) fire damage plus 9 (2d8) thunder damage on a failed save, or half as much damage on a successful one. This explosion destroys the orthon, its infernal dagger, and its brass crossbow.


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