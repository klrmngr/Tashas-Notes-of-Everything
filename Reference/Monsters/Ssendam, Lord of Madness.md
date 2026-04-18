---
type: pc
race: "Aberration"
class:
 - "Ssendam, Lord of Madness"
subClass:
 - "CR 23"
cover: "Ssendam, Lord of Madness.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/23
  - source/mabjov
---
###### Ssendam, Lord of Madness
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Ssendam, Lord of Madness.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 299 (26d10 + 156) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 24 | 22 | 20 | 18 | 26 |
| **Mod** | +5 | +7 | +6 | +5 | +4 | +8 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +14, Con +13, Cha +15
**Skills:** Arcana +12, Deception +15, Insight +18, Intimidation +15, Perception +11
**Damage Resistances:** acid; cold; fire; lightning; thunder
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Aura of Madness.** Any creature (other than Undead or Constructs) that ends its turn within 10 feet of Ssendam must succeed on a DC 20 Charisma saving throw or be inflicted with a random short-term madness. If a creature succeeds against any madness ability of Ssendam's, they are immune to Ssendam's madness for 1 hour.

**Legendary Resistance (3/Day).** If Ssendam fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Ssendam has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Ssendam's weapon attacks are magical.

**Regeneration (Golden Amoeba Form Only).** Ssendam regains 40 hit points at the start of her turn if she has at least 1 hit point.


---

### Actions

**Multiattack.** Ssendam makes three attacks: one with her Touch of Madness and two with her Chaos Staff.

**Touch of Madness.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) slashing damage plus 11 (2d10) necrotic damage. A target that fails a DC 20 Charisma saving throw is inflicted with a random short-term madness. If it is already mad, the existing madness is replaced with a random long-term madness.

**Chaos Staff.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage plus 11 (2d10) necrotic damage. The target must succeed on a DC 19 Constitution saving throw or have the stunned condition for 1 minute. The target may repeat the saving throw at the end of each of their turns, ending the effect on a success.

**Summon Slaadi (1/Day).** Ssendam summons 1d4 + 1 [[Death Slaad|death slaadi]]. A summoned slaad appears in an unoccupied space within 60 feet of Ssendam, acts as an ally of Ssendam, and can't summon other slaadi. It remains for 1 minute, until it or Ssendam dies, or until Ssendam dismisses it as an action.

**Teleport.** Ssendam magically teleports, along with any equipment she is wearing or carrying, up to 120 feet to an unoccupied space she can see.


---

### Bonus Actions

**Change Shape.** Ssendam polymorphs into a Small or Medium-sized Humanoid, into a Small Aberration that looks like a golden amoeba, or back into this, her golden slaad form. Any equipment she is wearing or carrying isn't transformed. She reverts to her true form if she dies. Her statistics in the Humanoid forms, other than her size, are the same.
While in her amoeba form, Ssendam also has the same statistics with the following changes. She can't take any actions (except her Change Shape action), speak, or manipulate objects. She has a movement speed of 40 feet and can enter a hostile creature's space and stop there. In addition, Ssendam can move through a space as narrow as 1 inch wide without squeezing. She has advantage on Strength and Dexterity saving throws, and has resistance to all damage except psychic and radiant.


---

### Reactions

**Amoeba.** When damaged, Ssendam uses her reaction to activate Change Shape to transform into her golden amoeba form. Doing this reduces the damage to 0.


---

### Legendary Actions

### 

**Chaos Staff.** Ssendam makes one Chaos Staff attack.

**Teleport.** Ssendam uses her Teleport action.

**Subversion (Costs 2 Actions).** Ssendam forces every creature suffering from madness within 60 feet of her to use their reaction to attack another creature within 5 feet of them.


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