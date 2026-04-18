---
type: pc
race: "Elemental"
class:
 - "Salamander Inferno Master"
subClass:
 - "CR 15"
cover: "Salamander Inferno Master.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/15
  - source/xmm
---
###### Salamander Inferno Master
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Salamander Inferno Master.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 256 (27d10 + 108) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 16 | 18 | 14 | 10 | 20 |
| **Mod** | +7 | +3 | +4 | +2 | +0 | +5 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 10
**Languages:** Primordial (Ignan)
**Saving Throws:** Dex +8, Wis +5
**Damage Vulnerabilities:** cold
**Damage Immunities:** fire

---

### Traits

**Fire Aura.** At the end of each of the salamander's turns, each creature of the salamander's choice in a 10-foot Emanation originating from the salamander takes 10 (3d6) Fire damage.

**Magic Resistance.** The salamander has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The salamander makes two Flame Trident attacks.

**Flame Trident.** m,r +12, reach 5 ft. or range 30/90 ft. *Hit:* 16 (2d8 + 7) Piercing damage plus 14 (4d6) Fire damage. The trident magically returns to the salamander's hand immediately after a ranged attack.

**Inferno Blast (Recharge 5–6).** dex DC 18, each creature in a 30-foot-radius Sphere centered on a point the salamander can see within 120 feet.  35 (10d6) Fire damage, and the target starts burning, taking 5 (1d10) Fire damage at the start of each of its turns instead of the normal burning damage. The target gains 1 Exhaustion level whenever it takes this burning damage.  Half damage only.


---

### Bonus Actions

**Blazing Movement.** The salamander moves up to its Speed without provoking Opportunity Attacks. During this movement, fire fills a 5-foot Emanation originating from the salamander. When the Emanation enters a creature's space, that creature takes 7 (2d6) Fire damage. A creature can take this damage only once per turn.


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