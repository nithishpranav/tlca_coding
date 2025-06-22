# My First Arcade Game

## Step 1: Create a Sprite

Let's start by creating a player sprite.

```blocks
let player = sprites.create(img`
    . . . . . . f f f f . . . . . .
    . . . . f f e e e e f f . . . .
    . . f f e e e e e e e e f f . .
    . f e e e f f f f f f e e e f .
    . f f f f f e e e e f f f f f .
    f f e e f b f 4 4 f b f e e f f
`, SpriteKind.Player)
controller.moveSprite(player)
player.setStayInScreen(true)

