---
type: pc
race: "Fiend (devil)"
class:
 - "Baalzebul"
subClass:
 - "CR 26"
cover: "Baalzebul.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/26
  - source/coa
---
###### Baalzebul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Baalzebul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (devil) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 540 (40d12 + 280) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 15 | 25 | 21 | 24 | 26 |
| **Mod** | +9 | +2 | +7 | +5 | +7 | +8 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., tremorsense 10 ft., passive Perception 17
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Str +17, Con +15, Int +13, Cha +16
**Skills:** Athletics +17, Deception +24, Insight +15, Intimidation +16, Persuasion +16
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Baalzebul's darkvision.

**Fiendish Regeneration.** Baalzebul regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Baalzebul dies only if he starts his turn with 0 hit points and doesn't regenerate.

**Lord of Flies.** Insects don't attack Baalzebul, and he can issue orders to them.

**Legendary Resistance (3/Day).** If Baalzebul fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Baalzebul has advantage on saving throws against spells and other magical effects.

**Stench of the Slug (Slug Form Only).** A creature that starts its turn within 10 feet of Baalzebul must succeed on a DC 21 Constitution saving throw or have the poisoned condition until the start of its next turn. On a successful save, a creature is immune to this stench for 1 hour.


---

### Actions

**Multiattack.** Baalzebul uses Heart of Pestilence (if available), then makes three Slam attacks.

**Slam.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 19 (3d6 + 9) bludgeoning damage plus 7 (2d6) necrotic damage.

**Pungent Eruption (Slug Form Only, Recharge 4-6).** Baalzebul causes refuse and caustic liquid to spill from the ground at a point he can see within 300 feet. Each creature in a 15-foot-radius sphere centered on that point must make a DC 21 Constitution saving throw. Targets take 36 (8d8) acid damage on a failed save, or half as much on a successful one. Creatures that fail the save have the poisoned condition for 1 minute.

**Heart of Pestilence (Recharge 5–6).** Baalzebul channels pestilence into his body, sickening creatures within 50 feet that can see him. Sickened creatures must make a DC 21 Charisma saving throw, followed by a DC 21 Constitution saving throw. Failing the Charisma save makes a creature have the frightened condition, while failing the Constitution save makes a creature weak. While weakened, a creature deals half damage on melee attacks. Both effects last for 1 minute or until a Greater Restoration spell or similar is cast.


---

### Bonus Actions

**Displace.** Baalzebul magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.


---

### Legendary Actions

### 

**Pummel.** Baalzebul makes a Slam attack.

**Teleport.** Baalzebul uses Displace.

**Insect Gorge (Costs 2 Actions).** Baalzebul disgorges a swarm of biting flies at a point he can see within 300 feet of himself. Each creature within a 20-foot-radius sphere centered on that point must make a DC 21 Constitution saving throw. A creature takes 44 (8d10) piercing damage on a failed save, or half as much damage on a successful one. The biting flies persist for 1 minute, or until Baalzebul uses this ability again. Creatures that enter the flies' area or end their turn inside it must repeat the saving throw.

**Call Underling (Costs 3 Actions).** Baalzebul summons an allied [[Bone Devil]] in an unoccupied space that he can see.


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