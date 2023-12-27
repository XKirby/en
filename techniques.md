---
layout: default
title: Techniques
permalink: /techniques
nav_order: 15
---

# Techniques
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Techniques are the myriad ways a character acts in combat, most often by attacking.

By default, all Techniques start from the same template:

{: .specie-inner-callout }
> *Basic Attack*{: .header-font } (*0 FP*{: .spirit-color })  
*Coordination*{: .heart-color }:  
Auto: [Power] DMG  
*Nice!*{: .nice-color }: [2 x Power] DMG  
*(No Traits)*{: .italic }
>

Techniques require the user to pass a Primary Check in order to deal damage, which defaults to their *Coordination*{: .heart-color }. The results vary depending on their overall success.

As in the above example, Techniques can still function with no Grades of Success, but improve with better results – though this threshold for success can be increased, making it harder to hit the minimum and maximum results.

If a Technique doesn't earn enough Grades to achieve any result, though, it fails outright!

## Damage Calculation

Whenever a Primary Check would deal damage as part of a Strike, each Strike is modified by the user's Attack to get the Raw Damage.  
Then, that damage value is reduced by the defender's Defense and any applicable Resistances they have, and that amount of damage is taken from the target's *HP*{: .heart-color }.

Importantly, your Attack can be negative too! In this case, the Attack value is taken out of the Raw Damage, and may reduce it right down to 0!

## Strikes

A Technique can divide its potential damage up into any number of strikes.

- *Single-Strike*{: .italic }  
    Single-Strike attacks can hit one target solidly, dealing [Power] in DMG at a minimum, or [2 x Power] with an additional Grade of Success.  
    Single-Strike attacks hit with more force up-front; as long as they score that additional Grade of Success, and the overall attack would only damage one target, they treat the user's positive Attack modifiers as doubled, and always treat their base damage before Attack as at least 1 (regardless of the user's Power).  
    While Single-Strike attacks can be made to hit additional targets with Traits like *Burst*{: .spirit-color } or *Strike-Through*{: .spirit-color }, this gives up some of the raw power.
- *Multi-Strike*{: .italic }  
    Multi-Strike attacks split some of the force up between their hits, dealing a portion of the attack's damage potential with each hit; as a general rule, each strike should deal no more than [Power] in damage.  
    They strike once if successful, then can make one more strike for each additional Grade of Success earned, but the total base damage of the split strikes can't be more than [2 x Power].

Taking damage at any point during an attack (such as from a Contact Trait) interrupts and cancels the Technique, but doesn't prevent the strike's damage.

![](assets/images/scenes/04.png)
{: .center-img }

{: .tip-callout }
> *Multi-Strike attacks take a bit more work than Single-Strike attacks, but the more strikes you make, the more damage you can get from Attack boosts! ![](assets/images/icons/tipguy.png)*{: .icon-right }

## Technique Traits

When defining your Techniques you have a wide variety of Traits to modify them with, which either increase or decrease the Technique's final *FP*{: .spirit-color } cost. If this reduces your *FP*{: .spirit-color } cost to 0 or less, the Technique doesn't cost any *FP*{: .spirit-color }.

Your Species' Tech Defaults are especially useful here – you can add on one of your Tech Default sets without modifying the *FP*{: .spirit-color } cost at all!  
Any Optional Tech Defaults which would apply can be added on as well without *FP*{: .spirit-color }.  
Required Tech Defaults *must*{: .underlined } be added where they would apply, and don't modify *FP*{: .spirit-color }.

Generally you can only take a Trait once, with different forms of the Trait (e.g. different elements) counting as separate distinct Traits.  
While you can stack as many Traits on a Technique as you please, there are limits to how much *FP*{: .spirit-color } you can save with negative Traits. You can only save *FP*{: .spirit-color } from a number of Traits equal to your level.  
Any other negative Traits you add contribute to the overall Technique's effect, but don't modify *FP*{: .spirit-color } at all.

{: .example-callout}
> *Example: Negative Traits*{: .header-font }
>
> A level 1 Buzzy Beetle wants to begin play with a powerful *0 FP*{: .spirit-color } attack.
> They could add Strong for *2 FP*{: .spirit-color }, and offset it with Unwieldy, for a powerful – but inaccurate – melee attack.
> They could add more negative Traits, but since they can only save *FP*{: .spirit-color } from one Trait at a time, they decide to leave it there to start with.

While you can describe a Technique in shorthand by referring to its Traits, in practice it's better to write out the full effect for your own reference – you may not always remember that a Piercing attack ignores Defense, or you may need to record how your Boost Technique works at different Grades of Success.

While the mechanics of building a Technique can be complicated, it's best to work within this system until you have a good idea of how Techniques work and what effects should cost.

If you find that you just can't make the Technique of your dreams, or your Technique isn't as effective as it should be, try discussing alternatives with your GM. You should consider this system to be a starting point for your own exciting ideas!

## Trait Effects

Some Traits have similar functions which are referred to in shorthand, explained here.

## [X]
{: .no_toc }

This Trait can be chosen multiple times to strengthen its effects; additional instances are treated as the same singular Trait, but with effects varying based on how many times the Trait has been taken, [X].  
If there's a limit on how many times it can be taken, this is referred to as the Cap.  
Note that multiple instances of these values are added together, not multiplied. If [X] is 3, then [XX] would be 6 (3 + 3), and [XXXX] would be 12 (3 + 3 + 3 + 3).

## [Secondary]
{: .no_toc }

After the Primary Check is resolved, as long as it didn't fail and there's still a valid target, some Techniques have follow-up effects which require a Secondary Check. The Skill required for this is defined by the Trait it's acquired from – if the Trait lists multiple Skills, choose one of them when you first define the Technique, and if the Technique has multiple [Secondary] Traits, choose one skill to represent all Secondary effects.  
In any case, you only roll one Secondary Check for all relevant effects. If multiple targets would be affected, they all suffer the consequences of the same Secondary Check.

## [Approach]
{: .no_toc }

This Trait modifies the way the user approaches their target(s). Generally, multiple [Approach] Traits can't be taken at once.

## [Target]
{: .no_toc }

This Trait modifies the available targets for this Technique in some way. Generally, multiple [Target] Traits can't be taken at once.

## [Strikes]
{: .no_toc }

This Trait modifies the way Strikes and damage are allocated in some way, making it fundamentally different from a Single-Strike or Multi-Strike Technique.  
Generally, multiple Strikes Traits can't be taken at once.

## [Random]
{: .no_toc }

This Trait features a random element. Multiple [Random] Traits can't be taken 
at once, unless otherwise specified.

## Positive Technique Traits

WIP