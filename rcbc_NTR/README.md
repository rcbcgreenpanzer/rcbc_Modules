# rcbc\_Tweak\_NTR
RCBC's tweaks to vin\_NTR

* vin\_NTR:
  * Scenes:
    * boss\_asks\_impregnate\_cms:
      * Add check that the boss can impregnate and dating can be impregnated.
    * dating\_cheating\_family\_cms:
      * Add logic for open relationship using relative\_asks\_cms
    * dating\_cheating\_family\_shower\_cms:
      * Add logic for open relationship using relative\_asks\_cms
    * dating\_visits\_office\_cms:
      * Split player and dating logic trees so that both can fire
      * Add logic for open relationship using boss\_asks\_cms
    * owned\_ntr\_cms:
      * Replace isFemale() criteria with !isMale()
      * Replace Player.isMale() with !Player.isFemale()
