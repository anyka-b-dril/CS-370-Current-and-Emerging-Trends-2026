# CS-370-Current-and-Emerging-Trends-2026
Students explore advanced topics in CS, specifically Artificial Intelligence (AI) and machine learning. Students will analyze the role of ethics in current trends within the field as well as apply fundamental concepts of the field to solve complex problems in new ways.

<ul>
  <li><b>Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?</b></li>
  <br>
  <p>In the Pirate Intelligent Agent project, I created the Q-Training algorithm that trained the agent to find the best possible navigation sequence that results in reaching the treasure cell while maximizing the reward. With each turn, the agent either chooses a random valid exploration action or predicts the best exploitable action and moves down, up, right, or left. Each action yields a reward, providing the pirate with a measurable measure of success or failure. For instance, moving into a free space earns 1 point, a blocked space is penalized by 1 point, and a revisited space is penalized by 0.25 points. At the end of each game, the agent tallies its reward or score and logs whether it won or lost. The pirate will also store each game in its experience replay. This experience replay stores past actions, the rewards received, and the resulting next states, which the network then uses to train the pathfinding algorithm. This technique imitates how humans create a mental map to navigate new locations.  </p>
  <li><b>Connect your learning from throughout this course to the larger field of computer science:</b></li>
  <ul>
    <li><b>What do computer scientists do and why does it matter?</b></li>
    <br>
    <p>Answer</p>
    <li><b>How do I approach a problem as a computer scientist?</b></li>
    <br>
    <p>Answer</p>
    <li><b>What are my ethical responsibilities to the end user and the organization?</b></li>
    <br>
    <p>Answer</p>
  </ul>
</ul>
