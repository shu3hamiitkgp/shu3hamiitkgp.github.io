---
layout: default
title: CHM Oral Histories
description: A comprehensive directory of Computer History Museum oral history interviews on YouTube
---

## CHM Oral Histories

A directory of oral history video interviews from the [Computer History Museum](https://computerhistory.org/oral-histories/) (CHM) YouTube channel — computing legends telling their stories in their own words. CHM has recorded 1,000+ interviews; this page covers the ones available as videos on YouTube.

<style>
  .chm-controls {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin: 20px 0 16px;
    align-items: center;
  }
  #chm-search {
    flex: 1;
    min-width: 180px;
    padding: 7px 12px;
    border-radius: 6px;
    border: 1px solid rgba(155,135,245,0.35);
    background: rgba(255,255,255,0.05);
    color: inherit;
    font-size: 0.88rem;
    outline: none;
  }
  #chm-search:focus { border-color: rgba(155,135,245,0.7); }
  .chm-filters {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }
  .chm-filter-btn {
    padding: 4px 10px;
    border-radius: 20px;
    border: 1px solid rgba(155,135,245,0.3);
    background: transparent;
    color: inherit;
    font-size: 0.76rem;
    cursor: pointer;
    transition: all 0.15s;
    opacity: 0.7;
  }
  .chm-filter-btn:hover, .chm-filter-btn.active {
    background: rgba(155,135,245,0.2);
    border-color: rgba(155,135,245,0.7);
    opacity: 1;
  }
  #chm-count {
    font-size: 0.78rem;
    opacity: 0.45;
    margin-left: auto;
    white-space: nowrap;
  }

  .chm-section { margin-top: 28px; }
  .chm-section-title {
    font-size: 0.8rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    opacity: 0.45;
    margin-bottom: 10px;
    padding-bottom: 5px;
    border-bottom: 1px solid rgba(255,255,255,0.07);
  }
  .chm-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }
  @media (max-width: 600px) { .chm-grid { grid-template-columns: 1fr; } }

  .chm-card {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(155,135,245,0.14);
    border-radius: 8px;
    padding: 12px 15px;
    transition: border-color 0.2s, background 0.2s;
  }
  .chm-card:hover {
    background: rgba(155,135,245,0.07);
    border-color: rgba(155,135,245,0.4);
  }
  .chm-card.hidden { display: none; }
  .chm-card-top {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 8px;
  }
  .chm-name {
    font-size: 0.97rem;
    font-weight: 700;
    margin: 0;
    color: #9b87f5;
  }
  .chm-name a { color: #9b87f5; text-decoration: none; }
  .chm-name a:hover { text-decoration: underline; }
  .chm-tag {
    font-size: 0.68rem;
    background: rgba(155,135,245,0.13);
    color: #a78bfa;
    border-radius: 4px;
    padding: 2px 7px;
    white-space: nowrap;
    flex-shrink: 0;
    margin-top: 2px;
  }
  .chm-desc {
    margin: 5px 0 0;
    font-size: 0.83rem;
    line-height: 1.5;
    opacity: 0.82;
  }
  .chm-multi {
    font-size: 0.7rem;
    opacity: 0.45;
    margin-top: 4px;
  }
  .chm-multi a { color: inherit; }

  .chm-section.hidden { display: none; }
  .chm-legend {
    font-size: 0.8rem;
    opacity: 0.5;
    margin-top: 36px;
    border-top: 1px solid rgba(255,255,255,0.07);
    padding-top: 12px;
  }
  #chm-noresults {
    display: none;
    opacity: 0.5;
    font-size: 0.9rem;
    padding: 20px 0;
  }
</style>

<div class="chm-controls">
  <input id="chm-search" type="text" placeholder="Search by name or keyword..." />
  <span id="chm-count"></span>
</div>
<div class="chm-filters" id="chm-filters">
  <button class="chm-filter-btn active" data-cat="all">All</button>
  <button class="chm-filter-btn" data-cat="Languages">Languages</button>
  <button class="chm-filter-btn" data-cat="OS &amp; Systems">OS &amp; Systems</button>
  <button class="chm-filter-btn" data-cat="Hardware &amp; Chips">Hardware &amp; Chips</button>
  <button class="chm-filter-btn" data-cat="Graphics &amp; HCI">Graphics &amp; HCI</button>
  <button class="chm-filter-btn" data-cat="AI &amp; ML">AI &amp; ML</button>
  <button class="chm-filter-btn" data-cat="Networking &amp; Internet">Networking &amp; Internet</button>
  <button class="chm-filter-btn" data-cat="Personal Computing">Personal Computing</button>
  <button class="chm-filter-btn" data-cat="Databases">Databases</button>
  <button class="chm-filter-btn" data-cat="Crypto &amp; Security">Crypto &amp; Security</button>
  <button class="chm-filter-btn" data-cat="Software Eng.">Software Eng.</button>
  <button class="chm-filter-btn" data-cat="Gaming">Gaming</button>
  <button class="chm-filter-btn" data-cat="Entrepreneurship">Entrepreneurship</button>
</div>

<div id="chm-noresults">No interviews match your search.</div>

<!-- ═══════════════════════════════ LANGUAGES ═══════════════════════════════ -->
<div class="chm-section" data-section="Languages">
<div class="chm-section-title">Programming Languages</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Languages" data-name="Donald Knuth">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=Wp7GAKLSGnI" target="_blank">Donald Knuth</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Author of <em>The Art of Computer Programming</em>, the bible of algorithm analysis. Creator of TeX. Turing Award winner, 1974.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=gqPPll3uDa0" target="_blank">Part 2 →</a></p>
</div>

<div class="chm-card" data-cat="Languages" data-name="John Backus">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=dDsWTyLEgbk" target="_blank">John Backus</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Created FORTRAN, the first widely used high-level programming language (1957), and invented Backus-Naur Form (BNF) for describing language grammars. Turing Award, 1977.</p>
</div>

<div class="chm-card" data-cat="Languages" data-name="John McCarthy">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=KuU82i3hi8c" target="_blank">John McCarthy</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Created the LISP programming language (1958) and coined the term "artificial intelligence." Founded the Stanford AI Lab. Turing Award, 1971.</p>
</div>

<div class="chm-card" data-cat="Languages" data-name="Bjarne Stroustrup">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=ZO0PXYMVGSU" target="_blank">Bjarne Stroustrup</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Designer and creator of C++ at Bell Labs in the early 1980s. One of the most widely used languages in the world, powering systems software, games, and embedded devices.</p>
</div>

<div class="chm-card" data-cat="Languages" data-name="James Gosling">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=TJ6XHroNewc" target="_blank">James Gosling</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Creator of Java at Sun Microsystems. Java became the world's most-deployed programming language and the foundation for Android, enterprise systems, and billions of devices.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=LaJtYHvpa68" target="_blank">Part 2 →</a></p>
</div>

<div class="chm-card" data-cat="Languages" data-name="Guido van Rossum">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=Pzkdci2HDpU" target="_blank">Guido van Rossum</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Creator of the Python programming language, designed with readability as a core principle. Python became the dominant language for data science, AI/ML, and scripting.</p>
</div>

<div class="chm-card" data-cat="Languages" data-name="Alfred Aho">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=ir9Mwl9zhIM" target="_blank">Alfred V. Aho</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Co-created the AWK text-processing language, co-authored the "Dragon Book" (the definitive compiler textbook), and made fundamental contributions to algorithms and string matching. Turing Award, 2020.</p>
</div>

<div class="chm-card" data-cat="Languages" data-name="Ken Thompson">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=wqI7MrtxPnk" target="_blank">Ken Thompson</a></p>
    <span class="chm-tag">Languages</span>
  </div>
  <p class="chm-desc">Co-created Unix and the B language (C's precursor) at Bell Labs. Co-designed the Go programming language at Google. Turing Award, 1983.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=OmVHkL0IWk4" target="_blank">Extended 2024 interview →</a></p>
</div>

</div></div>

<!-- ═══════════════════════════════ OS & SYSTEMS ═══════════════════════════════ -->
<div class="chm-section" data-section="OS &amp; Systems">
<div class="chm-section-title">Operating Systems &amp; Systems Software</div>
<div class="chm-grid">

<div class="chm-card" data-cat="OS &amp; Systems" data-name="Dennis Ritchie">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=de2Hsvxaf8M" target="_blank">Dennis Ritchie</a></p>
    <span class="chm-tag">OS &amp; Systems</span>
  </div>
  <p class="chm-desc">Created the C programming language and co-created Unix at Bell Labs. His work arguably underpins all modern software. Turing Award, 1983 (shared with Thompson).</p>
</div>

<div class="chm-card" data-cat="OS &amp; Systems" data-name="Dave Cutler">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=29RkHH-psrY" target="_blank">Dave Cutler</a></p>
    <span class="chm-tag">OS &amp; Systems</span>
  </div>
  <p class="chm-desc">Lead architect of DEC's VMS and then Microsoft's Windows NT — the kernel that became the foundation for every modern Windows version. One of the most prolific OS designers in history.</p>
</div>

<div class="chm-card" data-cat="OS &amp; Systems" data-name="Linus Torvalds">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=A4oLRnG2q3Q" target="_blank">Linus Torvalds</a></p>
    <span class="chm-tag">OS &amp; Systems</span>
  </div>
  <p class="chm-desc">Created the Linux kernel (1991) which now runs most of the world's servers, Android phones, and supercomputers. Also created Git, the version-control system used by virtually all software projects.</p>
</div>

<div class="chm-card" data-cat="OS &amp; Systems" data-name="Ray Ozzie">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=4Mj_zDw21xY" target="_blank">Ray Ozzie</a></p>
    <span class="chm-tag">OS &amp; Systems</span>
  </div>
  <p class="chm-desc">Created Lotus Notes, one of the first widely-deployed groupware and email platforms. Later became Chief Software Architect at Microsoft, succeeding Bill Gates in that role.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ HARDWARE & CHIPS ═══════════════════════════════ -->
<div class="chm-section" data-section="Hardware &amp; Chips">
<div class="chm-section-title">Hardware, Chips &amp; Semiconductors</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Gordon Moore">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=gtcLzokagAw" target="_blank">Gordon Moore</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Co-founder of Intel and author of Moore's Law — the 1965 observation that transistor density doubles roughly every two years. This prediction guided the semiconductor industry for decades.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Jim Keller">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=Xh8nhK7WS80" target="_blank">Jim Keller</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Legendary chip architect behind AMD K8 (64-bit x86), Apple A4/A5, AMD Zen, and Tesla's Autopilot chip. Known for leading small teams to outsized breakthroughs in processor design.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Chuck Peddle">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=enHF9lMseP8" target="_blank">Chuck Peddle</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Lead designer of the MOS 6502, one of the most influential chips ever made. The 6502 powered the Apple I, Apple II, Atari 2600, Commodore 64, and NES — igniting the personal computer and gaming revolutions.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Jensen Huang">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=0c8i4T9BSqY" target="_blank">Jensen Huang</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Co-founder and CEO of NVIDIA, which invented the GPU and became the engine of the modern AI revolution. Under his 30-year leadership, NVIDIA grew into one of the world's most valuable companies.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Charlie Sporck">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=duMUvoKP-pk" target="_blank">Charlie Sporck</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">CEO of National Semiconductor and a towering figure in the early semiconductor industry. Pioneered the offshore manufacturing model that defined the global chip supply chain.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Pradeep Sindhu">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=PL40bQPP1EA" target="_blank">Pradeep Sindhu</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Co-founder and Chief Scientist of Juniper Networks. His research at Xerox PARC and work on high-performance networking routers helped define the backbone infrastructure of the internet.</p>
</div>

<div class="chm-card" data-cat="Hardware &amp; Chips" data-name="Bernard Widrow">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=CRFJkDBuQzY" target="_blank">Bernard Widrow</a></p>
    <span class="chm-tag">Hardware &amp; Chips</span>
  </div>
  <p class="chm-desc">Pioneer of adaptive signal processing and neural networks. Invented the ADALINE (Adaptive Linear Neuron) model and the LMS algorithm in 1960 — foundational work that preceded modern deep learning.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ GRAPHICS & HCI ═══════════════════════════════ -->
<div class="chm-section" data-section="Graphics &amp; HCI">
<div class="chm-section-title">Graphics, HCI &amp; User Interfaces</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Ivan Sutherland">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=Bjr7qLeyvlw" target="_blank">Ivan Sutherland</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Father of computer graphics. His 1963 Sketchpad dissertation was the world's first interactive graphics program, laying groundwork for GUIs, CAD, and virtual reality. Turing Award, 1988.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=z8ZQJx0abj4" target="_blank">Part 2 →</a></p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Douglas Engelbart">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=iqJCvuHrkOI" target="_blank">Douglas Engelbart</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Inventor of the computer mouse and hypertext. His 1968 "Mother of All Demos" previewed the GUI, video conferencing, and collaborative editing — decades before they became mainstream.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Alan Kay">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=wqI7MrtxPnk" target="_blank">Alan Kay</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Pioneer of OOP and the Smalltalk language at Xerox PARC. Conceived the Dynabook — the conceptual forerunner of the laptop and tablet. His work directly inspired the Macintosh GUI. Turing Award, 2003.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Adele Goldberg">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=fjDVaHNA8ls" target="_blank">Adele Goldberg</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Key developer of Smalltalk-80 at Xerox PARC and a champion of object-oriented programming and user-centered design. Co-authored the definitive Smalltalk book and influenced the design of the Macintosh.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Edwin Catmull">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=imrliaThKrI" target="_blank">Edwin Catmull</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Co-founder of Pixar and pioneer of 3D computer graphics. Invented key rendering algorithms (z-buffering, texture mapping) and led Pixar to produce the first fully computer-animated feature film, Toy Story. Turing Award, 2019.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Butler Lampson">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=iegl5MFqk6Y" target="_blank">Butler Lampson</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Researcher at Xerox PARC who contributed to the Alto personal computer — the first machine with a GUI, mouse, and ethernet. His work influenced virtually every modern PC. Turing Award, 1992.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Bas Ording">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=2x9XdVWr_70" target="_blank">Bas Ording</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Apple UI designer who created many of the iconic iPhone interactions — the rubber-band scroll, the slide-to-unlock animation, and the fluid touch gestures that defined the smartphone era.</p>
</div>

<div class="chm-card" data-cat="Graphics &amp; HCI" data-name="Bert Sutherland">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=NZJxwzVx5BY" target="_blank">Bert Sutherland</a></p>
    <span class="chm-tag">Graphics &amp; HCI</span>
  </div>
  <p class="chm-desc">Computer scientist and research lab director (Xerox PARC, SUN Labs) who contributed to early networked computing and graphics. Brother of Ivan Sutherland.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ AI & ML ═══════════════════════════════ -->
<div class="chm-section" data-section="AI &amp; ML">
<div class="chm-section-title">Artificial Intelligence &amp; Machine Learning</div>
<div class="chm-grid">

<div class="chm-card" data-cat="AI &amp; ML" data-name="Edward Feigenbaum">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=11UxoW-_4NU" target="_blank">Edward Feigenbaum</a></p>
    <span class="chm-tag">AI &amp; ML</span>
  </div>
  <p class="chm-desc">Pioneer of expert systems and "knowledge engineering." Co-founded the Stanford Heuristic Programming Project and built DENDRAL and MYCIN — early AI systems that demonstrated machines could match expert human reasoning. Turing Award, 1994.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=7N0HL8Gc01w" target="_blank">Session 2 →</a> <a href="https://www.youtube.com/watch?v=7MekVtYyhIc" target="_blank">Part 2 →</a></p>
</div>

<div class="chm-card" data-cat="AI &amp; ML" data-name="Jürgen Schmidhuber">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=5ggjLhYVzh8" target="_blank">Jürgen Schmidhuber</a></p>
    <span class="chm-tag">AI &amp; ML</span>
  </div>
  <p class="chm-desc">Co-inventor of the LSTM (Long Short-Term Memory) neural network, the architecture that powered speech recognition, machine translation, and sequence modeling before the transformer era.</p>
</div>

<div class="chm-card" data-cat="AI &amp; ML" data-name="John McCarthy">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=KuU82i3hi8c" target="_blank">John McCarthy</a></p>
    <span class="chm-tag">AI &amp; ML</span>
  </div>
  <p class="chm-desc">Coined the term "artificial intelligence" and organized the 1956 Dartmouth Conference that launched AI as a field. Created LISP, the dominant AI research language for decades. Turing Award, 1971.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ NETWORKING & INTERNET ═══════════════════════════════ -->
<div class="chm-section" data-section="Networking &amp; Internet">
<div class="chm-section-title">Networking &amp; Internet</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Networking &amp; Internet" data-name="Vint Cerf">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=7w0HDoAT8dI" target="_blank">Vint Cerf</a></p>
    <span class="chm-tag">Networking &amp; Internet</span>
  </div>
  <p class="chm-desc">Co-designed TCP/IP, the protocol suite that forms the technical foundation of the internet. Known as a "Father of the Internet." Long-time VP at Google. Turing Award, 2004.</p>
</div>

<div class="chm-card" data-cat="Networking &amp; Internet" data-name="Robert Metcalfe">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=zKz07DdaKzw" target="_blank">Robert Metcalfe</a></p>
    <span class="chm-tag">Networking &amp; Internet</span>
  </div>
  <p class="chm-desc">Inventor of Ethernet at Xerox PARC and founder of 3Com. Ethernet became the universal standard for local networking. Also known for Metcalfe's Law: a network's value grows with the square of its users. Turing Award, 2022.</p>
</div>

<div class="chm-card" data-cat="Networking &amp; Internet" data-name="John Chambers">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=CcA4aHKL_bE" target="_blank">John Chambers</a></p>
    <span class="chm-tag">Networking &amp; Internet</span>
  </div>
  <p class="chm-desc">CEO of Cisco Systems 1995–2015, growing it from $1.2B to $47B in revenue. Cisco's routers and switches became the plumbing of the internet. Known for navigating Cisco through the dot-com bust via aggressive acquisitions.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ PERSONAL COMPUTING ═══════════════════════════════ -->
<div class="chm-section" data-section="Personal Computing">
<div class="chm-section-title">Personal Computing &amp; Apple</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Personal Computing" data-name="Steve Wozniak">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=0-EZMvLDrX4" target="_blank">Steve Wozniak</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Co-founder of Apple and sole designer of the Apple I and Apple II — the machines that launched the personal computer industry. Widely regarded as one of the greatest hardware engineers ever.</p>
</div>

<div class="chm-card" data-cat="Personal Computing" data-name="Mike Markkula">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=0DuOnDWRwI4" target="_blank">Mike Markkula</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Apple's first major investor and co-founder who provided $250,000 in seed funding and became Apple's first chairman. Wrote Apple's early marketing philosophy and was instrumental in turning it into a real company.</p>
</div>

<div class="chm-card" data-cat="Personal Computing" data-name="Jon Rubinstein">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=PJxElfc0N9E" target="_blank">Jon Rubinstein</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Apple's SVP of Hardware Engineering and "father of the iPod." Led engineering on the iMac G3, PowerBook G4, and the iPod line before later becoming CEO of Palm.</p>
  <p class="chm-multi"><a href="https://www.youtube.com/watch?v=47bNpIbCaL8" target="_blank">Session 2 →</a></p>
</div>

<div class="chm-card" data-cat="Personal Computing" data-name="Dan'l Lewin">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=qJdF96yG5D0" target="_blank">Dan'l Lewin</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Early Apple executive who led higher education sales for the original Macintosh, then followed Steve Jobs to NeXT as VP of Marketing. Later a senior executive at Microsoft helping build its startup ecosystem.</p>
</div>

<div class="chm-card" data-cat="Personal Computing" data-name="Allen Baum">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=wN02z1KbFmY" target="_blank">Allen Baum</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Early Apple engineer and longtime friend of Steve Wozniak who helped recruit Wozniak to build the Apple I. Later contributed to the RISC-V instruction set architecture.</p>
</div>

<div class="chm-card" data-cat="Personal Computing" data-name="Scott McNealy">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=1qttU8U3ZvQ" target="_blank">Scott McNealy</a></p>
    <span class="chm-tag">Personal Computing</span>
  </div>
  <p class="chm-desc">Co-founder and CEO of Sun Microsystems. Sun produced the SPARC processor, the Java language (through James Gosling), and pioneered the "The Network is the Computer" vision long before cloud computing.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ DATABASES ═══════════════════════════════ -->
<div class="chm-section" data-section="Databases">
<div class="chm-section-title">Databases</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Databases" data-name="Donald Chamberlin">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/playlist?list=PLQsxaNhYv8daKdGi7s85ubzbWdTB36-_q" target="_blank">Donald Chamberlin</a></p>
    <span class="chm-tag">Databases</span>
  </div>
  <p class="chm-desc">Co-creator of SQL (Structured Query Language) at IBM. SQL became the universal language for relational databases, still used by virtually every data-driven application on the planet. ACM Software System Award, 1988.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ CRYPTO & SECURITY ═══════════════════════════════ -->
<div class="chm-section" data-section="Crypto &amp; Security">
<div class="chm-section-title">Cryptography &amp; Security</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Crypto &amp; Security" data-name="Ronald Rivest">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=gQJmqQrcazU" target="_blank">Ronald Rivest</a></p>
    <span class="chm-tag">Crypto &amp; Security</span>
  </div>
  <p class="chm-desc">The "R" in RSA — the public-key cryptography algorithm that secures the internet. Also invented the MD5 and SHA hash functions and the RC4 cipher. Turing Award, 2002 (shared with Shamir and Adleman).</p>
</div>

</div></div>

<!-- ═══════════════════════════════ SOFTWARE ENG ═══════════════════════════════ -->
<div class="chm-section" data-section="Software Eng.">
<div class="chm-section-title">Software Engineering</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Software Eng." data-name="Barry Boehm">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=AULogC_ub30" target="_blank">Barry Boehm</a></p>
    <span class="chm-tag">Software Eng.</span>
  </div>
  <p class="chm-desc">Pioneer of software engineering economics and process models. Created the COCOMO cost estimation model and the Spiral Model of software development — foundational concepts for managing large software projects.</p>
</div>

<div class="chm-card" data-cat="Software Eng." data-name="Tony Wasserman">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=S7UytX6uzXY" target="_blank">Tony Wasserman</a></p>
    <span class="chm-tag">Software Eng.</span>
  </div>
  <p class="chm-desc">Pioneer in software engineering methods and tools, including early work on structured design, software development environments, and open-source software business models.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ GAMING ═══════════════════════════════ -->
<div class="chm-section" data-section="Gaming">
<div class="chm-section-title">Gaming</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Gaming" data-name="Nolan Bushnell">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=izYWqhUGBGA" target="_blank">Nolan Bushnell</a></p>
    <span class="chm-tag">Gaming</span>
  </div>
  <p class="chm-desc">Founder of Atari and creator of Pong, which launched the video game industry. Also founded Chuck E. Cheese and was an early mentor to Steve Jobs, shaping Silicon Valley's startup culture.</p>
</div>

</div></div>

<!-- ═══════════════════════════════ ENTREPRENEURSHIP ═══════════════════════════════ -->
<div class="chm-section" data-section="Entrepreneurship">
<div class="chm-section-title">Entrepreneurship &amp; Venture Capital</div>
<div class="chm-grid">

<div class="chm-card" data-cat="Entrepreneurship" data-name="Steve Blank">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=qToxb6PVp9I" target="_blank">Steve Blank</a></p>
    <span class="chm-tag">Entrepreneurship</span>
  </div>
  <p class="chm-desc">Serial entrepreneur and creator of the Customer Development methodology — the foundation of the Lean Startup movement. His work transformed how startups validate ideas and is taught in entrepreneurship programs worldwide.</p>
</div>

<div class="chm-card" data-cat="Entrepreneurship" data-name="David Morgenthaler">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=1w3DXB5SSR0" target="_blank">David Morgenthaler</a></p>
    <span class="chm-tag">Entrepreneurship</span>
  </div>
  <p class="chm-desc">Pioneer of the modern venture capital industry who founded Morgenthaler Ventures in 1968, making it one of the oldest VC firms in the US. Backed dozens of foundational technology companies over five decades.</p>
</div>

<div class="chm-card" data-cat="Entrepreneurship" data-name="Chuck Newhall">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=FSruTgf7to0" target="_blank">Chuck Newhall</a></p>
    <span class="chm-tag">Entrepreneurship</span>
  </div>
  <p class="chm-desc">Co-founder of New Enterprise Associates (NEA), one of the largest and most prolific venture capital firms in the world, with investments across semiconductors, software, and biotech spanning four decades.</p>
</div>

<div class="chm-card" data-cat="Entrepreneurship" data-name="Alan Patricof">
  <div class="chm-card-top">
    <p class="chm-name"><a href="https://www.youtube.com/watch?v=AU5iFGmcQYA" target="_blank">Alan Patricof</a></p>
    <span class="chm-tag">Entrepreneurship</span>
  </div>
  <p class="chm-desc">Founding father of the venture capital industry and founder of Apax Partners. Early investor in Apple Computer, AOL, Office Depot, and New York Magazine. Helped establish the modern VC model.</p>
</div>

</div></div>

<div id="chm-noresults">No interviews match your search.</div>

<div class="chm-legend">
  Links go to the CHM YouTube channel. For multi-session interviews, the card links to Session 1. Browse the full <a href="https://www.youtube.com/playlist?list=PLQsxaNhYv8daKdGi7s85ubzbWdTB36-_q" target="_blank">CHM Oral Histories playlist</a> and the <a href="https://computerhistory.org/oral-histories/" target="_blank">CHM website</a> for the complete 1,000+ interview collection.
</div>

<script>
(function() {
  var cards = Array.from(document.querySelectorAll('.chm-card'));
  var sections = Array.from(document.querySelectorAll('.chm-section'));
  var searchInput = document.getElementById('chm-search');
  var filterBtns = Array.from(document.querySelectorAll('.chm-filter-btn'));
  var countEl = document.getElementById('chm-count');
  var noResults = document.getElementById('chm-noresults');
  var activeCat = 'all';

  function updateCount(n) {
    countEl.textContent = n + ' interview' + (n !== 1 ? 's' : '');
  }

  function filter() {
    var query = searchInput.value.toLowerCase().trim();
    var visible = 0;

    cards.forEach(function(card) {
      var catMatch = activeCat === 'all' || card.dataset.cat === activeCat;
      var nameText = (card.dataset.name || '').toLowerCase();
      var descText = card.querySelector('.chm-desc') ? card.querySelector('.chm-desc').textContent.toLowerCase() : '';
      var tagText = card.dataset.cat.toLowerCase();
      var textMatch = !query || nameText.includes(query) || descText.includes(query) || tagText.includes(query);
      var show = catMatch && textMatch;
      card.classList.toggle('hidden', !show);
      if (show) visible++;
    });

    // Hide empty sections
    sections.forEach(function(sec) {
      var anyVisible = Array.from(sec.querySelectorAll('.chm-card')).some(function(c) {
        return !c.classList.contains('hidden');
      });
      sec.classList.toggle('hidden', !anyVisible);
    });

    noResults.style.display = visible === 0 ? 'block' : 'none';
    updateCount(visible);
  }

  searchInput.addEventListener('input', filter);

  filterBtns.forEach(function(btn) {
    btn.addEventListener('click', function() {
      filterBtns.forEach(function(b) { b.classList.remove('active'); });
      btn.classList.add('active');
      activeCat = btn.dataset.cat;
      filter();
    });
  });

  filter();
})();
</script>
