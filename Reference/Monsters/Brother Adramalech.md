---
type: pc
race: "Fiend (devil)"
class:
 - "Brother Adramalech"
subClass:
 - "CR 21"
cover: "Brother Adramalech.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/21
  - source/coa
---
###### Brother Adramalech
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Brother Adramalech.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 212 (25d8 + 100) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 18 | 25 | 25 | 25 |
| **Mod** | +2 | +3 | +4 | +7 | +7 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Int +14, Wis +14, Cha +14
**Skills:** Arcana +14, Deception +21, Insight +14, Intimidation +14, Persuasion +21, Religion +14
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Adramalech's darkvision.

**Magic Resistance.** Adramalech has advantage on saving throws against spells and other magical effects.

**Unbreakable Bond.** If Adramalech is reduced to 0 hit points while Brother Morax still lives, Adramalech regenerates 50 hit points at the start of his next turn. This regeneration is interrupted if Brother Morax is reduced to 0 hit points before the start of Adramalech's turn.


---

### Actions

**Multiattack.** Adramalech makes four attacks using Mental

**Barrage.** He can replace one of the attacks with Brain Freeze or Cone of Madness (if available).

**Mental Barrage.** Melee or Ranged Weapon Attack: +14 to hit, reach 5 ft. or range 60/120 ft., one target. *Hit:* 25 (4d8 + 7) psychic damage.

**Brain Freeze.** Adramalech attempts to overload the brain of a creature he can see within 60 feet of him. The target must make a DC 22 Intelligence saving throw, taking 22 (4d10) psychic damage on a failed save, or half as much on a successful one. Creatures that fail the saving throw have the stunned condition for up to 1 minute. A stunned creature may repeat the saving throw at the end of each of their turns, ending the effect on a success.

**Cone of Madness (Recharge 4–6).** Adramalech unleashes visions in a 30-foot cone in front of him. All creatures in the cone must make a DC 22 Wisdom saving throw, taking 17 (5d6) psychic damage on a failed save, or half as much on a successful one. For up to 1 minute, creatures that failed the save can't take reactions and each turn must use their action to make a melee attack against the nearest creature. Creatures may repeat the saving throw at the end of each of their turns, ending the effect on a success.


---

### Bonus Actions

**Conjure Effigy (Recharge 6).** Adramalech targets a creature, reading its thoughts and creating an effigy of a loved one in an unoccupied space that he can see within 60 feet of Adramalech. The effigy has 55 (10d10) hit points, an AC of 10, and ability scores of 10. It occasionally shouts for help, but otherwise takes no actions. While the effigy is alive, the target creature has disadvantage on attacks targeting Adramalech and any time the effigy takes damage, the target creature also takes an equal amount as psychic damage. If the effigy is killed, the target creature gains a level of exhaustion. If Adramalech is killed while effigies exist, they harmlessly melt into a warm sludge.


---

### Legendary Actions

### 

**Barrage.** Adramalech makes a Mental Barrage attack.

**Mental Blocker.** Adramalech fortifies the mind of a creature he can see within 60 feet of him, or himself. The target benefits as if the Greater Restoration spell has been cast on them and is granted resistance to psychic damage until the end of Adramalech's next turn.


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