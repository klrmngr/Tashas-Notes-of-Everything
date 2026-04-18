---
type: pc
race: "Monstrosity (titan)"
class:
 - "Thessalkraken"
subClass:
 - "CR 14"
cover: "Thessalkraken.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/14
  - source/imr
---
###### Thessalkraken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Thessalkraken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 11 | 20 | 19 | 15 | 17 |
| **Mod** | +7 | +0 | +5 | +4 | +2 | +3 |

**Speed:** 20 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 12
**Languages:** understands Abyssal, Celestial, Infernal, and Primordial but can't speak, telepathy 120 ft.
**Saving Throws:** Str +12, Dex +5, Con +10, Int +9, Wis +7
**Damage Immunities:** acid; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; paralyzed

---

### Traits

**Amphibious.** The thessalkraken can breathe air and water.

**Freedom of Movement.** The thessalkraken ignores 3, and magical effects can't reduce its speed or cause it to be restrained. It can spend 5 feet of movement to escape from nonmagical restraints or being grappled.


---

### Actions

**Multiattack.** The thessalkraken makes one bite attack and two tentacle attacks. It can replace each tentacle attack with one use of Fling.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) piercing damage plus 5 (1d10) acid damage. If the target is a Medium or smaller creature grappled by the thessalkraken, that creature is swallowed, and the grapple ends. While swallowed, the creature is blinded and restrained, it has 3 against attacks and other effects outside the thessalkraken, and it takes 21 (6d6) acid damage at the start of each of the thessalkraken's turns.
If the thessalkraken takes 35 damage or more on a single turn from a creature inside it, it must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the thessalkraken. If the thessalkraken dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 10 feet of movement, exiting prone.

**Tentacle.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 17 (3d6 + 7) slashing damage, and the target is grappled (escape DC 16). Until this grapple ends, the target is restrained. The thessalkraken has ten tentacles, each of which can grapple one target.

**Fling.** One Medium or smaller object held or creature grappled by the thessalkraken is thrown up to 40 feet in a random direction and knocked prone. If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 16 Dexterity saving throw or take the same damage and be knocked prone.

**Acid Saliva (Recharge 5–6).** The thessalkraken spits a glob of acid at a point it can see within 60 feet of it. Each creature within 10 feet of that point must make a DC 18 Dexterity saving throw, taking 22 (4d10) acid damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tentacle Attack.** The thessalkraken makes one tentacle attack.

**Fling.** The thessalkraken uses Fling.

**Ink Cloud (Costs 3 Actions).** While underwater, the thessalkraken expels an ink cloud in a 60-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than the thessalkraken. Each creature other than the thessalkraken that ends its turn there must succeed on a DC 18 Constitution saving throw, taking 16 (3d10) poison damage on a failed save, or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of the thessalkraken's next turn.


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