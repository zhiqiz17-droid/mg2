# minigame 2
## Devlog
Write your Devlog here.
1
I encountered an issue involving an "if" statement. Because the health value changed before the conditional check, the color didn't update in the correct order, and the treasure chest disappeared prematurely. I resolved this by checking the updated health value and adjusting the color accordingly; I also ensured that the chest only disappears when the health drops to zero.

2
I think that the dot operator "." is used to access an object's properties. For instance, "_spriteRenderer.color" accesses the color property of the "SpriteRenderer". I think the "new" keyword creates a new "Color" object using the values ​​inside the parentheses, where "r", "0.2f", and "0.2f" likely represent the red, green, and blue (RGB) color components, respectively.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
