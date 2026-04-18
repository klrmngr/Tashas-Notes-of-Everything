---
type: pc
race: "Celestial"
class:
 - "Alyxian the Callous"
subClass:
 - "CR 12"
cover: "Alyxian the Callous.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/12
  - source/crcotn
---
###### Alyxian the Callous
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian the Callous.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 157 (15d10 + 75) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 18 | 21 | 15 | 16 | 20 |
| **Mod** | +6 | +4 | +5 | +2 | +3 | +5 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Celestial, Common, Elvish, telepathy 120 ft.
**Saving Throws:** Str +10, Con +9, Wis +7
**Skills:** Deception +9, Insight +7, Perception +7
**Damage Immunities:** radiant
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; restrained; stunned

---

### Traits

**Apotheonic Rejuvenation.** When Alyxian the Callous drops to 0 hit points, his body dies and sheds its wings, and he rises to his feet in his third form, Alyxian the Dispossessed. His initiative count doesn't change.

**Divinely Blessed.** Alyxian can't be surprised and can't be changed into another form against his will.

**Legendary Resistance (2/Day).** If Alyxian fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Alyxian makes two Radiant Spear attacks. He can replace one of these attacks with Blinding Teleport.

**Radiant Spear.** Melee or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 15 (2d8 + 6) radiant damage.

**Blinding Teleport.** Alyxian teleports, along with any equipment he is wearing or carrying, to an unoccupied space he can see within 120 feet of himself. Each creature within 5 feet of his new location must succeed on a DC 17 Constitution saving throw or be blinded until the end of its next turn.

**Heavenly Destruction (1/Day).** Alyxian releases divine energy in a 60-foot cone. Each creature of his choice in that area must make a DC 17 Constitution saving throw. On a failed saving throw, the creature takes 31 (7d8) radiant damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone.


---

### Legendary Actions

### 

**Attack.** Alyxian makes one Radiant Spear attack.

**Celestial Chains.** Alyxian targets one creature he can see within 120 feet of himself. The target must succeed on a DC 17 Strength saving throw or be restrained by magical chains for 1 minute. While restrained in this way, the target can't leave the space by any means. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Flare (Costs 2 Actions).** Alyxian targets one creature he can see within 30 feet of himself. Light flares around the target, dealing 17 (5d6) radiant damage to it and creatures within 10 feet of it.


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