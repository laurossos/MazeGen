# MazeGen

MazeGen is a Spigot/Bukkit/PaperMC plugin that turns your Minecraft world into an infinite, randomly generated maze.
It is compatible with the current 1.16.1 release of the game and the respective server platforms.

Feel free to join the 1.16.1 public testing server at:
		
	51.178.92.46:25601

## Building

There are up-to-date builds of the current master available [here](https://github.com/DevMiner-BuildBot/MazeGen-Builds/releases).

To build MazeGen, run the `install` task from your IDE in the Maven section or run this command from your command line.

```bash
mvn install
```

## Setup

To enable the world generator, put the compiled jar into your plugins folder add the following lines to your bukkit.yml:

```yaml
worlds:
  world:
    generator: MazeGen
```

## Screenshots

  ![Screenshot 1](/assets/Maze-Screenshot-1.jpg)
  ![Screenshot 2](/assets/Maze-Screenshot-2.jpg)
  ![Screenshot 3](/assets/Maze-Screenshot-3.jpg)
  ![Screenshot 4](/assets/Maze-Screenshot-4.jpg)
  ![Screenshot 5](/assets/Maze-Screenshot-5.jpg)
  ![Screenshot 6](/assets/Maze-Screenshot-6.jpg)
