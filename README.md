# MG3
## Devlog
1) Floats and ints are both values of 0, bools are "false", and strings are empty as in null.
2) I'm pretty sure it's automatically called when by Unity as stated in the prelearning slides.
3) When the player kicks, ActivateKick() sets the timer and uses _lifeTimer.IsFinished in its Update() method to check if the timer is over, if true then the weapon/kick is turned off with gameObject.SetActive(false). Thus, Kickweapon uses the timer to know if the player is attacking.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)