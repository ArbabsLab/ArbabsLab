<style>
  .terminal {
    background-color: #1e1e1e;
    color: #00ff9f;
    font-family: 'Courier New', Courier, monospace;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px rgba(0,255,160,0.4);
    position: relative;
    overflow: hidden;
  }

  .terminal::before {
    content: '';
    display: block;
    position: absolute;
    width: 12px;
    height: 12px;
    background-color: #ff5f56;
    border-radius: 50%;
    top: 10px;
    left: 10px;
    box-shadow: 20px 0 #ffbd2e, 40px 0 #27c93f;
  }

  .typewriter p {
    overflow: hidden;
    white-space: nowrap;
    border-right: 2px solid #00ff9f;
    animation: typing 4s steps(40, end), blink 1s step-end infinite;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink {
    50% { border-color: transparent }
  }
</style>

<div class="terminal">
  <div class="typewriter">
    <p>$ whoami</p>
    <p>Arbab Husain - CS @ City College of New York</p>
    <p>$ echo "Full-Stack Developer | Student"</p>
    <p> Currently building: Fitness Plan Generator</p>
    <p> Learning: Systems Design, Site Reliability Engineering, DevOps</p>
    <p> Soccer lover, Calisthenics master in progress, binger</p>
    
    <br>
    <p>$ skills --list</p>
    <p>🔹 Languages: JavaScript, Python, TypeScript, C++, Java</p>
    <p>🔹 Frontend: React, Next.js, Tailwind CSS</p>
    <p>🔹 Backend: Flask, FastAPI, Node.js</p>
    <p>🔹 DB & Infra: PostgreSQL, Convex, Supabase, MongoDB, Docker</p>
    <p>🔹 Tools: Git, Postman, REST APIs</p>

    <br>
    <p>$ projects --show</p>
    <p>📦 Fitness Plan Chatbot → Personalized workouts using Gemini API</p>

    <br>
    <p>$ contact --all</p>
    <p>🔗 <a href="https://linkedin.com/in/your-link" style="color: #00ff9f;">LinkedIn</a></p>
    <p>✉️ <a href="mailto:your.email@example.com" style="color: #00ff9f;">Email Me</a></p>
    <p>🌐 <a href="https://your-portfolio.com" style="color: #00ff9f;">Portfolio</a></p>

    <br>
    <p>$ exit</p>
    <p>logout</p>
  </div>
</div>
