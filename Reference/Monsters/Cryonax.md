---
type: pc
race: "Elemental"
class:
 - "Cryonax"
subClass:
 - "CR 22"
cover: "Cryonax.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/22
  - source/mabjov
---
###### Cryonax
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Cryonax.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 391 (27d12 + 216) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 16 | 26 | 19 | 19 | 23 |
| **Mod** | +8 | +3 | +8 | +4 | +4 | +6 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 14
**Languages:** Common, Primordial
**Saving Throws:** Str +15, Dex +10, Con +15, Wis +11
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Cold Aura.** At the start of each of Cryonax's turns, each creature within 10 feet of him takes 21 (6d6) cold damage. A creature also takes 21 (6d6) cold damage if they touch or hit Cryonax. Nonmagical weapons that hit Cryonax are frozen immediately after dealing damage to Cryonax. If used again and they hit any creature, the weapon shatters. The freezing effect disappears after an hour.

**Empowered Attacks.** Cryonax's Slam attacks are treated as magical for the purpose of bypassing resistance and immunity to nonmagical weapons.

**Ice Walker.** No ability checks are required when Cryonax walks or climbs across icy surfaces and difficult snow or ice terrain does not cost him extra movement.

**Legendary Resistance (3/Day).** If Cryonax fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Cryonax has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Cryonax makes two Slam attacks with his tentacles or two Ice Spear attacks.

**Slam.** Melee Weapon Attack: +15 to hit, reach 15 ft., one target. *Hit:* 27 (3d12 + 8) bludgeoning damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 20). Cryonax can grapple up to two targets but any tentacle that is grappling can't be used to make a Slam or Ice Spear attack.

**Ice Spear.** Ranged Weapon Attack: +10 to hit, range 120 ft., one target. *Hit:* 36 (6d10 + 3) cold damage.

**Summon Frost Horde (1/Day).** Cryonax summons two [[Young White Dragon|young white dragons]] or a [[Frost Giant]] with two [[Yeti|yetis]]. The summoning costs Cryonax 50 hit points. The summoned creatures have maximum hit points and appear within 100 feet of Cryonax.


---

### Legendary Actions

### 

**Smash.** Cryonax slams a grappled target against the ground, dealing 13 (3d8) bludgeoning damage to it.

**Tentacle Freeze.** Cryonax's tentacle freezes a grappled target. If the target fails a DC 22 Constitution saving throw they are paralyzed and Cryonax releases them from its tentacle. They remain frozen indefinitely but can attempt the Constitution saving throw at the end of each of their turns. Success means they are no longer frozen.

**Ice Shroud (Costs 3 Actions).** With a gesture Cryonax targets a frozen creature (see Tentacle Freeze) that is within 30 feet of him. The target is encased instantly in a hard shell of crushing ice. The target receives no saving throw and takes 22 (5d8) cold damage immediately and at the start of each of their turns. The target is considered stunned but is partly protected by the shroud and resistant to all damage. The shroud disappears if Cryonax removes it, Cryonax dies, the shroud takes 100 hit points of damage or another character uses their action and succeeds on a DC 22 Strength check to remove the trapped ally.


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