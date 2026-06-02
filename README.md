
<style>
  @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Syne:wght@400;700;800&display=swap');
  .profile-wrap { font-family: 'Syne', sans-serif; max-width: 680px; padding: 1.5rem 0; }
  .badge { display: inline-block; font-family: 'Fira Code', monospace; font-size: 11px; padding: 3px 10px; border-radius: 20px; margin: 3px; }
  .skill-tag { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); color: var(--color-text-secondary); font-size: 12px; padding: 4px 10px; border-radius: 20px; display: inline-block; margin: 3px; font-family: 'Fira Code', monospace; }
  .stat-card { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem; text-align: center; }
  .repo-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; }
  .lang-dot { width: 10px; height: 10px; border-radius: 50%; display: inline-block; vertical-align: middle; margin-right: 5px; }
  .section-label { font-size: 11px; font-family: 'Fira Code', monospace; color: var(--color-text-tertiary); letter-spacing: 2px; text-transform: uppercase; margin-bottom: 8px; }
  .copy-btn { background: transparent; border: 0.5px solid var(--color-border-secondary); border-radius: var(--border-radius-md); padding: 6px 14px; font-size: 13px; cursor: pointer; color: var(--color-text-secondary); display: flex; align-items: center; gap: 6px; }
  .copy-btn:hover { background: var(--color-background-secondary); }
  .tab { padding: 6px 14px; border-radius: var(--border-radius-md); font-size: 13px; cursor: pointer; border: 0.5px solid transparent; }
  .tab.active { border-color: var(--color-border-secondary); background: var(--color-background-secondary); color: var(--color-text-primary); }
  .tab:not(.active) { color: var(--color-text-secondary); }
  pre { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1.25rem; font-family: 'Fira Code', monospace; font-size: 12px; line-height: 1.7; overflow-x: auto; white-space: pre-wrap; color: var(--color-text-primary); }
  .green-text { color: #3B6D11; }
  .blue-text { color: #185FA5; }
  .amber-text { color: #BA7517; }
  .teal-text { color: #0F6E56; }
</style>

<div class="profile-wrap">
  <h2 style="font-size:18px; font-weight:500; margin:0 0 4px;">Your new GitHub README</h2>
  <p style="font-size:14px; color:var(--color-text-secondary); margin:0 0 1.5rem;">Preview + copy-ready markdown below</p>

  <div style="display:flex; gap:8px; margin-bottom:1.5rem;">
    <div class="tab active" id="tab-preview" onclick="showTab('preview')">Preview</div>
    <div class="tab" id="tab-md" onclick="showTab('md')">Markdown</div>
  </div>

  <div id="view-preview">
    <div style="background:var(--color-background-primary); border:0.5px solid var(--color-border-tertiary); border-radius:var(--border-radius-lg); padding:1.5rem 1.75rem;">

      <div style="display:flex; align-items:center; gap:12px; margin-bottom:1.5rem;">
        <div style="width:52px; height:52px; border-radius:50%; background:#9FE1CB; display:flex; align-items:center; justify-content:center; font-weight:800; font-size:18px; color:#085041;">CV</div>
        <div>
          <div style="font-size:20px; font-weight:800; font-family:'Syne',sans-serif;">chennamsettyvardhan</div>
          <div style="font-size:13px; color:var(--color-text-secondary); font-family:'Fira Code',monospace;">Full-Stack Developer · Builder of things</div>
        </div>
      </div>

      <div style="border-left:3px solid #1D9E75; padding-left:14px; margin-bottom:1.5rem; font-size:14px; line-height:1.7; color:var(--color-text-secondary);">
        Hey! I'm Vardhan — a developer from Hyderabad 🇮🇳 who loves building web apps, experimenting with AI, and shipping projects that solve real problems. Currently exploring full-stack dev and data engineering.
      </div>

      <div style="margin-bottom:1.5rem;">
        <div class="section-label">currently working on</div>
        <div style="display:flex; flex-wrap:wrap; gap:6px;">
          <span class="skill-tag">⚡ smart-queue-system</span>
          <span class="skill-tag">🧠 ai-virtual-mouse-web</span>
          <span class="skill-tag">📊 SMART-EXPENSES-TRACKER</span>
        </div>
      </div>

      <div style="margin-bottom:1.5rem;">
        <div class="section-label">tech stack</div>
        <div style="display:flex; flex-wrap:wrap; gap:6px;">
          <span class="skill-tag">HTML</span>
          <span class="skill-tag">TypeScript</span>
          <span class="skill-tag">JavaScript</span>
          <span class="skill-tag">React</span>
          <span class="skill-tag">Node.js</span>
          <span class="skill-tag">Azure</span>
          <span class="skill-tag">Python</span>
          <span class="skill-tag">SQL</span>
        </div>
      </div>

      <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(140px,1fr)); gap:10px; margin-bottom:1.5rem;">
        <div class="stat-card">
          <div style="font-size:22px; font-weight:800; font-family:'Syne',sans-serif; color:#1D9E75;">6</div>
          <div style="font-size:12px; color:var(--color-text-secondary);">public repos</div>
        </div>
        <div class="stat-card">
          <div style="font-size:22px; font-weight:800; font-family:'Syne',sans-serif; color:#378ADD;">27</div>
          <div style="font-size:12px; color:var(--color-text-secondary);">contributions</div>
        </div>
        <div class="stat-card">
          <div style="font-size:22px; font-weight:800; font-family:'Syne',sans-serif; color:#BA7517;">3</div>
          <div style="font-size:12px; color:var(--color-text-secondary);">languages</div>
        </div>
      </div>

      <div style="margin-bottom:1.5rem;">
        <div class="section-label">pinned projects</div>
        <div style="display:grid; grid-template-columns:1fr 1fr; gap:10px;">
          <div class="repo-card">
            <div style="font-weight:500; font-size:13px; color:#185FA5; margin-bottom:4px;">💸 SMART-EXPENSES-TRACKER</div>
            <div style="font-size:12px; color:var(--color-text-secondary); line-height:1.5;">Web app to record daily expenses & manage personal finances</div>
            <div style="margin-top:8px;"><span style="background:#F5C4B3; color:#4A1B0C; font-size:11px; padding:2px 8px; border-radius:20px;">HTML</span></div>
          </div>
          <div class="repo-card">
            <div style="font-weight:500; font-size:13px; color:#185FA5; margin-bottom:4px;">🖱️ ai-virtual-mouse-web</div>
            <div style="font-size:12px; color:var(--color-text-secondary); line-height:1.5;">AI-powered virtual mouse control via browser</div>
            <div style="margin-top:8px;"><span style="background:#F5C4B3; color:#4A1B0C; font-size:11px; padding:2px 8px; border-radius:20px;">HTML</span></div>
          </div>
          <div class="repo-card">
            <div style="font-weight:500; font-size:13px; color:#185FA5; margin-bottom:4px;">🚦 smart-queue-system</div>
            <div style="font-size:12px; color:var(--color-text-secondary); line-height:1.5;">Smart queuing system built with JavaScript</div>
            <div style="margin-top:8px;"><span style="background:#FAC775; color:#412402; font-size:11px; padding:2px 8px; border-radius:20px;">JavaScript</span></div>
          </div>
          <div class="repo-card">
            <div style="font-weight:500; font-size:13px; color:#185FA5; margin-bottom:4px;">🌐 Portfolio-Website-main</div>
            <div style="font-size:12px; color:var(--color-text-secondary); line-height:1.5;">Personal portfolio site in TypeScript</div>
            <div style="margin-top:8px;"><span style="background:#CECBF6; color:#26215C; font-size:11px; padding:2px 8px; border-radius:20px;">TypeScript</span></div>
          </div>
        </div>
      </div>

      <div style="display:flex; gap:16px; font-size:13px; color:var(--color-text-secondary);">
        <span>📍 Hyderabad, India</span>
        <span>🔗 <span style="color:#185FA5;">linkedin</span></span>
        <span>📧 reach out anytime</span>
      </div>
    </div>
  </div>

  <div id="view-md" style="display:none;">
    <div style="display:flex; justify-content:flex-end; margin-bottom:8px;">
      <button class="copy-btn" onclick="copyMd()"><i class="ti ti-copy" aria-hidden="true"></i> Copy markdown</button>
    </div>
    <pre id="md-content"></pre>
  </div>
</div>

<script>
const md = `# Hi there, I'm Vardhan 👋

> *Full-Stack Developer · Builder of things · Based in Hyderabad 🇮🇳*

---

Hey! I'm a developer who loves building web apps, experimenting with AI, and shipping projects that solve real problems. Currently exploring full-stack development and data engineering.

## 🚀 Currently Working On
- ⚡ **smart-queue-system** — intelligent queue management
- 🧠 **ai-virtual-mouse-web** — AI-powered virtual mouse via browser
- 📊 **SMART-EXPENSES-TRACKER** — personal finance web app

## 🛠️ Tech Stack
\`\`\`
Frontend   : HTML · TypeScript · JavaScript · React
Backend    : Node.js · Python · SQL
Cloud      : Azure Data Factory · Azure Databricks
\`\`\`

## 📌 Featured Projects

| Project | Description | Tech |
|---|---|---|
| [💸 SMART-EXPENSES-TRACKER](https://github.com/chennamsettyvardhan/SMART-EXPENSES-TRACKER) | Track daily expenses with categories like Food & Travel | HTML |
| [🖱️ ai-virtual-mouse-web](https://github.com/chennamsettyvardhan/ai-virtual-mouse-web) | Control your cursor using AI via the browser | HTML |
| [🚦 smart-queue-system](https://github.com/chennamsettyvardhan/smart-queue-system) | Smart queuing built in JavaScript | JavaScript |
| [🌐 Portfolio-Website-main](https://github.com/chennamsettyvardhan/Portfolio-Website-main) | Personal developer portfolio | TypeScript |

## 📈 GitHub Stats
![Vardhan's GitHub stats](https://github-readme-stats.vercel.app/api?username=chennamsettyvardhan&show_icons=true&theme=default&hide_border=true)

## 📫 Connect With Me
- 📍 Hyderabad, India
- 💼 [LinkedIn](https://linkedin.com/in/your-link-here)
- 📧 your-email@example.com

---
*"Building one commit at a time."*`;

document.getElementById('md-content').textContent = md;

function showTab(t) {
  document.getElementById('view-preview').style.display = t === 'preview' ? 'block' : 'none';
  document.getElementById('view-md').style.display = t === 'md' ? 'block' : 'none';
  document.getElementById('tab-preview').className = 'tab' + (t === 'preview' ? ' active' : '');
  document.getElementById('tab-md').className = 'tab' + (t === 'md' ? ' active' : '');
}

function copyMd() {
  navigator.clipboard.writeText(document.getElementById('md-content').textContent).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.innerHTML = '<i class="ti ti-check" aria-hidden="true"></i> Copied!';
    setTimeout(() => { btn.innerHTML = '<i class="ti ti-copy" aria-hidden="true"></i> Copy markdown'; }, 2000);
  });
}
</script>
