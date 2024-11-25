# Hi 🐸

## [Pentatronic 2024](https://glumbi.itch.io/pentatronic-2024)

Submission for the GMTK 2024 Game Jam with the theme: "Built To Scale", developed in about ~10h using Godot.

![image](https://github.com/user-attachments/assets/5eb3acab-050a-48fb-9d6f-37fc1ead83d8)

## [GHTN](https://github.com/Lumbi/GHTN)

A Hierarchical Task Network implementation based on [Game AI Pro](https://www.gameaipro.com/GameAIPro/GameAIPro_Chapter12_Exploring_HTN_Planners_through_Example.pdf)'s article.

I also created Blueprint bindings for Unreal and a small prototype [here](https://github.com/Lumbi/GHTNProto).

![image](https://github.com/user-attachments/assets/b7508575-6e4d-48b6-ad1e-d142cc973b37)

### [pineBT](https://github.com/Lumbi/pineBT)

A C++ Behavior Tree implementation and FFI bridging to an Electron app allowing editing and previewing a simulated BT in real-time

C++ Builder API example

```cpp
auto behaviorTree = BehaviorTree::build()
	.select()
		.conditon(PlayerVisible)
		.conditon(CanFire)
			.task(FireAtPlayer)
		.sequence()
			.task(MoveToPlayer)
			.task(Wait)
		.close()
		.task(Idle)
	.close()
.end();
```

Electron editor app

<img width="800" alt="Behavior Tree Editor" src="https://github.com/Lumbi/Lumbi/assets/1648852/c9946b7c-4bbb-43b7-a400-ab6d2fbb8df6">

<img width="800" alt="Behavior Tree Editor" src="https://github.com/Lumbi/Lumbi/assets/1648852/4e8affbb-10c0-473a-8329-2e5121039cda">

### [Ball Strikes Back!](https://glumbi.itch.io/ball-strikes-back)

Submission for the GMTK 2023 Game Jam with the theme: "Roles Reversed", developed in about ~8h using Unity

<img width="600" alt="Ball knocking out a player" src="https://github.com/Lumbi/Lumbi/assets/1648852/54effef4-6045-47b9-ae9f-66b100bd8037">

### [Doggo](https://github.com/Lumbi/doggo)

An AI using Unreal's Behavior Tree for a dog that follows you, explores areas around and takes a nap when tired

<img width="646" alt="doggo" src="https://github.com/Lumbi/Lumbi/assets/1648852/b117617d-7f8f-4177-a563-dfed3d62a4b4">

### [Curling Around](https://github.com/Lumbi/curling-around)

A game prototype based on curling using OpenGL

https://github.com/Lumbi/Lumbi/assets/1648852/8138a00b-b859-4e82-b8b1-ef5906f4ad74

### [Gabboy](https://github.com/Lumbi/gabboy)

A Game Boy emulator written in C++, can only run the bootrom

https://github.com/Lumbi/Lumbi/assets/1648852/8da491e9-cde3-4ffa-b667-2808ab414abe

### [Stardust](https://github.com/Lumbi/stardust)

A n-body simulation running on the GPU using Metal

https://github.com/Lumbi/Lumbi/assets/1648852/c7e6420c-b702-4367-9e24-0a97117d6c27

### [GOAP](https://github.com/Lumbi/goap-cpp)

A C++ implementation of goal-oriented action planning

https://github.com/Lumbi/Lumbi/assets/1648852/9d67d082-77b9-419b-a44e-a6564d435a35

### [Lark](https://github.com/Lumbi/game-lark)

A 2D exploration game prototype based on stealth and puzzle solving, written in C# using Unity

_Enemy waypoint, patrolling and chasing mechanic_

https://github.com/Lumbi/Lumbi/assets/1648852/ced7a022-f3ed-4137-a53e-34dec85123fc

### Lander

A 2D game prototype about controlling a lander and finding crystals, written in Swift using SpriteKit

https://github.com/Lumbi/Lumbi/assets/1648852/21cad985-7693-4e93-8fed-4349049532ee

### [MagNet-Soul](https://github.com/Lumbi/MagNet-Soul)

A 2D platformer made in 48 hours with a team of 4 for the GMTK Game Jam 2021, using custom TypeScript engine built during the jam.

https://github.com/Lumbi/Lumbi/assets/1648852/6d22085f-ab77-4191-a205-e1e1673bad18

### [Virtual Tag](https://github.com/Lumbi/virtualtag)

An augmented reality graffiti iOS app, written in Objective-C, using Vuforia

<img width="300" src="https://github.com/Lumbi/Lumbi/assets/1648852/3bbf1493-6afe-494f-9772-0a6fef8e5656">

### [Game of Life](https://github.com/Lumbi/game-of-life-haskell)

Conway's [Game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) written in Haskell using OpenGL

https://github.com/Lumbi/Lumbi/assets/1648852/30866ab6-7851-41ce-9c41-31db9caa9380

### [Dragon Curve](https://github.com/Lumbi/dragoncurve-lsystem-haskell)

A 2D visualization of the [Dragon Curve](https://en.wikipedia.org/wiki/Dragon_curve) [L-system](https://en.wikipedia.org/wiki/L-system) written in Hashell using OpenGL

<img width="800" src="https://github.com/Lumbi/dragoncurve-lsystem-haskell/blob/master/screenshot.png">

### [Spaceship](https://github.com/Lumbi/spaceship-game)

A 2D game prototype à la Asteroids but where bullets ricochet, written C++ using SFML

https://github.com/Lumbi/Lumbi/assets/1648852/fb35d482-305b-48eb-8735-b2abde0f19ec
