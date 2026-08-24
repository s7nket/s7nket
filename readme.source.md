```aura width=860 height=200 link="https://github.com/s7nket"
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(350px); opacity: 1.2; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(-250px); opacity: 1.1; }
      }
      @keyframes float-fast {
        0%, 100% { transform: translateX(0px); opacity: 0.9; }
        50% { transform: translateX(200px); opacity: 0.6; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
      #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.72)" />
        <stop offset="40%" stopColor="rgba(90,15,180,0.35)" />
        <stop offset="70%" stopColor="rgba(90,15,180,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="45%" stopColor="rgba(30,50,200,0.25)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,190,230,0.42)" />
        <stop offset="60%" stopColor="rgba(0,190,230,0.1)" />
        <stop offset="70%" stopColor="rgba(0,190,230,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.5)" />
        <stop offset="60%" stopColor="rgba(130,20,220,0.15)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="glow-1" cx="180" cy="230" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="330" cy="240" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="560" cy="240" rx="200" ry="150" fill="url(#g3)" />
    <ellipse id="glow-4" cx="740" cy="250" rx="150" ry="120" fill="url(#g4)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #6622ee, #0088ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <div style={{
      display: 'flex', width: 88, height: 88, borderRadius: 44,
      background: '#08080c', alignItems: 'center', justifyContent: 'center',
      fontSize: 34, fontWeight: 800, color: '#ffffff', fontFamily: 'Inter',
    }}>ST</div>
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8, position: 'relative' }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      {github?.user?.name || 'Sanket Tengale'}
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(180,165,255,0.8)', fontWeight:400, letterSpacing:'0.3px' }}>
      Final-year CSE student — building multi-agent AI systems and full-stack products
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap: 'wrap' }}>
      {['Python', 'TypeScript', 'React', 'FastAPI'].map(function(tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
            background:'rgba(80,40,220,0.18)', border:'1px solid rgba(100,70,240,0.32)',
            color:'rgba(205,195,255,0.85)', fontSize:12, fontWeight:600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

## Hey, I'm Sanket

I'm a final-year Computer Science Engineering student at KLE College of Engineering & Technology (KLECET), Chikodi, affiliated with VTU. I build full-stack and AI-integrated systems end to end — backend, frontend, and whatever model needs fine-tuning in between — and I'm currently looking for an SDE role at a product-based company.

I also lead a 120+ member coding club at KLECET, split across 12 teams, and I'm gearing up for Smart India Hackathon 2026 with a new AI/ML idea.

## What I'm building

**ARGUS** — my capstone project. A multi-agent AI debate platform with a dual-judge architecture: one judge (Nemotron 30B) writes natural-language verdicts, the other is a Llama 4B model I fine-tuned myself with LoRA/Unsloth on argument-quality datasets to score rounds numerically. FastAPI + WebSockets on the backend, React/TypeScript/Vite on the front, Groq powering the debate agents. The IEEE paper is submitted.

**AGM-HRMS** — a leave management system I co-built, now used by 100+ college staff. React, Zustand, Vite, Tailwind, Supabase. It replaced an earlier version we'd built together on JSP/Tomcat/MySQL.

**ReviewFlow** — a QR-based Google review redirect tool, live for its first client, a dental clinic in Belagavi. FastAPI backend, SQLite, a React/Vite admin dashboard with scan analytics.

**Zeni** — an AI wellness platform for Indian youth on the Claude API. A two-stage pipeline (HuggingFace emotion detection feeding Claude) with a calibration mechanism for human-in-the-loop escalation, built with a regional-language focus for tier-2/3 users.

## Let's connect

```aura width=168 height=44 link="https://github.com/s7nket" inline align=center
<SocialMediaButton icon="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0iI2ZmZmZmZiI+PHBhdGggZD0iTTggMEMzLjU4IDAgMCAzLjU4IDAgOGMwIDMuNTQgMi4yOSA2LjUzIDUuNDcgNy41OS40LjA3LjU1LS4xNy41NS0uMzggMC0uMTktLjAxLS44Mi0uMDEtMS40OS0yLjAxLjM3LTIuNTMtLjQ5LTIuNjktLjk0LS4wOS0uMjMtLjQ4LS45NC0uODItMS4xMy0uMjgtLjE1LS42OC0uNTItLjAxLS41My42My0uMDEgMS4wOC41OCAxLjIzLjgyLjcyIDEuMjEgMS44Ny44NyAyLjMzLjY2LjA3LS41Mi4yOC0uODcuNTEtMS4wNy0xLjc4LS4yLTMuNjQtLjg5LTMuNjQtMy45NSAwLS44Ny4zMS0xLjU5LjgyLTIuMTUtLjA4LS4yLS4zNi0xLjAyLjA4LTIuMTIgMCAwIC42Ny0uMjEgMi4yLjgyLjY0LS4xOCAxLjMyLS4yNyAyLS4yNy42OCAwIDEuMzYuMDkgMiAuMjcgMS41My0xLjA0IDIuMi0uODIgMi4yLS44Mi40NCAxLjEuMTYgMS45Mi4wOCAyLjEyLjUxLjU2LjgyIDEuMjcuODIgMi4xNSAwIDMuMDctMS44NyAzLjc1LTMuNjUgMy45NS4yOS4yNS41NC43My41NCAxLjQ4IDAgMS4wNy0uMDEgMS45My0uMDEgMi4yIDAgLjIxLjE1LjQ2LjU1LjM4QTguMDEgOC4wMSAwIDAgMCAxNiA4YzAtNC40Mi0zLjU4LTgtOC04eiIvPjwvc3ZnPgo=" text="GitHub" backgroundColor="#111111" width={168} height={44} iconSize={18} />
```
```aura width=190 height=44 link="https://www.linkedin.com/in/sanket-tengale" inline align=center
<SocialMediaButton icon="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0iI2ZmZmZmZiI+PHBhdGggZD0iTTE0LjgyIDBIMS4xOEMuNTMgMCAwIC41MiAwIDEuMTZ2MTMuNjhDMCAxNS40OC41MyAxNiAxLjE4IDE2aDEzLjY0Yy42NSAwIDEuMTgtLjUyIDEuMTgtMS4xNlYxLjE2QzE2IC41MiAxNS40NyAwIDE0LjgyIDB6TTQuNzUgMTMuNjNIMi4zOFY2LjE1aDIuMzd2Ny40OHpNMy41NiA1LjEyYTEuMzcgMS4zNyAwIDEgMSAwLTIuNzUgMS4zNyAxLjM3IDAgMCAxIDAgMi43NXptMTAuMDcgOC41MWgtMi4zN1Y5Ljk5YzAtLjktLjAyLTIuMDYtMS4yNi0yLjA2LTEuMjYgMC0xLjQ1Ljk4LTEuNDUgMS45OXYzLjcxSDYuMThWNi4xNWgyLjI4djEuMDJoLjAzYy4zMi0uNiAxLjA5LTEuMjQgMi4yNC0xLjI0IDIuNCAwIDIuODQgMS41OCAyLjg0IDMuNjN2NC4wN3oiLz48L3N2Zz4K" text="LinkedIn" backgroundColor="#0a2540" width={190} height={44} iconSize={18} gradientStops={[
  { offset: '0%', color: '#ffffff' },
  { offset: '20%', color: '#0a66c2' },
  { offset: '50%', color: '#eeeeee' },
  { offset: '70%', color: '#0a66c2' },
  { offset: '100%', color: '#555555' },
]} />
```
```aura width=210 height=44 link="mailto:s7nket@gmail.com" inline align=center
<SocialMediaButton icon="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0iI2ZmZmZmZiI+PHBhdGggZD0iTTEuNSAzQTEuNSAxLjUgMCAwIDAgMCA0LjV2LjM3OWw4IDQuNTcxIDgtNC41NzFWNC41QTEuNSAxLjUgMCAwIDAgMTQuNSAzaC0xM3pNMTYgNi4yNjdsLTYuOTE0IDMuOTUxYTIgMiAwIDAgMS0yLjE3MiAwTDAgNi4yNjdWMTEuNUExLjUgMS41IDAgMCAwIDEuNSAxM2gxM2ExLjUgMS41IDAgMCAwIDEuNS0xLjVWNi4yNjd6Ii8+PC9zdmc+Cg==" text="s7nket@gmail.com" backgroundColor="#1a1030" width={210} height={44} iconSize={18} />
```
