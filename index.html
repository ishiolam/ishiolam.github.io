<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ishi Olam</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=EB+Garamond:ital,wght@0,400;1,400&family=Noto+Serif+Hebrew&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg: #0A0908;
            --text: #E2D9C8;
            --gold: #C5A55A;
            --fire-rgb: 139, 105, 20;
            --card-bg: #12100E;
            --border: #2A2318;
            --hover: #D4B96A;
            
            --cinzel: 'Cinzel', serif;
            --garamond: 'EB Garamond', serif;
            --hebrew: 'Noto Serif Hebrew', serif;
        }

        /* RESET & BASE */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: var(--garamond);
            font-size: 19px;
            line-height: 1.78;
            letter-spacing: 0.01em;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
        }
        a { text-decoration: none; color: inherit; cursor: pointer; }
        button { cursor: pointer; font-family: inherit; }

        /* TYPOGRAPHY */
        h1, h2, h3, .cinzel { font-family: var(--cinzel); color: var(--gold); font-weight: 400; }
        .page-title { font-size: 42px; text-align: center; margin-bottom: 10px; }
        .page-subtitle { font-size: 22px; font-style: italic; text-align: center; color: var(--text); margin-bottom: 80px; }
        .italic { font-style: italic; }
        .gold { color: var(--gold); }
        .small-caps { font-variant: small-caps; letter-spacing: 0.15em; }
        
        /* SPACING & LAYOUT */
        .container { max-width: 700px; margin: 0 auto; padding: 120px 20px; }
        p { margin-bottom: 32px; }
        .divider { text-align: center; color: var(--gold); opacity: 0.4; margin: 80px 0; letter-spacing: 0.5em; }

        /* NAVIGATION */
        nav {
            position: fixed; top: 0; left: 0; width: 100%; height: 56px;
            background: rgba(10, 9, 8, 0.95);
            display: flex; justify-content: space-between; align-items: center;
            padding: 0 40px; z-index: 100;
        }
        .nav-brand { font-family: var(--cinzel); color: var(--gold); font-size: 13px; font-variant: small-caps; letter-spacing: 0.15em; }
        .nav-links { display: flex; gap: 30px; }
        .nav-link {
            font-family: var(--cinzel); font-size: 12px; font-variant: small-caps; letter-spacing: 0.15em;
            color: rgba(197, 165, 90, 0.7); position: relative; transition: color 0.3s ease;
        }
        .nav-link:hover { color: var(--hover); }
        .nav-link::before {
            content: ''; position: absolute; top: 50%; left: 50%; width: 150%; height: 150%;
            background: radial-gradient(circle, rgba(var(--fire-rgb), 0.3) 0%, transparent 70%);
            transform: translate(-50%, -50%) scale(0.8); opacity: 0; transition: opacity 0.3s ease-in, transform 0.3s ease;
            z-index: -1; filter: blur(4px); pointer-events: none;
        }
        .nav-link:hover::before { opacity: 1; transform: translate(-50%, -50%) scale(1); }

        /* WATERMARK */
        .watermark {
            position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%);
            font-family: var(--hebrew); font-size: 200px; color: var(--gold);
            opacity: 0.03; pointer-events: none; z-index: -1; white-space: nowrap;
        }

        /* PAGE TRANSITIONS */
        .page { display: none; opacity: 0; transition: opacity 0.4s ease-in-out; }
        .page.active { display: block; opacity: 1; }

        /* SCROLL ANIMATIONS */
        .fade-up { opacity: 0; transform: translateY(8px); transition: opacity 0.8s ease-out, transform 0.8s ease-out; }
        .fade-up.visible { opacity: 1; transform: translateY(0); }

        /* HOMEPAGE - THE APPROACH */
        #home-darkness { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; position: relative; }
        #approach-text { font-family: var(--garamond); font-style: italic; color: var(--gold); font-size: 28px; text-align: center; z-index: 2; position: relative; }
        .word { opacity: 0; transition: opacity 0.3s ease-in; }
        
        .fire-glow {
            position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);
            width: 400px; height: 400px; border-radius: 50%;
            background: radial-gradient(circle, rgba(var(--fire-rgb), 0.8) 0%, transparent 70%);
            opacity: 0; pointer-events: none; z-index: 1; filter: blur(20px);
        }
        @keyframes breathe {
            0% { opacity: 0.05; transform: translate(-50%, -50%) scale(1); }
            50% { opacity: 0.08; transform: translate(-50%, -50%) scale(1.02); }
            100% { opacity: 0.05; transform: translate(-50%, -50%) scale(1); }
        }
        .scroll-indicator {
            position: absolute; bottom: 40px; width: 1px; height: 40px; background: var(--gold);
            opacity: 0; transition: opacity 2s ease;
        }

        /* CARDS */
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 80px; }
        .card {
            background: var(--card-bg); border: 1px solid var(--border); padding: 40px 30px;
            text-align: center; position: relative; overflow: hidden; cursor: pointer;
        }
        .card-title { font-family: var(--cinzel); color: var(--gold); font-size: 18px; font-variant: small-caps; margin-bottom: 12px; position: relative; z-index: 2; }
        .card-desc { font-style: italic; font-size: 14px; position: relative; z-index: 2; }
        .card::before {
            content: ''; position: absolute; top: 50%; left: 50%; width: 150%; height: 150%;
            background: radial-gradient(circle, rgba(var(--fire-rgb), 0.2) 0%, transparent 60%);
            transform: translate(-50%, -50%); opacity: 0; transition: opacity 0.3s ease-in; z-index: 1; pointer-events: none;
        }
        .card:hover::before { opacity: 1; }

        /* BUTTONS & FORMS */
        .btn {
            display: inline-block; font-family: var(--cinzel); font-variant: small-caps; font-size: 14px; letter-spacing: 0.1em;
            color: var(--gold); border: 1px solid var(--gold); background: transparent; padding: 14px 40px;
            transition: background 0.3s ease, color 0.3s ease; position: relative; overflow: hidden;
        }
        .btn:hover { background: rgba(var(--fire-rgb), 0.15); color: var(--hover); }
        
        input[type="email"] {
            width: 100%; max-width: 400px; background: var(--card-bg); border: 1px solid var(--border);
            color: var(--text); padding: 14px 20px; font-family: var(--garamond); font-size: 16px; margin: 40px auto; display: block; outline: none; transition: border-color 0.3s ease;
        }
        input[type="email"]:focus { border-color: var(--gold); }
        input[type="email"]::placeholder { color: rgba(226, 217, 200, 0.3); }

        /* SPECIFIC ELEMENTS */
        .book-cover {
            width: 340px; height: 520px; background: var(--card-bg); border: 1px solid var(--border); margin: 60px auto;
            display: flex; justify-content: center; align-items: center; position: relative;
        }
        .book-cover::before {
            content: ''; position: absolute; width: 100%; height: 100%;
            background: radial-gradient(circle, rgba(var(--fire-rgb), 0.15) 0%, transparent 70%); z-index: 0; pointer-events: none;
        }
        .whisper { text-align: right; margin-right: 15%; margin-top: 200px; font-style: italic; color: rgba(197, 165, 90, 0.7); font-size: 16px; }
        
        .essay-entry { padding: 40px 0; border-bottom: 1px solid var(--border); }
        .essay-title { font-size: 22px; margin-bottom: 8px; }
        .essay-epigraph { color: rgba(226, 217, 200, 0.7); font-size: 14px; margin-bottom: 16px; }
        .essay-date { color: rgba(197, 165, 90, 0.5); font-size: 12px; font-family: var(--cinzel); }

        .audio-player { background: var(--card-bg); padding: 20px; display: flex; align-items: center; gap: 20px; margin-top: 16px; }
        .play-btn { width: 40px; height: 40px; border-radius: 50%; border: 1px solid var(--gold); display: flex; justify-content: center; align-items: center; }
        .play-triangle { width: 0; height: 0; border-top: 6px solid transparent; border-bottom: 6px solid transparent; border-left: 10px solid var(--gold); margin-left: 4px; }
        .progress-bar { flex-grow: 1; height: 1px; background: rgba(197, 165, 90, 0.3); position: relative; }
        
        .gallery-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
        .gallery-item { aspect-ratio: 1; background: var(--card-bg); position: relative; cursor: pointer; display: flex; justify-content: center; align-items: center; }
        .gallery-item::after { content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(var(--fire-rgb), 0); transition: background 0.4s ease; }
        .gallery-item:hover::after { background: rgba(var(--fire-rgb), 0.1); }
        .gallery-text { font-family: var(--cinzel); opacity: 0.1; font-size: 14px; }

        footer { text-align: center; padding: 80px 20px; }
        
        @media (max-width: 640px) {
            .grid, .gallery-grid { grid-template-columns: 1fr; }
            nav { padding: 0 20px; }
            .nav-links { display: none; } /* Hamburger logic would go here for mobile */
            .watermark { font-size: 100px; }
        }
    </style>
</head>
<body>

    <nav>
        <a class="nav-brand" onclick="navigate('home')">Ishi Olam</a>
        <div class="nav-links">
            <a class="nav-link" onclick="navigate('book')">The Book</a>
            <a class="nav-link" onclick="navigate('writings')">Writings</a>
            <a class="nav-link" onclick="navigate('listen')">Listen</a>
            <a class="nav-link" onclick="navigate('see')">See</a>
            <a class="nav-link" onclick="navigate('gather')">Gather</a>
            <a class="nav-link" onclick="navigate('name')">The Name</a>
        </div>
    </nav>

    <div class="watermark">שַׁלְהֶבֶתְיָה</div>

    <main id="app">
        
        <section id="home" class="page active">
            <div id="home-darkness">
                <div class="fire-glow" id="approach-glow"></div>
                <div id="approach-text"></div>
                <div class="scroll-indicator" id="scroll-ind"></div>
            </div>
            <div class="container">
                <p class="fade-up" style="text-align: center; font-size: 20px; margin-bottom: 80px;">
                    What if every verse of Scripture — every covenant, every prophecy, every name — is a love letter written by a Bridegroom who has been walking toward you since before the foundation of the world?
                </p>
                <div class="grid fade-up">
                    <div class="card" onclick="navigate('book')">
                        <div class="card-title">The Book</div>
                        <div class="card-desc">The Bridegroom: The Desire of God</div>
                    </div>
                    <div class="card" onclick="navigate('writings')">
                        <div class="card-title">Writings</div>
                        <div class="card-desc">Ongoing reflections on Scripture and desire</div>
                    </div>
                    <div class="card" onclick="navigate('listen')">
                        <div class="card-title">Listen</div>
                        <div class="card-desc">The voice in the wilderness</div>
                    </div>
                    <div class="card" onclick="navigate('gather')">
                        <div class="card-title">Gather</div>
                        <div class="card-desc">For those the fire has found</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="book" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Bridegroom</h1>
                <div class="page-subtitle fade-up">The Desire of God</div>
                <div class="cinzel small-caps gold fade-up" style="text-align: center; font-size: 14px;">Ishi Olam</div>
                
                <div class="book-cover fade-up">
                    <div class="cinzel" style="color: rgba(197, 165, 90, 0.2); position: relative; z-index: 1;">Cover Image</div>
                </div>
                
                <div class="divider fade-up">* · * · *</div>
                
                <p class="fade-up" style="text-align: center;">
                    The entire Bible is a love story. From the garden of genesis to the descending city of revelation, it is the record of a God who is not merely a King seeking subjects, but a Bridegroom seeking a bride. He is the one who initiates. You are the one being pursued. 
                </p>
                
                <div class="divider fade-up">* · * · *</div>
                
                <div class="fade-up" style="text-align: center;">
                    <a href="#" class="btn">Read the Book</a>
                </div>
                
                <div class="divider fade-up">* · * · *</div>
                
                <div class="fade-up">
                    <div class="italic gold" style="margin-bottom: 12px; font-size: 16px;">"Set me as a seal upon your heart, as a seal upon your arm, for love is strong as death..." — Song of Solomon 8:6</div>
                    <p>When He speaks from the fire, He does not ask for your servitude. He asks for your gaze. The tragedy of modern theology is that we have mistaken the wedding invitation for a legal summons.</p>
                </div>

                <div class="whisper fade-up">"Where are you?"</div>
            </div>
        </section>

        <section id="writings" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Fire</h1>
                <div class="page-subtitle fade-up">Writings on the Nuptial Mystery</div>

                <div class="card fade-up" style="margin-bottom: 60px; text-align: left;" onclick="navigate('essay-example')">
                    <div class="card-title" style="font-size: 24px; margin-bottom: 16px;">Start Here</div>
                    <div class="card-desc" style="color: var(--text);">An introduction to the theology of pursuit. Why we read the Scripture not as a manual for living, but as the heartbeat of the Bridegroom...</div>
                </div>

                <div class="essay-entry fade-up">
                    <h2 class="essay-title cinzel">The Wound of the Word</h2>
                    <div class="essay-epigraph italic">"Did not our hearts burn within us while he talked to us on the road?" — Luke 24:32</div>
                    <p style="margin-bottom: 12px;">To read the Scriptures rightly is to risk being undone. The text is not flat. It is the very lattice through which He is looking...</p>
                    <div class="essay-date">Feast of the Epiphany</div>
                </div>
                <div class="essay-entry fade-up">
                    <h2 class="essay-title cinzel">The Silence of the Sanctuary</h2>
                    <div class="essay-epigraph italic">"The Lord is in his holy temple; let all the earth keep silence before him." — Habakkuk 2:20</div>
                    <p style="margin-bottom: 12px;">Silence is not the absence of sound. In the architecture of intimacy, silence is the space cleared for the Bridegroom's breath...</p>
                    <div class="essay-date">First Sunday of Advent</div>
                </div>
            </div>
        </section>

        <section id="listen" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Voice</h1>
                <div class="page-subtitle fade-up">Scripture Meditations</div>

                <div class="fade-up" style="margin-bottom: 80px;">
                    <h2 class="cinzel" style="font-size: 20px;">The Approach at Sinai</h2>
                    <div class="italic" style="color: rgba(226, 217, 200, 0.7); font-size: 16px;">Exodus 19</div>
                    <div style="font-size: 14px; margin-top: 8px;">A meditation on the terror and intimacy of the mountain.</div>
                    <div class="audio-player">
                        <div class="play-btn"><div class="play-triangle"></div></div>
                        <div class="progress-bar"></div>
                    </div>
                </div>

                <div class="fade-up">
                    <h2 class="cinzel" style="font-size: 20px;">The Garden Tomb</h2>
                    <div class="italic" style="color: rgba(226, 217, 200, 0.7); font-size: 16px;">John 20</div>
                    <div style="font-size: 14px; margin-top: 8px;">Mary, the angels, and the Voice that speaks her name.</div>
                    <div class="audio-player">
                        <div class="play-btn"><div class="play-triangle"></div></div>
                        <div class="progress-bar"></div>
                    </div>
                </div>
            </div>
        </section>

        <section id="see" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Veil</h1>
                <div class="page-subtitle fade-up">Visual Meditations</div>

                <div class="gallery-grid fade-up">
                    <div class="gallery-item"><span class="gallery-text">Visual Meditation</span></div>
                    <div class="gallery-item"><span class="gallery-text">Visual Meditation</span></div>
                    <div class="gallery-item"><span class="gallery-text">Visual Meditation</span></div>
                    <div class="gallery-item"><span class="gallery-text">Visual Meditation</span></div>
                </div>
            </div>
        </section>

        <section id="gather" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Garden</h1>
                
                <div id="gather-form-area" class="fade-up" style="margin-top: 80px; text-align: center;">
                    <p style="margin-bottom: 40px;">You have followed the fire this far.</p>
                    <p style="margin-bottom: 40px;">Through the Torah and the Prophets and the Song.</p>
                    <p style="margin-bottom: 40px;">Through the Incarnation and the Cross and the locked room.</p>
                    <p style="margin-bottom: 40px;">Through the bread and the breath and the garden at dawn.</p>
                    <p style="margin-bottom: 40px;">You are here.</p>
                    <p style="margin-bottom: 80px;">The fire has found you.</p>

                    <div class="gold italic" style="font-size: 22px;">Leave your name.</div>
                    <input type="email" placeholder="your email" id="email-input">
                    <button class="btn" onclick="submitGather()">Enter</button>
                </div>
                
                <div id="gather-success" style="display: none; text-align: center; margin-top: 120px; opacity: 0; transition: opacity 0.6s ease;">
                    <div class="gold italic" style="font-size: 18px;">The fire knows your name.</div>
                </div>
            </div>
        </section>

        <section id="name" class="page">
            <div class="container">
                <h1 class="page-title fade-up">The Name</h1>
                <div class="italic fade-up" style="text-align: center; color: rgba(226, 217, 200, 0.7); margin-bottom: 60px;">
                    "In that day, declares the LORD, you will call me 'My Husband,' and no longer will you call me 'My Master.'"<br>— Hosea 2:16
                </div>
                
                <div class="fade-up">
                    <p><em>Ishi</em> — my husband. It is the language of Hosea 2:16. God is not satisfied with obedience; He demands union. A master has servants, but a bridegroom has a bride.</p>
                    <p><em>Olam</em> — forever. From Hosea 2:19: "I will betroth you to me forever." It is the eternal duration of His desire.</p>
                    <p>In Hebrew grammar, the <em>vav</em> prefix functions as the bridge, the conjunction, the turning point. It is the Bridegroom's initiative preceding the bride's response. He always speaks first. He always moves first. We do not find Him; we are found by Him.</p>
                    <p>There is no face behind this name. No biography. No credentials. Only a voice, and the Voice it carries. The work exists to make one thing visible: that the God of the Bible is a Bridegroom, and His desire for you is the oldest fire in the cosmos, and it has not gone out.</p>
                    <div style="text-align: center; margin-top: 80px;">
                        <a href="mailto:v.ishi.olam@gmail.com" style="color: rgba(197, 165, 90, 0.6); font-size: 14px;">v.ishi.olam@gmail.com</a>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <footer>
        <div class="cinzel small-caps gold" style="font-size: 12px; margin-bottom: 8px;">Ishi Olam</div>
        <a href="mailto:v.ishi.olam@gmail.com" style="font-size: 12px; color: rgba(197, 165, 90, 0.6);">v.ishi.olam@gmail.com</a>
    </footer>

    <script>
        // PAGE NAVIGATION LOGIC
        function navigate(pageId) {
            window.scrollTo({ top: 0, behavior: 'smooth' });
            const pages = document.querySelectorAll('.page');
            const target = document.getElementById(pageId);
            
            // Fade out current
            document.querySelector('.page.active').style.opacity = '0';
            
            setTimeout(() => {
                pages.forEach(p => { p.classList.remove('active'); p.style.display = 'none'; });
                target.style.display = 'block';
                // Trigger reflow
                void target.offsetWidth;
                target.classList.add('active');
                target.style.opacity = '1';
                
                // Re-trigger scroll animations
                initScrollAnimations();
            }, 400);
        }

        // HOMEPAGE: THE APPROACH ANIMATION
        function initApproach() {
            const container = document.getElementById('approach-text');
            const glow = document.getElementById('approach-glow');
            const ind = document.getElementById('scroll-ind');
            
            const line1 = "The entire Bible is a love story.".split(" ");
            const line2 = "You are the one being pursued.".split(" ");
            
            let html = "<div>";
            line1.forEach(word => html += `<span class="word">${word} </span>`);
            html += "</div><div style='height: 10px;'></div><div>";
            line2.forEach(word => html += `<span class="word">${word} </span>`);
            html += "</div>";
            container.innerHTML = html;

            const words = document.querySelectorAll('.word');
            
            setTimeout(() => {
                let delay = 0;
                
                // Animate first line
                for(let i=0; i<line1.length; i++) {
                    setTimeout(() => words[i].style.opacity = '1', delay);
                    delay += 800; // 0.3s fade + 0.5s pause
                }
                
                // Pause between lines
                delay += 1500;
                
                // Animate second line
                for(let i=0; i<line2.length; i++) {
                    setTimeout(() => words[i + line1.length].style.opacity = '1', delay);
                    delay += 800;
                }
                
                // Ignite the glow
                setTimeout(() => {
                    glow.style.animation = "breathe 5s infinite ease-in-out";
                    setTimeout(() => ind.style.opacity = '1', 2000);
                }, delay);

            }, 1500); // Initial 1.5s darkness
        }

        // SCROLL ANIMATIONS (Intersection Observer)
        function initScrollAnimations() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.fade-up').forEach(el => {
                el.classList.remove('visible'); // reset for page changes
                observer.observe(el);
            });
        }

        // GATHER FORM
        function submitGather() {
            const area = document.getElementById('gather-form-area');
            const success = document.getElementById('gather-success');
            
            area.style.transition = "opacity 0.6s ease";
            area.style.opacity = "0";
            
            setTimeout(() => {
                area.style.display = "none";
                success.style.display = "block";
                // Trigger reflow
                void success.offsetWidth;
                success.style.opacity = "1";
            }, 600);
        }

        // INIT
        window.onload = () => {
            initApproach();
            initScrollAnimations();
        };
    </script>
</body>
</html>
