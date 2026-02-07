<h1 align="center">Mega Micro Music Tools</h1>

<div align="center">
  <img src="nin.png" width="200" height="200" alt="Logo" />
</div>
<div align="center">
  <img src="lazer.png" alt="Lazer Logo" />
</div>

<hr />

<h2>What is this?</h2>
<p>
  A collection of simple, browser-based tools for making music. These apps are designed to be fast, lightweight, and easy to run on <strong>ChromeOS</strong> or any modern browser without needing to install anything.
</p>

<h3>The Apps</h3>
<ul>
  <li><strong><a href="https://alphaslider.github.io/megamicrodaw/">Mega Micro DAW</a></strong> – The main workstation for putting tracks together.</li>
  <li><strong><a href="https://alphaslider.github.io/Omikuji/">Omikuji 3</a></strong> – A randomizer for generating new ideas and patterns.</li>
  <li><strong><a href="https://alphaslider.github.io/SP224-Pitch-shifter/">SP-224 Pitch Shifter</a></strong> – For changing the pitch and speed of your sounds.</li>
  <li><strong><a href="https://alphaslider.github.io/HTML5SAMPLER/">HTML5 Tab Sampler</a></strong> – A quick way to play samples in your browser tabs.</li>
  <li><strong><a href="https://alphaslider.github.io/LazerBlade3/">Lazer Blade Wave Edit</a></strong> – A tool for looking at and cutting up waveforms.</li>
  <li><strong><a href="https://alphaslider.github.io/slicer/">S.L.I.C.E.R</a></strong> – A simple interface for chopping samples and saving them.</li>
</ul>

<hr />

<h2>How it's built</h2>
<p>I use standard web tech to keep things fast and functional. No heavy frameworks or extra bloat—just clean code that plays audio well.</p>

<table width="100%">
  <thead>
    <tr>
      <th align="left">Structure</th>
      <th align="left">Style</th>
      <th align="left">Logic</th>
      <th align="left">Sound</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" /></td>
      <td><img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" /></td>
      <td><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" /></td>
      <td><strong>Web Audio API</strong></td>
    </tr>
  </tbody>
</table>

<hr />

<h2>The Rules</h2>
<ul>
  <li><strong>Mono Triggering:</strong> Samples on the same track will never overlap; new triggers cut off the previous sound to keep the mix clean.</li>
  <li><strong>Mixer & FX:</strong> Built-in mixer and FX loaders stay integrated for immediate sound shaping.</li>
  <li><strong>Vanilla Code:</strong> No external dependencies. This ensures the tools work for a long time and load instantly.</li>
  <li><strong>Portability:</strong> Uses a <code>.daw</code> file format to bundle your samples and project settings into one file.</li>
</ul>

<div align="right">
  <p><sub>Updated: 2026.02.07</sub></p>
</div>
