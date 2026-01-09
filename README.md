<div align="center">
  <h1>A* Pathfinder Implementation</h1>
  <p><b>A robust Java implementation of the A* search algorithm for 2D grid navigation.</b></p>
</div>

<hr>

<h3>🚀 Project Overview</h3>
<p>
  This repository demonstrates a classic heuristic search implementation. 
  The algorithm efficiently finds the shortest path between a starting point (marked as <b>2</b>) 
  and a destination (marked as <b>3</b>) within a matrix.
</p>

<h3>🛠️ Technical Specifications</h3>
<ul>
  <li><b>Language:</b> Java.</li>
  <li><b>Heuristic Logic:</b> Combines G-Score (actual cost) and H-Score (estimated distance to target).</li>
  <li><b>Movement:</b> Supports diagonal and orthogonal traversal with cost calculations.</li>
  <li><b>Data Structures:</b> Utilizes <code>ArrayList</code>, <code>HashMap</code>, and 2D arrays for grid management.</li>
</ul>

<h3>📂 Key Components</h3>
<table>
  <tr>
    <th>File</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>AStar.java</code></td>
    <td>Core logic, including distance counting and path prioritization.</td>
  </tr>
  <tr>
    <td><code>Matrix</code></td>
    <td>External grid configuration file used to define obstacles and points.</td>
  </tr>
</table>

<h3>📖 How to Use</h3>
<ol>
  <li>Configure your 10x10 grid in the <code>Matrix</code> file.</li>
  <li>Set your origin (<code>STARTROW</code>/<code>STARTCOL</code>) and destination (<code>ENDROW</code>/<code>ENDCOL</code>) in the source code or via the matrix values.</li>
  <li>Run the application to visualize the calculated coordinates of the shortest path.</li>
</ol>

<hr>

<div align="center">
  <p>Developed as part of my algorithm research and software quality studies at <b>USP</b>.</p>
</div>
