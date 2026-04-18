---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Loup Garou"
subClass:
 - "CR 13"
cover: "Loup Garou.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/13
  - source/vrgr
---
###### Loup Garou
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Loup Garou.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 14 | 16 | 16 |
| **Mod** | +4 | +4 | +4 | +2 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 23
**Languages:** Common (can't speak in wolf form)
**Saving Throws:** Dex +9, Con +9, Cha +8
**Skills:** Perception +13, Stealth +9
**Condition Immunities:** charmed; frightened

---

### Traits

**Blood Frenzy.** The loup garou has advantage on attack rolls against a creature that doesn't have all its hit points.

**Legendary Resistance (2/Day).** When the loup garou fails a saving throw, it can choose to succeed instead.

**Regeneration.** The loup garou regains 10 hit points at the start of each of its turns. If the loup garou takes damage from a silver weapon, this trait doesn't function at the start of the loup garou's next turn. The loup garou dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The loup garou makes two attacks: two with its Longsword (humanoid form) or one with its Bite and one with its Claws (dire wolf or hybrid form).

**Bite (Dire Wolf or Hybrid Form Only).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage plus 14 (4d6) necrotic damage. If the target is a Humanoid, it must succeed on a DC 17 Constitution saving throw or be cursed with loup garou lycanthropy.

**Claws (Dire Wolf or Hybrid Form Only).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.

**Longsword (Humanoid Form Only).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage, or 15 (2d10 + 4) slashing damage if used with two hands.


---

### Bonus Actions

**Change Shape.** The loup garou polymorphs into a Large wolf-humanoid hybrid or into a Large dire wolf, or back into its true form, which appears humanoid. Its statistics, other than its size and speed, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


---

### Legendary Actions

### 

**Swipe.** The loup garou makes one Claws attack (dire wolf or hybrid form only) or one Longsword attack (humanoid form only).

**Mauling Pounce (Costs 2 Actions).** The loup garou moves up to its speed without provoking opportunity attacks, and it can make one Claws attack (dire wolf or hybrid form only) or one Longsword attack (humanoid form only) against each creature it moves past.

**Bite (Costs 3 Actions).** The loup garou changes into hybrid or dire wolf form and then makes one Bite attack.


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