---
type: pc
race: "Fiend"
class:
 - "Kelubar Demodand"
subClass:
 - "CR 13"
cover: "Kelubar Demodand.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/mpp
---
###### Kelubar Demodand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Kelubar Demodand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 187 (22d8 + 88) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 13 | 18 | 14 | 15 | 18 |
| **Mod** | +6 | +1 | +4 | +2 | +2 | +4 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Demodand, telepathy 120 ft.
**Saving Throws:** Dex +6, Wis +7
**Skills:** Insight +7
**Damage Resistances:** cold; fire
**Damage Immunities:** acid; poison
**Condition Immunities:** paralyzed; poisoned; restrained

---

### Traits

**Acidic Secretions.** A creature that touches the kelubar or hits it with a melee attack while within 5 feet of it takes 5 (2d4) acid damage.

**Boundless Movement.** The kelubar ignores difficult terrain, and magical effects can't reduce its speed. It can spend 5 feet of movement to automatically remove the grappled condition from itself.

**Magic Resistance.** The kelubar has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The kelubar makes two Bite attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) piercing damage plus 18 (4d8) acid damage.

**Spit Acid.** The kelubar spits acid in a line 60 feet long and 5 feet wide. Each creature in that area must make a DC 17 Dexterity saving throw, taking 27 (6d8) acid damage on a failed save, or half as much damage on a successful one.

**Summon Demodand (1/Day).** The kelubar has a 40 percent chance of summoning its choice of 1d2 farastu demodands or 1 kelubar demodand. A summoned demodand appears in an unoccupied space within 60 feet of the kelubar, acts as an ally of the kelubar, and can't summon other demodands. It remains for 1 minute, until it or the kelubar dies, or until the kelubar dismisses it as an action.


---

### Bonus Actions

**Nauseating Fog (Recharge 6).** The kelubar magically creates a cloud of greenish fog that fills a 20-foot-radius sphere centered on a point within 120 feet of itself. The cloud remains for 1 minute or until the kelubar uses this bonus action again. The cloud is heavily obscured and difficult terrain. Any creature that starts its turn in the cloud or enters the cloud for the first time on a turn must succeed on a DC 17 Constitution saving throw or have the poisoned condition until the end of its next turn.


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