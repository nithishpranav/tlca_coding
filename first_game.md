# My First Arcade Game

## Step 1: Create a Sprite

```blocks
let player = sprites.create(img`
    . . . . . . f f f f . . . . . .
    . . . . f f e e e e f f . . . .
    . . f f e e e e e e e e f f . .
`, SpriteKind.Player)
```

## Step 2: Move the Sprite

```blocks
controller.moveSprite(player)
```

## Step 3: Stay on Screen

```blocks
player.setStayInScreen(true)
```

