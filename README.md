<h1 align="center">Web Audio Engineering and Interface Design</h1>

<div align="center">
  <img src="nin.png" width="200" height="200" alt="Logo" />
</div>
<div align="center">
  <img src="lazer.png" alt="Lazer Logo" />
</div>

<hr />

<h2>What is this?</h2>
<p>
  The MEGAMICRO suite is a collection of simple, no-nonsense web apps for making music. They are built specifically for <strong>ChromeOS</strong> and modern browsers to be lightweight, fast, and easy to use. No big setups, just tools that work.
</p>

<h3>The Project List</h3>
<h2>Workstations</h2>
  <ul>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/megamicrodaw/">Mega Micro DAW</a> 
      <span class="stats">(47 KB)</span>
      <span class="desc">A lightweight beat-making environment featuring a traditional mixer architecture with FX strips, generative pattern tools, and support for 32 steps across 8 banks.</span>
    </li>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/BapStep8/">BapStep8</a>
      <span class="desc">A lean 16-step sampler and sequencer built for a boom-bap workflow. Includes dedicated FX slots per track and mono-trigger logic for clean sample layering.</span>
    </li>
  </ul>

  <h2>Utilities</h2>
  <ul>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/SP224-Pitch-shifter/">SP-224 Pitch Shifter</a>
      <span class="desc">Focused pitch-corrected time stretching. Inspired by the grit and workflow of the Zoom ST-224 and Boss SP-202 hardware units.</span>
    </li>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/HTML5SAMPLER/">HTML5 Tab Sampler</a>
      <span class="desc">Capture audio directly from a browser tab. Features four quality grades (from lo-fi to clean) with instant export.</span>
    </li>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/LazerBlade3/">Lazer Blade Wave Edit</a>
      <span class="desc">A precise tool for visualizing and trimming audio loops via a zoomable canvas interface.</span>
    </li>
    <li>
      <a class="project-link" href="https://alphaslider.github.io/slicer/">S.L.I.C.E.R</a>
      <span class="desc">A linear interface for setting slice points and exporting chops as individual files or a ZIP archive.</span>
    </li>
  </ul>

<hr />
<h2>Modular Plugins</h2>
    <p>Modular DSP components used in Mega Micro DAW. <a href="https://github.com/alphaslider/megamicrodaw/tree/main/plugins" style="color: #0969da;">View Source on GitHub</a></p>

    <div class="category-grid">
        <div>
            <h3>Dynamics & Tone</h3>
            <ul>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/3bandisolator.js">3-Band Isolator</a><span class="desc">Frequency splitter for isolation.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/LofiComp.js">Lofi Comp</a><span class="desc">Character-driven compression.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/tone.js">Tone</a><span class="desc">Fundamental harmonic shaping.</span></li>
            </ul>

            <h3>Time & Space</h3>
            <ul>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/reverb.js">Reverb</a><span class="desc">Algorithmic spatial depth.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/Tape_Echo.js">Tape Echo</a><span class="desc">Vintage feedback and saturation.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/dub.js">Dub Delay</a><span class="desc">Feedback-heavy performance delay.</span></li>
            </ul>
        </div>

        <div>
            <h3>Character & Lo-Fi</h3>
            <ul>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/Hitachetapedeck.js">Hitache Tape</a><span class="desc">Hardware-style saturation.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/Vinyl_Sim.js">Vinyl Sim</a><span class="desc">Mechanical noise and pitch flutter.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/voicetoskull.js">VoiceToSkull</a><span class="desc">Experimental resonant filtering.</span></li>
            </ul>

            <h3>Performance</h3>
            <ul>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/DJFXLooper.js">DJFX Looper</a><span class="desc">Live beat-repeats and rolls.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/grossglitch.js">Gross Glitch</a><span class="desc">Time-domain buffer chopping.</span></li>
                <li><a class="project-link" href="https://github.com/alphaslider/megamicrodaw/blob/main/plugins/meter2.js">Meter Pro</a><span class="desc">Visual signal level analysis.</span></li>
            </ul>
        </div>
    </div>
<h2>How it works</h2>
<p>The focus here is on <strong>Vanilla JS</strong> and <strong>HTML5</strong>. By avoiding heavy frameworks, these tools stay fast and won't break when the next big update rolls around.</p>

<table width="100%">
  <thead>
    <tr>
      <th align="left">Core</th>
      <th align="left">Markup</th>
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

<h2>Design Choices</h2>
<ul>
  <li><strong>Mono Triggering:</strong> Track cells and samples trigger one at a time. No overlapping, no messy phase issues—just a clean, single signal per track.</li>
  <li><strong>Integrated Mixer:</strong> Includes a built-in mixer and FX loader so you can shape the sound as you go.</li>
  <li><strong>Portable Projects:</strong> The <code>.daw</code> format saves everything (samples and settings) into one file for 100% session recall.</li>
  <li><strong>Zero Dependencies:</strong> Pure code. No external libraries to load or manage.</li>
</ul>

<div align="right">
  <p><sub>Build Status: Ready to Play | Last Sync: 2026.02.07</sub></p>
</div>
