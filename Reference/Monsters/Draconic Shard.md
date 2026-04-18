---
type: pc
race: "Undead"
class:
 - "Draconic Shard"
subClass:
 - "CR 17"
cover: "Draconic Shard.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/17
  - source/ftd
---
###### Draconic Shard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconic Shard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (deflection) |
> | :FasHeart: HP | 168 (16d12 + 64) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 12 | 18 | 22 | 18 | 22 |
| **Mod** | -5 | +1 | +4 | +6 | +4 | +6 |

**Speed:** 0 ft., fly 80 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +7, Int +12, Wis +10, Cha +12
**Skills:** Arcana +12, History +12, Perception +16, Stealth +7
**Damage Resistances:** acid; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone

---

### Traits

**Deflection.** The shard's AC includes its Intelligence modifier.

**Incorporeal Movement.** The shard can move through creatures and objects as if they were 3. If it ends its turn inside an object, it takes 5 (1d10) force damage.

**Legendary Resistance (3/Day).** If the shard fails a saving throw, it can choose to succeed instead.

**Rejuvenation.** When it drops to 0 hit points, the shard disappears and leaves a Tiny cracked gemstone in its space. The gemstone matches the kind of gem dragon it was in life and has AC 20, 15 hit points, and immunity to all damage except force. Unless the gemstone is destroyed, after 1d20 days, the gemstone dissipates and the shard re-forms, regaining all its hit points and appearing in the place the gemstone once occupied or in the nearest unoccupied space.

**Unusual Nature.** The shard doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The shard makes two Telekinetic Rend attacks.

**Telekinetic Rend.** Melee or Ranged Spell Attack: +12 to hit, reach 10 ft. or range 120 ft., one target. *Hit:* 15 (2d8 + 6) force damage.

**Inhabit Object.** The shard disappears as it pours its psychic essence into a Medium or smaller nonsentient object it can see within 30 feet of it, magically possessing it. The object uses the shard's AC, and any damage dealt to the object applies to the shard's hit points. The shard inhabits the object until it uses an action to leave; until it is turned; until it is reduced to 0 hit points; or until an effect that ends possession, such as a dispel evil and good spell, is used on it. When it leaves the object, it reappears in the nearest unoccupied space.
While inhabited, the object becomes a magic item if it wasn't already, and a Tiny cracked gemstone matching the kind of gem dragon the shard was in life appears somewhere on the object. The shard can cause the object to fly using the shard's own flying speed, use its senses, speak verbally or telepathically, cast spells, and use its legendary actions.
If a creature wears or carries the inhabited object, the shard can grant the creature the following benefits:
Each of the creature's attacks deals an extra 1d8 force damage on a hit.
The creature gains resistance to psychic damage.

**Psychic Crush (Recharge 5–6).** The shard unleashes a pulse of psychic power. Each creature of the shard's choice in a 60-foot-radius sphere centered on it must make a DC 20 Intelligence saving throw. On a failed save, the creature takes 55 (10d10) psychic damage and is stunned until the end of its next turn. On a successful save, the creature takes half as much damage and isn't stunned.


---

### Legendary Actions

### 

**Rend.** The shard makes one Telekinetic Rend attack.

**Cast a Spell (Costs 2 Actions).** The shard uses Spellcasting.

**Commanding Thought (Costs 2 Actions).** The shard targets a creature it can see within 30 feet of it. The target must succeed on a DC 20 Wisdom saving throw or be charmed until the end of its next turn. While charmed in this way, the target becomes the shard's puppet, acting and moving in accordance with its telepathic commands. While under the shard's control, the target can take only the Attack (shard chooses the target) or Dash action on its turn.


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