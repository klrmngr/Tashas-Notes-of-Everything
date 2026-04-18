---
type: pc
race: "Beast"
class:
 - "Bhaal, Ravager"
subClass:
 - "CR 24"
cover: "Bhaal, Ravager.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/24
  - source/mabjov
---
###### Bhaal, Ravager
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Bhaal, Ravager.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 351 (26d12 + 182) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 24 | 24 | 14 | 16 | 14 |
| **Mod** | +9 | +7 | +7 | +2 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 60 ft., passive Perception 20
**Languages:** Abyssal, Common, Primordial, Undercommon
**Saving Throws:** Str +16, Dex +14, Cha +9
**Skills:** Athletics +16, Perception +10, Stealth +14
**Damage Resistances:** necrotic
**Damage Immunities:** acid; cold; fire; lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; incapacitated; paralyzed; petrified; poisoned; stunned; unconscious

---

### Traits

**Avatar of Bhaal.** When the ravager drops to 0 hit points, its form fractures. Within the next 24 hours, it will reappear in its [[Bhaal, Slayer|slayer form]] within 2d6 miles of where the ravager form fell.

**Cull the Weak.** When the ravager damages a creature with a melee attack and the target is left with 20 or fewer remaining hit points, the creature must succeed on a DC 21 Constitution saving throw or be reduced to 0 hit points.

**Immutable Form.** The ravager is immune to any spell or effect that would alter its form.

**Legendary Resistance (3/Day).** If the ravager fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The ravager has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The ravager's Claw, Bite, and Spines attacks are magical.

**Spiked Hide.** At the start of each of its turns, the ravager deals 16 (3d10) piercing damage to any creature grappling it or being grappled by it.


---

### Actions

**Multiattack.** The ravager makes one Bite attack and then either two Claw attacks or two Spines attacks.

**Claw.** Melee Weapon Attack: +16 to hit, reach 5 ft., one target. *Hit:* 22 (3d8 + 9) slashing damage plus 7 (2d6) necrotic damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the greater restoration spell or other magic.

**Bite.** Melee Weapon Attack: +16 to hit, reach 5 ft., one target. *Hit:* 25 (3d10 + 9) piercing damage plus 7 (2d6) necrotic damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the greater restoration spell or other magic. Large or smaller creatures damaged by this attack are grappled (escape DC 20) and the ravager can't make another Bite attack until this grapple ends.

**Spines.** Ranged Weapon Attack: +14 to hit, range 60/120 ft., one target. *Hit:* 17 (3d6 + 7) piercing damage. If the target fails a DC 19 Constitution saving throw, they are stunned until the end of their next turn.


---

### Legendary Actions

### 

**Detect.** The ravager makes a Wisdom (Perception) check.

**Spiky Carapace.** The ravager flares its numerous spines and they elongate. Any creature within 5 feet of the ravager must make a DC 21 Dexterity saving throw, taking 27 (5d10) piercing damage on a failed save, or half as much damage on a successful one.

**Smash (Costs 2 Actions).** The ravager smashes downwards with great force, causing a violent implosion. Any creature within 10 feet of the ravager must make a DC 20 Constitution saving throw, taking 18 (4d8) thunder damage on a failed save, or half as much damage on a successful one. Creatures that fail the saving throw are also pulled 5 feet towards the ravager. The noise produced by this attack can be heard up to 1 mile away.


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