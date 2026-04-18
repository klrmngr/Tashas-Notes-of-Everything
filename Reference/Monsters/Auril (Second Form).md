---
type: pc
race: "Elemental"
class:
 - "Auril (Second Form)"
subClass:
 - "CR 10"
cover: "Auril (Second Form).png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/10
  - source/idrotf
---
###### Auril (Second Form)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Auril (Second Form).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (13d10 + 65) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 21 | 24 | 26 | 28 |
| **Mod** | +3 | +3 | +5 | +7 | +8 | +9 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 120 ft., passive Perception 26
**Languages:** all, telepathy 1000 ft.
**Saving Throws:** Con +9, Wis +12
**Skills:** Deception +13, Insight +12, Intimidation +13, Perception +16
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Divine Being.** Auril can't be surprised and can't be changed into another form against her will.

**Divine Rejuvenation.** When Auril drops to 0 hit points, her body collapses into shards of ice, whereupon Auril instantly reappears in her third form, in an unoccupied space within 60 feet of where her second form was destroyed. Her initiative count doesn't change.

**Legendary Resistance (2/Day in This Form).** If Auril fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Auril has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** Auril doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Auril attacks twice with her ice morningstar or hurls three ice darts.

**Ice Morningstar.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 9 (2d8) cold damage.

**Ice Dart.** Ranged Weapon Attack: +7 to hit, range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 3 (1d6) cold damage.

**Cone of Cold (Recharges after a Short or Long Rest).** Auril causes a magical blast of cold air to erupt from her hand. Each creature in a 60-foot cone must make a DC 21 Constitution saving throw, taking 36 (8d8) cold damage on a failed save, or half as much damage on a successful one.

**Create Ice Mephit (3/Day).** Auril breaks off an icicle from her body and hurls it into an unoccupied space she can see within 20 feet of her, where it magically transforms into an ice mephit (see its entry in the Monster Manual). The mephit acts immediately after Auril in the initiative order and obeys her commands.

**Ice Stasis (Recharge 5–6).** Auril magically creates a gem-sized ice crystal that hovers in a space within 5 feet of her. Auril then targets a creature she can see within 60 feet of the crystal. The target must succeed on a DC 21 Charisma saving throw or become trapped in the crystal, which is immovable. If the saving throw succeeds, the crystal shatters and nothing else happens. A creature trapped in the crystal is stunned, has 3 against attacks and other effects outside the crystal, and takes 21 (6d6) cold damage at the start of each of its turns. The creature can repeat the saving throw at the end of each of its turns, freeing itself on a success. The creature is also freed if the crystal is destroyed, which is a Tiny object with AC 18, 9 hit points, and immunity to all damage except fire damage. The freed creature appears in an unoccupied space of its choice within 30 feet of the shattered crystal.


---

### Legendary Actions

### 

**Attack.** Auril makes one weapon attack.

**Ice Flurry (Costs 2 Actions).** Each creature within 30 feet of Auril takes 5 (2d4) piercing damage from swirling ice, and nonmagical, open flames in that area are extinguished.

**Splinter (Costs 3 Actions).** Auril uses Create Ice Mephit or causes one to ice mephit she can see within 60 feet of her to explode and die. A mephit that dies in this way does not use its Death Burst. Instead, each creature within 10 feet of the exploding mephit must succeed on a DC 21 Dexterity saving throw, taking 13 (3d8) piercing damage on a failed saving throw, and half as much damage on a successful one.


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