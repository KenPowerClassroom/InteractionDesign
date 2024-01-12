# Storyboards

## The Art of Storyboarding[^1]

A storyboard is a sequence of panels illustrating action in a time-based medium, such as film or animation. In the case of animation, a storyboard helps the designer visualize the action before having to go through the process of making all the art assets.

## Storyboarding in Film

The practice of storyboarding has its origins in the film industry. It is a relative mature practice, and there are several standard techniques for creating storyboards. While film storyboarding is very different than game storyboarding, there is a lot of overlap.

![image](https://github.com/kenpower/kenpower.com/assets/105429/b3f396bd-a1d6-454b-9bbd-ad0a0c14ef9c)

In film, storyboarding is used to help the director not the actors:

- The focus of each panel is to set the scene, in terms of both content and perspective.
- Individual character action is implied but not overly specified in each scene (leave room for actors to _act_).
- Individual panels are intended to represent camera motion and cuts.

There are a lot of conventions about the proper way to draw a storyboard, though the conventions depend on the medium (e.g. film or interactive media).

## Storyboarding in Games

When you storyboard for a game, you want to indicate what the player can do. And the primary thing that the player can do is to control the character (or other game elements). While the player has some control over the camera, this is usually implicit in the control of the character (and not independent of the characters, as in film). Furthermore, the player generally has no control over the scene itself. Therefore the techniques that you use for storyboarding depend on the actions present in your game.

### Aspects of game to capture in a storyboard [^2]

- Players: How do humans affect the game?
  Verbs that describe what the player can do

  - Walk
  - Run
  - Jump
  - Shoot

  Does not need to be attached to an avatar

  - Build
  - Swap
  - Rotate

- Goals: What is the player trying to do?
  - Capture: take or destroy something of value
    - Includes “kill all enemies of type X”
  - Race: reach a goal within time
  - Chase: catch or elude an opponent
  - Race with a dynamic goal/destination
  - Rescue/Escape: Get someone to safety
  - Exploration: Locate something in game world
- Rules: How can the player achieve the goal?
  - Constraints on player actions
  - Can be physical (gravity, friction)
  - Can be logical (puzzle rules)
  - Can be social (rules of engagement)
- Challenges: What obstacles block the goal?

  - Obstacles
    - Prevent progress towards goal
    - Have to be “overcome”
  - Opponents
    - Players or bots with their own goals
    - May or may not need to be overcome
  - Dilemmas
    - Can only perform one of several actions
    - “Correct” choice not immediately clear
  - Resources
    - Limited in supply (ammo, enemy spawns)
    - Can be used up (health, time remaining)
    - Can be traded (power-ups, money)

- Space
  - Where does the game take place?
  - Boundaries and layout of the space?
  - important landmarks?
  - important objects?
  - important paths?

### Storyboarding Disembodied Action

Not all player activity has to be attached to a character. In real-time-strategy games, the player is spending a lot of time clicking on menus and buttons. Even RPGs, which are very character focused, have player modes (such as the “paper doll mode”) that have a lot of disembodied action.

Draw the initial scene
The initial scene can be the entirety of the computer screen, but it does not have to be. You can zoom in just the part of the screen that matters. However, your scene should focus on both the relevant UI element (menu, button, switch, etc.) and the part of the scene that may change (e.g. where new game elements might spawn).

Give some indication of action
Because the action is disembodied, it is likely to correspond to a keyboard or mouse click. You can indicate this with a mouse cursor or a hand. You can also indicate the action with a speech bubble or a thought bubble.

Draw the effect of the action
This is generally a second scene, indicated how the game interface has changed once the action was selected. Again, only focus on the relevant elements.

As a general rule, this process means that each action is a pair of scenes. For example, below we have two pairs of actions for Pokemon Blue. The picture on the** left shows the action and the picture on the right shows the result**.

In the examples below, the top pair of frames show a menu navigation(disembodies action), and the bottom pair shows controling the avatar (embodied)

![image](https://github.com/KenPowerClassroom/InteractionDesign/assets/105429/b9e3427d-650a-4f8c-b30d-963fb295fcfb)

### Storyboarding Embodied Action

The key thing to storyboarding a character is to illustrate its action as it completes (or attempts) to complete a goal. There are two popular ways to do this.

Show player progress in a single scene using movement lines. The style works well for small, compact challenges. It is also good for illustrating when a player has multiple ways of solving a puzzle.

![image](https://github.com/KenPowerClassroom/InteractionDesign/assets/105429/e47ec006-757d-4be1-993b-db751834cd5f)

# Example storyboards

Storyboards vary a lot in style and level of detail. How you draw a storyboard depends on your audience and the ideas you are trying to covey

[^1]: Adapted from https://www.cs.cornell.edu/courses/cs3152/2022sp/labs/design1/
[^2]: Adapted from https://www.cs.cornell.edu/courses/cs3152/2022sp/lectures/lecture3/slides-3.pdf

