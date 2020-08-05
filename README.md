# Decentraland Awesome Repository

Welcome to the Decentraland Awesome repository!

<img src="screenshots/shades.png" width="150">

Here you can find content to help you build scenes for Decentraland. Here you'll find links to:

- [Examples](#Examples)
- [Tutorials](#Tutorials)
- [FAQs](#FAQs)

If you can think of an example that is easy to understand and covers valuable topics that aren't covered here, you're encouraged to create a **Pull Request** and [contribute](https://github.com/decentraland-scenes/Awesome-Repository/blob/master/CONTRIBUTING.md)!

If something doesn’t work, please [file an issue](https://github.com/decentraland-scenes/Awesome-Repository/issues/new).

<!--
## FAQs

[Read the FAQs](https://github.com/decentraland-scenes/Awesome-Repository/blob/master/FAQ.md)

Check the Forum
Visit the Discord channel

-->

## Key Concepts

| Article                                                                                                             | Thumbnail                                           | Description                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [SDK functionality to a Builder scene](https://decentraland.org/blog/tutorials/adding-functionality-builder-scene/) | <img src="screenshots/builder.jpg" width="200">     | Take an exported Builder scene and understand how to edit its code to add more functionality.                                    |
| [Introduction to Entities, Components & Systems](https://decentraland.org/blog/tutorials/intro-to-sdk-v5/)          | <img src="screenshots/hypnowheels.png" width="200"> | A walkthrough that starts from scratch and covers most of the main ideas to understand: Entities, Components, Systems, and more. |
| [Motion & Animations - Part 1](https://decentraland.org/blog/tutorials/motion-animations-in-SDK-5/)                 | <img src="screenshots/gnark1.gif" width="200">      | A walkthrough that covers animating an entity and making it move to follow a path.                                               |
| [Motion & Animations - Part 2](https://decentraland.org/blog/tutorials/motion-animations-in-SDK-5-part-2/)          | <img src="screenshots/gnark.gif" width="200">       | Building up on the previous part, this part covers alternating animations, and responding to the player's proximity.             |

For a fully comprehensive introduction, we also recommend you read the following topics from the Documentation:

- [Entities & Components](https://docs.decentraland.org/development-guide/entities-components/)
- [Systems](https://docs.decentraland.org/development-guide/systems/)
- [Custom Components](https://docs.decentraland.org/development-guide/custom-components/)
- [Component Groups](https://docs.decentraland.org/development-guide/component-groups/)
- [Files in a Scene](https://docs.decentraland.org/development-guide/scene-files/)

See the [Decentraland documentation](docs.decentraland.org) to find more specific information about various other.

## Examples

### Essentials

| Example                                                                           | Thumbnail                                                  | Description                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Sliding Door](https://github.com/decentraland-scenes/Sliding-door)               | <img src="screenshots/sliding-door.png" width="200">       | Use the Utils library to shift the position of a door gradually. Clicks on the door toggle it from open to closed.                                                                                                                                  |
| [Door](https://github.com/decentraland-scenes/Open-door)                          | <img src="screenshots/door.png" width="200">               | Use the Utils library to rotate a door gradually. Clicks on the door toggle it from open to closed.                                                                                                                                                 |
| [Puffer](https://github.com/decentraland-scenes/Puffer)                           | <img src="screenshots/puffer.png" width="200">             | Use the Utils library to scale items and delay actions. Also include 3D models and sounds.                                                                                                                                                          |
| [Button button events](https://github.com/decentraland-scenes/Basic-Interactions) | <img src="screenshots/basic-interactions.png" width="200"> | A simple example of each way in which players can use button events to interact with the scene. Each shape's color is activated by interacting with it in a special way.                                                                            |
| [Jukebox](https://github.com/decentraland-scenes/Jukebox)                         | <img src="screenshots/jukebox.png" width="200">            | Play different songs by pressing buttons on a jukebox.                                                                                                                                                                                              |
| [Hypno Wheels](https://github.com/decentraland-scenes/Hypno-wheels)               | <img src="screenshots/hypnowheels.png" width="200">        | A first encounter with Systems, Custom Components and Component Groups. Check out the [related tutorial](https://decentraland.org/blog/tutorials/intro-to-sdk-v5/).)                                                                                |
| [Shark Animation](https://github.com/decentraland-scenes/Shark-animation)         | <img src="screenshots/shark-animation.png" width="200">    | Control animations on a 3D model. Toggle them on or off when clicking on the model.                                                                                                                                                                 |
| [Gnark Patrolling](https://github.com/decentraland-scenes/Gnark-patrol)           | <img src="screenshots/gnark.gif" width="200">              | A character walks along a fixed path, using lerp over each segment of the path. If you approach it, it will switch states to yelling at you. Check out the [related tutorial](https://decentraland.org/blog/tutorials/motion-animations-in-SDK-5/). |
| [Hummingbirds](https://github.com/decentraland-scenes/)                           | <img src="screenshots/hummingbirds.png" width="200">       | A new bird spawns every time you click a tree. Each bird moves on its own to random positions.                                                                                                                                                      |
| [Smoke](https://github.com/decentraland-scenes/Smoke)                             | <img src="screenshots/smoke.png" width="200">              | Use planes to create a particle system that simulates smoke rising.                                                                                                                                                                                 |
| [Dance Floor](https://github.com/decentraland-scenes/Dance-floor)                 | <img src="screenshots/dancefloor.png" width="200">         | Combines animations, sound, and tiles on the floor that randomly change color to the beat.                                                                                                                                                          |
| [Laser-Ray Casting](https://github.com/decentraland-scenes/Laser-ray-casting)     | <img src="screenshots/laser.png" width="200">              | Use ray casting to trace a line in space and check for intersections. Cubes change material when hit by the laser. They also change when being pointed at by the player.                                                                            |
| [UV Map](https://github.com/decentraland-scenes/uv-map)                           | <img src="screenshots/uv.gif" width="200">                 | Use ray casting to trace a line in space and check for intersections. Cubes change material when hit by the laser. They also change when being pointed at by the player.                                                                            |
| [Swimming in Circles](https://github.com/decentraland-scenes/Swimming-shark)      | <img src="screenshots/shark-swimming.png" width="200">     | Move a shark along the segments of a curve to swim in circles.                                                                                                                                                                                      |
| [Block Dog](https://github.com/decentraland-scenes/Block-dog)                     | <img src="screenshots/blockdog.png" width="200">           | A simple AI character that randomly chooses what action to take: follow you, sit or remain idle. Tell it to sit or stand up by clicking it, or tell it to drink water by clicking its bowl.                                                         |

#### Game mechanics

| Example                                                                              | Thumbnail                                              | Description                                                                                                                                |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [Coin Pickup](https://github.com/decentraland-scenes/coin-pickup)                    | <img src="screenshots/coin-pickup.gif" width="200">    | Coins that are picked up when players walk over them.                                                                                      |
| [Item Pickup](https://github.com/decentraland-scenes/item-pickup)                    | <img src="screenshots/item-pickup.gif" width="200">    | Various items like health packs and ammo that are picked up when players walk over them.                                                   |
| [Grab Objects basic](https://github.com/decentraland-scenes/grab-objects-basic)      |                                                        | Click an item to hold it and drop it somewhere else in the scene.                                                                          |
| [Grab Objects Advanced](https://github.com/decentraland-scenes/grab-objects-advance) |                                                        | Click an item to hold it in the air and carry it or toss it around the scene using physics.                                                |
| [Shooting Range](https://github.com/decentraland-scenes/shooting-range)              | <img src="screenshots/shooting-range.gif" width="200"> | Shoot at moving targets. Bullet holes appear in the spots where shots hit.                                                                 |
| [NPC Dialog](https://github.com/decentraland-scenes/npc-dialog-example-scene)        | <img src="screenshots/npc-dialog.gif" width="200">     | A UI window presents texts from an NPC, allowing you to use the Right Click, E and F keys to advance the conversation or answer questions. |

#### Physics

| Example                                                                             | Thumbnail                                          | Description                                                                                     |
| ----------------------------------------------------------------------------------- | -------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| [Bouncing Balls](https://github.com/decentraland-scenes/cannon-example-scene)       | <img src="screenshots/balls.gif" width="200">      | Kick balls around and make them bounce off each other, using the cannon.js library for physics. |
| [Car + Physics](https://github.com/decentraland-scenes/cannon-car-example-scene)    | <img src="screenshots/cannon-car.gif" width="200"> | Drive a car through piles of boxes and see them tumble down, using cannon.js for physics.       |
| [2D Bouncing Ball](https://github.com/decentraland-scenes/box2d-ball-example-scene) |                                                    | A bouncing ball using the box2d physics library to simulate physics on a 2D space.              |

### Monetization & Blockchain

| Example                                                                    | Thumbnail                                             | Description                                                                                                     |
| -------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| [Donation Box](https://github.com/decentraland-scenes/Donations-Box)       | <img src="screenshots/donations.png" width="200">     | Request MANA donations to a wallet.                                                                             |
| [Paid Button](https://github.com/decentraland-scenes/Paid-Button)          | <img src="screenshots/paid-button.png" width="200">   | Add a button that is only activated by paying a MANA sum to a specified address.                                |
| [Paid Lever](https://github.com/decentraland-scenes/Paid-Lever)            | <img src="screenshots/paid-lever.png" width="200">    | Add a lever that only switches state by paying a MANA sum to a specified address.                               |
| [Simple NFT](https://github.com/decentraland-scenes/Certified-criptokitty) | <img src="screenshots/kitty.png" width="200">         | Display a 2D NFT in a picture frame.                                                                            |
| [NFT Wall](https://github.com/decentraland-scenes/nft-wall-example-scene)  | <img src="screenshots/nft-swap-wall.gif" width="200"> | Display a collection of 2D NFTs in picture frames, these swap every few seconds, taking data from a JSON file.  |
| [MANA Burning](https://github.com/decentraland-scenes/MANA-Burning-Altar)  | <img src="screenshots/mana-altar.png" width="200">    | Interact with the MANA contract to burn MANA fees collected over time by the Market place in a ceremonious way. |
| [POAP Booth](https://github.com/decentraland-scenes/POAP-Booth)            | <img src="screenshots/POAP.png" width="200">          | Interact with the [POAP](https://www.poap.xyz/) contract to mint a POAP token when clicking on a booth.         |

### Multiplayer & APIs

#### Hit an API

| Example                                                                         | Thumbnail                                          | Description                                                                                                                                           |
| ------------------------------------------------------------------------------- | -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Party Time](https://github.com/decentraland-scenes/Party-Time)                 | <img src="screenshots/party-time.png" width="200"> | Hit a world clock API to check the time, start a party if it's after 9PM.                                                                             |
| [Events API](https://github.com/decentraland-scenes/Events-API)                 | <img src="screenshots/events.png" width="200">     | Query the Decentraland Events API for any events that are currently active to display their info. If more than one, flip through them on the display. |
| [Wearables Scanner](https://github.com/decentraland-scenes/wearables-scanner)   | <img src="screenshots/scanner.gif" width="200">    | Fetch the list of wearables that a player currently has on. If they have something in the eyewear category, open the door for them.                   |
| [Weather Simulation](https://github.com/decentraland-scenes/Weather-simulation) | <img src="screenshots/weather.png" width="200">    | Check a weather API, then represent the weather conditions, whatever they are.                                                                        |

#### Use message bus

| Example                                                                         | Thumbnail                                           | Description                                                                                                                                   |
| ------------------------------------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| [Block Fountain](https://github.com/decentraland-scenes/Block-Fountain)         | <img src="screenshots/fountain.png" width="200">    | The cubes in this fountain have several animations that each set can play. When a player pushes a button, all players see the same animation. |
| [Piano Floor](https://github.com/decentraland-scenes/piano-floor-example-scene) | <img src="screenshots/piano-floor.gif" width="200"> | Play the keys of this piano by stepping on them. All players will hear the notes that are played.                                             |

#### Use an API as DB

| Example                                                                          | Thumbnail                                           | Description                                                                                                                           |
| -------------------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| [Leader Board](https://github.com/decentraland-scenes/Leader-Board)              | <img src="screenshots/leaderboard.png" width="200"> | Upload player's final scores to a server, the best ones are displayed for all to see on a board.                                      |
| [Guest Book API](ttps://github.com/decentraland-scenes/Guest-Book-API)           | <img src="screenshots/guestbook.png" width="200">   | Players that sign this guest-book upload their user name and address to the server. All signatures are fetched when opening the book. |
| [Pixel Mural](https://github.com/decentraland-scenes/mural-example-scene)        | <img src="screenshots/mural.png" width="200">       | Create 2D pixel art by painting tiles. Players are synced through both the messagebus and a DB in a server.                           |
| [3D Voxel Art Creator](https://github.com/decentraland-scenes/voxel-art-creator) | <img src="screenshots/voxel.png" width="200">       | Create 3D voxel art by placing cubes in place. Players are synced through both the messagebus and a DB in a server.                   |
| [Zenquencer](https://github.com/decentraland-scenes/Zenquencer)                  | <img src="screenshots/zenquencer.gif" width="200">  | Create musical patterns that are played in sequence. Players are synced through both the messagebus and a DB in a server.             |

#### WebSockets

| Example                                                                       | Thumbnail                                            | Description                                                                                                                                                                           |
| ----------------------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Broadcast Server](https://github.com/decentraland-scenes/ws-broadcast)       | (server code only)                                   | A basic server that broadcasts all messages it receives to all other players in a room.                                                                                               |
| [Color Switch](https://github.com/decentraland-scenes/ws-example)             | <img src="screenshots/ws-basic.png" width="200">     | A minimal scene where clicking on cubes changes their color. The broadcast server syncs these changes to all other players in the same realm.                                         |
| [Land Flipper Game](https://github.com/decentraland-scenes/Land-Flipper-Game) | <img src="screenshots/land-flipper.gif" width="200"> | A team game for 2 players or more, where tiles switch colors when walked on. The server keeps track of the game's state, and has the final word about when the game ends and who won. |
| [Discord Chat](https://github.com/decentraland-scenes/discordWebsocket) | | Display messages being posted to Decentraland discord server in real time inside the world |

### Full scenes

| Example                                                                                 | Thumbnail                                       | Description                                                                                                                                                                          |
| --------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Escape Room Tutorial](https://github.com/decentraland-scenes/dcl-escape-room-tutorial) |                                                 | An escape room full of puzzles to solve. A [video tutorial series](https://hardlydifficult.github.io/dcl-escape-room-tutorial/) covers how to make it, starting from the essentials. |
| [Genesis Plaza](https://github.com/decentraland-scenes/Genesis-Plaza)                   | <img src="screenshots/genesis.jpg" width="200"> | The full code used in Genesis Plaza (0,0), including all the interactive elements found there.                                                                                       |
| [Soho Plaza](https://github.com/decentraland-scenes/Soho-Plaza)                         | <img src="screenshots/soho.png" width="200">    | The full code used in Soho Plaza (-75,0), including all the interactive elements found there.                                                                                        |
| [Castaway 2048](https://github.com/decentraland-scenes/Castaway-2048)                   | <img src="screenshots/2048.png" width="200">    | A puzzle game based on 2048, where you merge similar gems into valuable ones, till you reach the value of 2048.                                                                      |

<!--

### NO GO

... let's debate if we want any of these:



https://github.com/decentraland-scenes/Mining-rocks

https://github.com/decentraland-scenes/Tower-defense

https://github.com/decentraland-scenes/Remote-mural

https://github.com/decentraland-scenes/Remote-door

https://github.com/decentraland-scenes/MANA-Transaction

https://github.com/decentraland-scenes/the-munastery

|[Memory Game](https://github.com/decentraland-scenes/Memory-game)|
-->

## Libraries

| Article                                                           | Description                                                                                                                                                               |
| ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ECS Utils](https://www.npmjs.com/package/decentraland-ecs-utils) | A very handy collection of common tasks made simple. Gradually move, rotate or scale over time. Add trigger areas, delay an action, run an event periodically, and more!. |

<!--
crypto library
MATIC library


physics??
 -->

## Tutorials

### Escape Room Video Tutorial Series

This series of 5 minute videos covers a number of essential concepts, game mechanics and coding best practices. They take you through the whole process of building a full escape room game.

[See the videos](https://hardlydifficult.github.io/dcl-escape-room-tutorial/)

> Tip: The videos are presented in the above link together with written accompanying content, including all the code in case you want to copy and paste parts of it.

The full code from the tutorial is available in this [repository](https://github.com/HardlyDifficult/dcl-escape-room-tutorial).

### Multiplayer & APIs

| Article                                                                     | Description                                                                                        |
| --------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [Servers - Part 1](https://decentraland.org/blog/tutorials/servers-part-1/) | Send requests to an API to fetch data.                                                             |
| [Servers - Part 2](https://decentraland.org/blog/tutorials/servers-part-2/) | Launch your own server on Firebase to handle HTTP requests from your scene and store data in a DB. |

### Other

| Article                                                                                                   | Description                                                                                                                                    |
| --------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| [Creating Genesis Plaza - Part 1](https://decentraland.org/blog/tutorials/creating-genesis-plaza-part-1/) | Tips and tricks that went into the creation of Genesis Plaza, regarding best practices and optimization.                                       |
| [Creating Genesis Plaza - Part 2](https://decentraland.org/blog/tutorials/creator-genesis-plaza-part-2/)  | Guidance about several features that were first introduced with Genesis Plaza, like video and audio streaming, teleports, external links, etc. |
| [Creating Salmonomicon](https://decentraland.org/blog/tutorials/behind-the-scenes-with-salmonomicon/)     | Tips and tricks that went into the creation of Salmonomicon (-50,0). Mostly related to UI and ray casting.                                     |

### Guest Posts

| Article                                                                                                                                            | Description                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [Using the UI](https://decentraland.org/blog/tutorials/adding-a-ui/)                                                                               | A walkthrough by Surz about how to create a UI for your scene.                                            |
| [Picking & Moving Objects](https://decentraland.org/blog/announcements/building-blocks/)                                                           | A walkthrough by Interweaver about how to pick up objects and place them in position, snapping to a grid. |
| [Sprite Animations](https://decentraland.org/blog/tutorials/creating-a-sprite-fire/)                                                               | A walkthrough by Brent Greyling about creating an animated fireplace using 2D sprite images.              |
| [Using the Blockchain - Part 1](https://www.decentral.games/blog/tutorial-1-setting-up-the-decentraland-environment-and-building-your-first-scene) | Part 1 in a series by Baus that goes from scene building essentials to using smart contracts.             |
| [Using the Blockchain - Part 2](https://www.decentral.games/blog/tutorial-2-using-custom-models-and-introduction-to-scripting)                     | Part 2 in a series by Baus that goes from scene building essentials to using smart contracts.             |
| [Using the Blockchain - Part 3](https://www.decentral.games/blog/decentral-games-tutorial-3-advanced-scripting-with-systems)                       | Part 3 in a series by Baus that goes from scene building essentials to using smart contracts.             |
| [Using the Blockchain - Part 4](https://www.decentral.games/blog/tutorial-4-using-the-ethereum-blockchain-in-your-scene)                           | Part 4 in a series by Baus that goes from scene building essentials to using smart contracts.             |
| [Placing Art NFTs](https://decentraland.org/blog/tutorials/placing-nft-art-into-a-scene/)                                                          | A walkthrough by Holodot about how to place NFT 2D art in a scene.                                        |

### 3D Modeling for Decentraland

| Video                                                                       | Description                                                                                                                                                 |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Add a collider](www.youtube.com/watch?v=UrByRRwfGjY)                       | Add a collider to an existing 3D model, to prevent players from walking through it.                                                                         |
| [Add predefined animations](https://www.youtube.com/watch?v=7RSsBmm-rVs)    | Download a freely licenced 3D model from Google Poly, and apply free animations that you can download from Mixamo to it.                                    |
| [Create animations in Blender](https://www.youtube.com/watch?v=eiHI-B5cH4k) | Download a freely licenced 3D model from Google Poly, import it into Blender and then create an _armature_ to manually create your own _animations_ for it. |

## Copyright info

All of these scenes are open source, protected with a standard Apache 2 licence. This licence states that this content can be used freely, even commercially, as long as you acknowledge the author. See the terms and conditions in the [LICENSE](/LICENSE) file.
