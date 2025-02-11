# pursuer-evader-solver
Program to solve pursuer evader style graph problems. Inspired by those silly tiktok filters.

<p align="center">
  <img src="https://github.com/adxb-pxthxn/pursuer-evader-solver/blob/main/tiktok.gif" alt="Tiktok Gif @oliver_hatcher">
</p>

<p align="center"> Credit: @oliver_hatcher on tiktok </p>

The app features a UI to create an unweighted and undirected graph specifying the positions of player, enemy, and target. The players goal is to reach the target in any number of turns without getting caught by the enemy. At any given turn the player can move to any neighbour node, the enemy will then move to it's neighbour which is closest to player. Under the hood is a puruit-evasion algorithm which uses BFS to determine a possible solution which is then displayed to the user.




