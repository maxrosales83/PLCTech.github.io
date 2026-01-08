<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PLC Portfolio | Max Rosales</title>
  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: #0f172a;
      color: #e5e7eb;
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      padding: 80px 24px;
      margin: auto;
    }
    h1, h2 {
      color: #f9fafb;
      letter-spacing: -0.02em;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 16px;
    }
    h2 {
      margin-top: 64px;
      font-size: 1.6rem;
    }
    p {
      max-width: 700px;
      color: #cbd5f5;
    }
    .tagline {
      font-size: 1.1rem;
      margin-bottom: 32px;
    }
    .stack {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 16px;
    }
    .pill {
      background: #1e293b;
      padding: 8px 14px;
      border-radius: 999px;
      font-size: 0.9rem;
    }
    .project {
      background: #020617;
      border: 1px solid #1e293b;
      border-radius: 12px;
      padding: 20px;
      margin-top: 20px;
    }
    footer {
      margin-top: 100px;
      font-size: 0.85rem;
      color: #94a3b8;
    }
    a {
      color: #38bdf8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>PLC & Industrial Controls Portfolio</h1>
    <p class="tagline">
      Hands-on PLC student focused on real-world automation, troubleshooting,
      and electrical systems.
    </p>

    <p>
      I’m currently studying electrical systems and PLC programming, building
      practical projects that simulate industrial environments — motors,
      sensors, relays, and automated sequences. This site documents what I’ve
      built and what I’m actively learning.
    </p>

    <h2>Technical Focus</h2>
    <div class="stack">
      <div class="pill">PLC Fundamentals</div>
      <div class="pill">Ladder Logic</div>
      <div class="pill">Discrete I/O</div>
      <div class="pill">Motor Control</div>
      <div class="pill">Relays & Contactors</div>
      <div class="pill">Electrical Schematics</div>
      <div class="pill">Troubleshooting</div>
    </div>

    <h2>Projects</h2>

    <div class="project">
      <h3>Motor Start / Stop with Safety Interlock</h3>
      <p>
        PLC-controlled motor circuit using start/stop push buttons,
        overload protection, and an emergency stop.
        Implemented using ladder logic with proper latching and fault handling.
      </p>
      <p>
        <strong>Skills:</strong> Ladder logic, safety circuits, motor control
      </p>
    </div>

    <div class="project">
      <h3>Timed Conveyor Sequence</h3>
      <p>
        Automated conveyor simulation using on-delay and off-delay timers
        to control start, run, and stop sequences.
      </p>
      <p>
        <strong>Skills:</strong> Timers, sequencing logic, I/O mapping
      </p>
    </div>

    <div class="project">
      <h3>Traffic Light Control System</h3>
      <p>
        Multi-state traffic light logic with timed transitions and
        fail-safe default states.
      </p>
      <p>
        <strong>Skills:</strong> State logic, timers, structured sequencing
      </p>
    </div>

    <h2>What I’m Learning Next</h2>
    <p>
      PLC troubleshooting under fault conditions, HMI basics, sensors,
      and preparing for field work in industrial environments.
    </p>

    <footer>
      <p>
        Built by Max Rosales ·
        <a href="https://github.com/YOUR_USERNAME" target="_blank">GitHub</a>
      </p>
    </footer>
  </div>

</body>
</html>
