---
type: pc
race: "Humanoid (warforged)"
class:
 - "The Lord of Blades"
subClass:
 - "CR 18"
cover: "The Lord of Blades.png"
campaign:
locations:
tags:
  - race/warforged
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/18
  - source/erlw
---
###### The Lord of Blades
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[The Lord of Blades.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warforged) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 195 (23d8 + 92) |
> | :FasUserGroup: Race | Humanoid (warforged) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 18 | 19 | 17 | 18 |
| **Mod** | +5 | +2 | +4 | +4 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Common, Draconic, Dwarvish, Elvish
**Saving Throws:** Str +11, Con +10, Int +10, Wis +9
**Skills:** Arcana +10, Athletics +11, History +10, Perception +9
**Damage Resistances:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; disease

---

### Traits

**Adamantine Plating.** Any critical hit against the Lord of Blades becomes a normal hit.

**Bladed Armor.** A creature that grapples the Lord of Blades or is grappled by him takes 13 (3d8) slashing damage. A creature takes 13 (3d8) slashing damage if it starts its turn grappling or being grappled by the Lord of Blades.

**Charge.** If the Lord of Blades moves at least 10 feet straight toward a target and then hits it with his adamantine sixblade on the same turn, the target takes an extra 11 (2d10) slashing damage. If the target is a creature, it must succeed on a DC 19 Strength saving throw or be pushed up to 10 feet away and knocked prone.

**Warforged Resilience.** The Lord of Blades has advantage on saving throws against being poisoned, is immune to disease, and magic can't put him to sleep.


---

### Actions

**Multiattack.** The Lord of Blades makes three attacks: two with his adamantine sixblade and one with his bladed wings.

**Adamantine Sixblade.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) slashing damage plus 7 (2d6) force damage.

**Bladed Wings.** Melee or Ranged Weapon Attack: +11 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage.

**Fire Bolt (Cantrip).** Ranged Spell Attack: +10 to hit, range 120 ft., one target. *Hit:* 22 (4d10) fire damage.


---

### Legendary Actions

### 

**Attack.** The Lord of Blades makes one weapon attack.

**Cantrip.** The Lord of Blades casts one of his cantrips.

**Cast a Spell (Costs 2 Actions).** The Lord of Blades casts a spell of 2nd level or lower from his spell list that takes 1 action to cast.

**Blade Dash (Costs 3 Actions).** The Lord of Blades moves up to his speed without provoking opportunity attacks, then makes one attack with his adamantine sixblade. He can make one bladed wings attack against each creature he moves past.


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