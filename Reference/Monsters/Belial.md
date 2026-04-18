---
type: pc
race: "Fiend (devil)"
class:
 - "Belial"
subClass:
 - "CR 25"
cover: "Belial.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/25
  - source/coa
---
###### Belial
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Belial.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 420 (40d8 + 240) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 17 | 22 | 22 | 22 | 29 |
| **Mod** | +7 | +3 | +6 | +6 | +6 | +9 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 24
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +15, Dex +11, Con +14, Wis +14
**Skills:** Athletics +15, Deception +25, Insight +14, Intimidation +17, Perception +14, Persuasion +25
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Deep Wounds.** All damage dealt by Belial can only be restored through magical means.

**Devil's Sight.** Magical darkness doesn't impede Belial's darkvision.

**Fear Aura.** When a creature starts their turn within 120 feet of Belial, they must succeed on a DC 22 Wisdom saving throw or have the frightened condition until they leave the aura. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

**Fiendish Regeneration.** Belial regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Belial dies only if he starts his turn with 0 hit points and doesn't regenerate.

**Legendary Resistance (3/Day).** If Belial fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Belial has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Belial makes three attacks using his Ranseur of Torture.

**Ranseur of Torture.** Melee Weapon Attack: +18 to hit, reach 10 ft., one target. *Hit:* 21 (2d10 + 10) piercing damage plus 5 (1d10) necrotic damage, and the target must make a DC 23 Constitution saving throw. On a failed save, the target's movement speed is reduced by 5 feet until the end of their next turn. This penalty can stack.

**Walls of Phlegethos.** Belial creates a wall of fire on a solid surface within 120 feet of him. The wall is 20 feet high and 1 foot thick, and Belial can make the wall up to 60 feet long or create a ringed wall up to 20 feet in diameter. The wall is opaque and lasts until Belial dismisses it. When the wall appears, each creature within its area must make a DC 25 Dexterity saving throw, taking 36 (8d8) fire damage on a failed save, or half as much damage on a successful one. A creature that ends its turn inside the wall, or within 5 feet of it, must repeat the save.

**Symbol of Insanity (Recharge 4–6).** Belial draws a magic symbol at a point he can see within 120 feet of him. All creatures within a 20-foot-radius sphere centered on the symbol must make a DC 25 Intelligence saving throw. Targets take 45 (10d8) psychic damage on a failed save, or half as much damage on a successful one. Creatures that fail the save immediately use their reaction to make a melee attack against a random creature within their reach, then move their full movement in a random direction.


---

### Reactions

**Pleasure in Pain.** As a reaction to taking damage, Belial immediately regenerates half the damage he took.


---

### Legendary Actions

### 

**Ranseur.** Belial makes a Ranseur of Torture attack.

**Eruption (Costs 2 Actions).** Belial causes molten stone to erupt from a point he can see within 90 feet of him. All creatures within a 20-foot-radius sphere centered on that point must make a DC 23 Dexterity saving throw. Targets take 28 (8d6) fire damage on a failed save, or half as much damage on a successful one.

**Call Underling (Costs 3 Actions).** Belial summons an allied horned devil in an unoccupied space that he can see.


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