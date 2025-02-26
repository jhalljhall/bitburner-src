<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Go](./bitburner.go.md) &gt; [resetBoardState](./bitburner.go.resetboardstate.md)

## Go.resetBoardState() method

Gets new IPvGO subnet with the specified size owned by the listed faction, ready for the player to make a move. This will reset your win streak if the current game is not complete and you have already made moves.

Note that some factions will have a few routers on the subnet at this state.

opponent is "Netburners" or "Slum Snakes" or "The Black Hand" or "Daedalus" or "Illuminati",

**Signature:**

```typescript
resetBoardState(opponent: GoOpponent, boardSize: 5 | 7 | 9 | 13): string[] | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  opponent | [GoOpponent](./bitburner.goopponent.md) |  |
|  boardSize | 5 \| 7 \| 9 \| 13 |  |

**Returns:**

string\[\] \| undefined

a simplified version of the board state as an array of strings representing the board columns. See ns.Go.getBoardState() for full details

## Remarks

RAM cost: 0 GB

