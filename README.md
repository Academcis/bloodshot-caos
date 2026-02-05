<h1>🎮 Bloodshot Chaos</h1>

<div style="border: 1px solid black; padding: 10px;">

<p>
  This project was developed as part of the <strong>Digital Games and Mobile Development</strong> course on the Master's in Computer Engineering (Mobile Computing) degree during the 2023/24 academic year. 
</p>

<h1>Collaborators</h1>
<ul>
  <li><a href="https://github.com/anamsmartins">Ana Martins</a></li>
  <li><a href="https://github.com/ivoafonsobispo">Ivo Bispo</a></li>
</ul>

<h1>Project Description</h1>

<p>
<strong>Bloodshot Chaos</strong> is a fast-paced, pixel-art action shooter designed for mobile platforms.
Set in a chaotic universe where <strong>blood acts as both ammunition and healing</strong>, the game
challenges players to balance aggression, survival, and resource management.
</p>

<p>
Players must defeat waves of enemies while carefully managing their blood tank, which fuels
both shooting and healing abilities. Each playthrough offers a unique experience thanks to
dynamic enemy spawning and configurable encounter zones.
</p>

<p>
The game blends skill and chance, rewarding precision, positioning, and strategic decision-making.
Victory is achieved by defeating the final boss in the fourth area of the game.
</p>

<h1>Game Mechanics</h1>

<h2>Main Mechanic</h2>
<ul>
  <li>Blood tank capacity: <strong>30 points</strong></li>
  <li>Shooting costs 1 blood point per bullet</li>
  <li>Enemies drop blood pools when hit</li>
  <li>Collecting blood restores 8 points</li>
  <li>Healing costs 10 points and fully restores health</li>
  <li>If blood is depleted, the player switches to melee combat</li>
</ul>

<h2>UI & Controls</h2>

![image](https://github.com/anamsmartins/bloodshot-caos/assets/93437355/e5361983-b0f3-46bd-ba6e-c11b1559028b)

<ul>
  <li><strong>Left Joystick:</strong> Player movement</li>
  <li><strong>Right Joystick:</strong> Aim and auto-fire</li>
  <li><strong>Heal Button:</strong> Consume blood to heal</li>
  <li><strong>Interact Button:</strong> Interact with NPCs and collectibles</li>
</ul>

<h1>Game Entities</h1>

<h2>Player</h2>
<ul>
  <li>Space fighter permanently centered on screen</li>
</ul>

<h2>Enemies</h2>
<ul>
  <li><strong>Red Enemy:</strong> High health tank</li>
  <li><strong>Blue Enemy:</strong> Fast shooter, low health</li>
  <li><strong>Yellow Enemy:</strong> Slow movement and attack</li>
  <li><strong>Boss Enemy:</strong> Red variant of the player sprite</li>
</ul>

<h2>Collectibles & Bonus</h2>
<ul>
  <li>Rune Pillars that refill the blood tank</li>
  <li>Bonus relaxation map with NPC interaction and passive enemies</li>
</ul>

<h1>Score System</h1>

<ul>
  <li><strong>Hitting Enemies:</strong>
    <ul>
      <li>Red: 20 pts</li>
      <li>Blue: 40 pts</li>
      <li>Yellow: 30 pts</li>
      <li>Boss: 100 pts</li>
    </ul>
  </li>
  <li><strong>Killing Enemies:</strong>
    <ul>
      <li>Red: 80 pts</li>
      <li>Blue: 160 pts</li>
      <li>Yellow: 60 pts</li>
      <li>Boss: 5000 pts</li>
    </ul>
  </li>
  <li>Healing: 15 pts</li>
  <li>Picking up blood: 30 pts</li>
</ul>

<h1>Replayability</h1>

<p>
Enemy behavior is driven by detection, avoidance, and retreat patterns. Enemies dynamically
spawn based on configuration files that define allowed enemy types, quantities, and spawn areas.
This ensures that each playthrough feels fresh and unpredictable.
</p>

<h1>Optimization</h1>

<p>
Since Bloodshot Chaos targets mobile devices, performance optimization techniques were applied
to ensure smooth gameplay. These optimizations were inspired by industry best practices for
mobile game development.
</p>

<h1>Future Work</h1>
<ul>
  <li>Difficulty balancing through playtesting</li>
  <li>Skill tree system</li>
  <li>Additional levels and enemy types</li>
  <li>New bosses with unique attack patterns</li>
  <li>Expanded roguelike mechanics</li>
</ul>

<h1>Tools & Technologies</h1>
<ul>
  <li>Unity – Game engine</li>
  <li>C# – Gameplay logic and mechanics</li>
  <li>Pixel Art Assets – Visual style</li>
  <li>Mobile Optimization Techniques</li>
</ul>

<h1>Other Information</h1>
<ul>
  <li><strong>Our project received a grade of 18.28 out of 20.</strong></li>
  <li>This project was developed for the <a href="https://www.ipleiria.pt/curso/mestrado-em-engenharia-informatica-computacao-movel/" rel="nofollow">Computer Engineering (Mobile Computing) master's degree</a> at <a href="https://www.ipleiria.pt" rel="nofollow">Polytechnic of Leiria</a></li>
</ul>

<p>
<a href="https://www.ipleiria.pt/estg/" rel="nofollow">
<img src="https://www.ipleiria.pt/normasgraficas/wp-content/uploads/sites/80/2017/09/estg_h-01.jpg"
     width="300"
     alt="Escola Superior de Tecnologia e Gestão"
     style="max-width: 100%;">
</a>
</p>

</div>
