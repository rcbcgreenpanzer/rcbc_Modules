# rcbc\_Pregnancy
RCBC's edits to vin\_Pregnancy

## Changelog 4.02.1:
* look\_like\_you:
  * Remove whitespace from whitespace-only lines
* NPC\_gives\_birth:
  * Fix wrong actor calling setRelativeType().
* NPC\_gives\_birth\_neutral:
  * Reorder logic to prioritize blood relations over step-.

## Contents:
* breeding\_party\_cms:
  * Remove sb\_Better\_Pregnancy dependency
  * Adjust verbiage to reflect the aim to get the player pregnant.
  * Expand guest conditions to allow trans characters.
  * Add one's companion as a potential partner.
* breeding\_party\_companion\_cms:
  * Remove sb\_Better\_Pregnancy dependency
  * Consolidate conditions so only one call to Random() is made
  * Add more stats to the mix
  * Expand guest conditions to allow trans characters.
* dildo\_impregnate\_cms:
  * Prevent scene from firing is actor is already pregnant.
  * Add shorter timeout when you choose to participate.
* double\_breeding:
  * Expand guest conditions to allow trans characters.
* ex\_pregnancy\_plot:
  * Rework trigger logic to make sure that at least one participant can get
    the other prregnant.
* go\_last\_cms:
  * Replace Player.isMale() with !Player.isFemale()
  * Expand guest conditions to allow trans characters.
* lesbian\_sperm\_donor:
  * Expand guest conditions to allow trans characters.
  * Change scene to support lesbian couples with one member already pregnant.
  * Add option to both get impregnated (if neither was pregnant before)
* lesbian\_sperm:
  * Expand guest conditions to allow trans characters.
  * Add option to both get impregnated
* look\_like\_you\_cms:
  * Replace Actor.isFemale() with !Actor.isMale()
  * Replace Player.isMale() with !Player.isFemale()
* make\_baby:
  * Add options to "This isn't working" to follow up with various other
    scenes.
* NPC\_discovers\_pregnancy:
  * Prevent spouse from making a fuss if they're in a poly
* NPC\_gives\_birth:
  * They're still a relative, even if they're growing up in another family
* NPC\_gives\_birth\_neutral:
  * Rename actors to prevent confusion
  * Father shows up
  * Kid will be a relative if either parent is either a relative or a spouse
  * Currently implemented:
    * Sibling (either parent is also your parent)
    * Stepchild (either parent is dating you)
    * Stepsibling (either parent is your stepparent)
    * ParentSibling (either parent is your grandparent)
    * Cousin (either parent is your parentsibling)
    * Cousin (default catchall)
* player\_gives\_birth:
  * Rename variables to keep who is who straight
  * Add both the real father and fake father if they are different.
* pregnancy\_arousal:
  * Change the criteria from the one who impregnated you to who you're dating
* pregnancy\_doctor:
  * Expand guest conditions to allow trans characters.
* pregnancy\_energy:
  * Change the criteria from the one who impregnated you to who you're dating
* pregnancy\_mood:
  * Change the criteria from the one who impregnated you to who you're dating
* pregnancy\_pact:
  * Expand guest conditions to allow trans characters.
* propose\_baby:
  * Change logic for extra non-cishet energy.
* surrogate:
  * Expand guest conditions to allow trans characters.
