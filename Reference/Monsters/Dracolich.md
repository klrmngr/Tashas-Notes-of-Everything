---
type: pc
race: "Undead"
class:
 - "Dracolich"
subClass:
 - "CR 17"
cover: "Dracolich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/17
  - source/xmm
---
###### Dracolich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dracolich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 225 (18d12 + 108) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 19 | 15 | 21 |
| **Mod** | +7 | +0 | +6 | +4 | +2 | +5 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 24
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +8
**Skills:** Perception +14, Stealth +6
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dracolich fails a saving throw, it can choose to succeed instead.

**Life Suppression.** Creatures within 60 feet of the dracolich can't regain Hit Points.

**Magic Resistance.** The dracolich has Advantage on saving throws against spells and other magical effects.

**Soul Gem.** The dracolich has a magical gem. If the dracolich is destroyed while the gem is on the same plane of existence as it, the dracolich gains a new body in 1d20 days, regaining all its Hit Points and appearing within 5 feet of the gem.
The gem is a Tiny object that has AC 20; HP 50; and Immunity to Necrotic, Poison, and Psychic damage. The gem regains all its Hit Points at the end of every turn, but it turns to dust if reduced to 0 Hit Points. If the gem is destroyed, the dracolich can create a new one by completing an 8-hour ritual using a gem worth 1,000+ GP and by expending 5,000 GP, which the ritual consumes.


---

### Actions

**Multiattack.** The dracolich makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Ray of Sickness (level 2 version).

**Rend.** m +13, reach 10 ft. *Hit:* 18 (2d10 + 7) Slashing damage plus 4 (1d8) Necrotic damage.

**Necrotic Breath (Recharge 5–6).** con DC 20, each creature in a 60-foot Cone.  52 (8d12) Necrotic damage.  Half damage.


---

### Legendary Actions

### 

**Pounce.** The dracolich moves up to half its Speed, and it makes one Rend attack.

**Sickening Ray.** The dracolich uses Spellcasting to cast Ray of Sickness (level 2 version). The dracolich can't take this action again until the start of its next turn.

**Terrifying Presence.** wis DC 19, each creature in a 30-foot Emanation originating from the dracolich.  11 (2d10) Psychic damage, and the target has the Frightened condition until the end of its next turn.  The dracolich can't take this action again until the start of its next turn.


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