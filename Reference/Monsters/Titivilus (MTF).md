---
type: pc
race: "Fiend (devil)"
class:
 - "Titivilus"
subClass:
 - "CR 16"
cover: "Titivilus.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/16
  - source/mtf
---
###### Titivilus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Titivilus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 22 | 17 | 24 | 22 | 26 |
| **Mod** | +4 | +6 | +3 | +7 | +6 | +8 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +11, Con +8, Wis +11, Cha +13
**Skills:** Deception +13, Insight +11, Intimidation +13, Persuasion +13
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Titivilus fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Titivilus has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Titivilus's weapon attacks are magical.

**Regeneration.** Titivilus regains 10 hit points at the start of his turn. If he takes cold or radiant damage, this trait doesn't function at the start of his next turn. Titivilus dies only if he starts his turn with 0 hit points and doesn't regenerate.

**Ventriloquism.** Whenever Titivilus speaks, he can choose a point within 60 feet; his voice emanates from that point.


---

### Actions

**Multiattack.** Titivilus makes one sword attack and uses his Frightful Word once.

**Silver Sword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 16 (3d10) necrotic damage, or 9 (1d10 + 4) slashing damage plus 16 (3d10) necrotic damage if used with two hands. If the target is a creature, its hit point maximum is reduced by an amount equal to half the necrotic damage it takes.

**Frightful Word.** Titivilus targets one creature he can see within 10 feet of him. The target must succeed on a DC 21 Wisdom saving throw or become frightened for 1 minute. While frightened in this way, the target must take the Dash action and move away from Titivilus by the safest available route on each of its turns, unless there is nowhere to move, in which case it needn't take the Dash action. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Teleport.** Titivilus magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

**Twisting Words.** Titivilus targets one creature he can see within 60 feet of him. The target must make a DC 21 Charisma saving throw. On a failure the target is charmed for 1 minute. The charmed target can repeat the saving throw if Titivilus deals any damage to it. A creature that succeeds on the saving throw is immune to Titivilus's Twisting Words for 24 hours.


---

### Legendary Actions

### 

**Assault (Costs 2 Actions).** Titivilus attacks with his silver sword or uses his Frightful Word.

**Corrupting Guidance.** Titivilus uses Twisting Words. Alternatively, he targets one creature charmed by him that is within 60 feet of him; that charmed target must make a DC 21 Charisma saving throw. On a failure, Titivilus decides how the target acts during its next turn.

**Teleport.** Titivilus uses his Teleport action.


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