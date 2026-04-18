---
type: pc
race: "Fiend"
class:
 - "Shator Demodand"
subClass:
 - "CR 16"
cover: "Shator Demodand.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/16
  - source/mpp
---
###### Shator Demodand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Shator Demodand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 195 (23d10 + 69) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 15 | 17 | 21 | 16 | 20 |
| **Mod** | +7 | +2 | +3 | +5 | +3 | +5 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** Abyssal, Common, Demodand, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +7, Wis +8
**Skills:** Perception +13, Stealth +7
**Damage Resistances:** cold; fire
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; frightened; paralyzed; poisoned; restrained

---

### Traits

**Boundless Movement.** The shator ignores difficult terrain, and magical effects can't reduce its speed. It can spend 5 feet of movement to automatically remove the grappled condition from itself.

**Jailer (1/Day).** The shator can cast the imprisonment spell, requiring no material components and using Intelligence as the spellcasting ability (chaining effect only; spell save DC 18).

**Liquefaction Ritual.** The shator can perform a 1-minute ritual that turns all willing farastus and kelubars of its choice within 60 feet of itself into a living liquid form. Each liquefied demodand becomes enough liquid to fill a flask. A demodand's liquefaction lasts until a shator uses an action to end it or a creature opens a container holding the liquid. While liquefied in this way, a demodand has the paralyzed condition despite any immunity to that condition, it has immunity to all damage, and any curse affecting it is suspended.

**Magic Resistance.** The shator has advantage on saving throws against spells and other magical effects.

**Numbing Secretions.** A creature that touches the shator or hits it with a melee attack while within 5 feet of it must succeed on a DC 17 Dexterity saving throw or have disadvantage on attack rolls and its speed halved until the end of its next turn.


---

### Actions

**Multiattack.** The shator makes one Bite attack and two Enervating Trident attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 17 (3d6 + 7) piercing damage plus 26 (4d12) acid damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the paralyzed condition until the start of the shator's next turn.

**Enervating Trident.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) necrotic damage.

**Inhibitory Spray (Recharge 5–6).** The shator exhales a spray of slime in a line 100 feet long and 5 feet wide. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 40 (9d8) acid damage and has the paralyzed condition for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.

**Summon Demodand (1/Day).** The shator has a 50 percent chance of summoning its choice of 1d4 farastu demodands, 1d2 kelubar demodands, or 1 shator demodand. A summoned demodand appears in an unoccupied space within 60 feet of the shator, acts as an ally of the shator, and can't summon other demodands. It remains for 1 minute, until it or the shator dies, or until the shator dismisses it as an action.


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