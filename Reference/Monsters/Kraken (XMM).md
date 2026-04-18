---
type: pc
race: "Monstrosity (titan)"
class:
 - "Kraken"
subClass:
 - "CR 23"
cover: "Kraken.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/23
  - source/xmm
---
###### Kraken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Kraken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 481 (26d20 + 208) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 26 | 22 | 18 | 20 |
| **Mod** | +10 | +0 | +8 | +6 | +4 | +5 |

**Speed:** 30 ft., swim 120 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 21
**Languages:** understands Abyssal, Celestial, Infernal, and Primordial but can't speak; telepathy 120 ft.
**Saving Throws:** Str +17, Dex +7, Con +15, Wis +11
**Skills:** History +13, Perception +11
**Damage Immunities:** cold; lightning
**Condition Immunities:** frightened; grappled; paralyzed; restrained

---

### Traits

**Amphibious.** The kraken can breathe air and water.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the kraken fails a saving throw, it can choose to succeed instead.

**Siege Monster.** The kraken deals double damage to objects and structures.


---

### Actions

**Multiattack.** The kraken makes two Tentacle attacks and uses Fling, Lightning Strike, or Swallow.

**Tentacle.** m +17, reach 30 ft. *Hit:* 24 (4d6 + 10) Bludgeoning damage. The target has the Grappled condition (escape DC 20) from one of ten tentacles, and it has the Restrained condition until the grapple ends.

**Fling.** The kraken throws a Large or smaller creature Grappled by it to a space it can see within 60 feet of itself that isn't in the air. dex DC 25, the creature thrown and each creature in the destination space.  18 (4d8) Bludgeoning damage, and the target has the Prone condition.  Half damage only.

**Lightning Strike.** dex DC 23, one creature the kraken can see within 120 feet.  33 (6d10) Lightning damage.  Half damage.

**Swallow.** dex DC 25, one creature Grappled by the kraken (it can have up to four creatures swallowed at a time).  23 (3d8 + 10) Piercing damage. If the target is Large or smaller, it is swallowed and no longer Grappled. A swallowed creature has the Restrained condition, has Total Cover against attacks and other effects outside the kraken, and takes 24 (7d6) Acid damage at the start of each of its turns.
If the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the kraken with the Prone condition. If the kraken dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 15 feet of movement, exiting Prone.


---

### Legendary Actions

### 

**Storm Bolt.** The kraken uses Lightning Strike.

**Toxic Ink.** con DC 23, each creature in a 15-foot Emanation originating from the kraken while it is underwater.  The target has the Blinded and Poisoned conditions until the end of the kraken's next turn. The kraken then moves up to its Speed.  The kraken can't take this action again until the start of its next turn.


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