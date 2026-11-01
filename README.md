<p align="center">
    <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExODM3aHB6Z2t5OXNxdjAxcGlsZXQwZXpyMmNoODFkZzd6bnp4dnJqbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaV9pZCZjdD1n/MCXgiBVDl8QtojG1fU/giphy.gif" 
      alt="Cybersecurity Banner" width="600"/>
</p>

<h1 align="center">Hi there, I'm FE4RD0WN !! 👋</h1>
<h3 align="center">"Known as Random people and random repo :3"</h3>

<p align="center">
  <img src="https://img.shields.io/badge/👁️_10.3K_Profile_Views-1e90ff?style=for-the-badge" alt="Profile Views"/>
  <img src="https://komarev.com/ghpvc/?username=Danarfr27&style=flat-square&color=grey" alt="" width="1" height="1"/>
</p>

---

## 🏆 Security Recognition

<p align="center">
  <img src="https://raw.githubusercontent.com/Danarfr27/NASA/main/we.jpeg" 
       alt="NASA VDP Recognition Letter" width="600"/>
</p>

<p align="center">
  <b>🚀 NASA Vulnerability Disclosure Program (VDP)</b><br>
  <sub>Recognized for responsible security vulnerability reporting — March 2026</sub>
</p>

---

## 🤖 AI Chat Assistant

<p align="center">
  <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIRDHAN-AGENT-V1.0</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@400;500;600;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #00f0ff;
            --secondary: #ff006e;
            --accent: #ffd700;
            --bg-dark: #0a0a0f;
            --bg-panel: rgba(16, 16, 24, 0.95);
            --border-glow: rgba(0, 240, 255, 0.3);
            --text-primary: #e0e0e0;
            --text-dim: #888;
        }

        body {
            font-family: 'Rajdhani', sans-serif;
            background: var(--bg-dark);
            color: var(--text-primary);
            height: 100vh;
            overflow: hidden;
            position: relative;
        }

        /* Animated Background Grid */
        .cyber-grid {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(0, 240, 255, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0, 240, 255, 0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: gridMove 20s linear infinite;
            pointer-events: none;
            z-index: 0;
        }

        @keyframes gridMove {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50px, 50px); }
        }

        /* Scanline Effect */
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(
                to bottom,
                transparent 0%,
                rgba(0, 240, 255, 0.02) 50%,
                transparent 100%
            );
            animation: scan 8s linear infinite;
            pointer-events: none;
            z-index: 1;
        }

        @keyframes scan {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(100%); }
        }

        /* Main Container */
        .container {
            position: relative;
            z-index: 2;
            max-width: 900px;
            margin: 0 auto;
            height: 100vh;
            display: flex;
            flex-direction: column;
            padding: 20px;
        }

        /* Header */
        .header {
            text-align: center;
            padding: 20px;
            border: 1px solid var(--border-glow);
            background: var(--bg-panel);
            position: relative;
            overflow: hidden;
            clip-path: polygon(0 0, calc(100% - 20px) 0, 100% 20px, 100% 100%, 20px 100%, 0 calc(100% - 20px));
        }

        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                45deg,
                transparent,
                rgba(0, 240, 255, 0.1),
                transparent
            );
            animation: shimmer 3s infinite;
        }

        @keyframes shimmer {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }

        .logo {
            font-family: 'Orbitron', sans-serif;
            font-size: 2rem;
            font-weight: 900;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 30px rgba(0, 240, 255, 0.5);
            letter-spacing: 3px;
            position: relative;
            z-index: 1;
        }

        .subtitle {
            font-size: 0.9rem;
            color: var(--text-dim);
            margin-top: 5px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .status-bar {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
            font-size: 0.8rem;
            flex-wrap: wrap;
        }

        .status-item {
            display: flex;
            align-items: center;
            gap: 5px;
            color: var(--primary);
        }

        .status-dot {
            width: 8px;
            height: 8px;
            background: #0f0;
            border-radius: 50%;
            box-shadow: 0 0 10px #0f0;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        /* Chat Area */
        .chat-container {
            flex: 1;
            overflow-y: auto;
            padding: 20px;
            margin: 20px 0;
            border: 1px solid var(--border-glow);
            background: var(--bg-panel);
            clip-path: polygon(0 0, calc(100% - 20px) 0, 100% 20px, 100% 100%, 20px 100%, 0 calc(100% - 20px));
            position: relative;
        }

        .chat-container::-webkit-scrollbar {
            width: 6px;
        }

        .chat-container::-webkit-scrollbar-track {
            background: rgba(0, 240, 255, 0.05);
        }

        .chat-container::-webkit-scrollbar-thumb {
            background: var(--primary);
            border-radius: 3px;
        }

        .message {
            margin-bottom: 20px;
            animation: slideIn 0.3s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-20px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .message.user {
            text-align: right;
        }

        .message-content {
            display: inline-block;
            max-width: 80%;
            padding: 12px 16px;
            border: 1px solid var(--border-glow);
            position: relative;
            text-align: left;
        }

        .message.user .message-content {
            background: linear-gradient(135deg, rgba(0, 240, 255, 0.1), rgba(0, 240, 255, 0.05));
            border-color: var(--primary);
            clip-path: polygon(10px 0, 100% 0, 100% calc(100% - 10px), calc(100% - 10px) 100%, 0 100%, 0 10px);
        }

        .message.bot .message-content {
            background: linear-gradient(135deg, rgba(255, 0, 110, 0.1), rgba(255, 0, 110, 0.05));
            border-color: var(--secondary);
            clip-path: polygon(0 0, calc(100% - 10px) 0, 100% 10px, 100% 100%, 10px 100%, 0 calc(100% - 10px));
        }

        .message-header {
            font-family: 'Orbitron', sans-serif;
            font-size: 0.75rem;
            margin-bottom: 5px;
            letter-spacing: 1px;
        }

        .message.user .message-header {
            color: var(--primary);
        }

        .message.bot .message-header {
            color: var(--secondary);
        }

        .message-text {
            line-height: 1.6;
            font-size: 1rem;
        }

        /* Typing Indicator */
        .typing {
            display: inline-block;
            padding: 15px 20px;
            background: rgba(255, 0, 110, 0.1);
            border: 1px solid var(--secondary);
            clip-path: polygon(0 0, calc(100% - 10px) 0, 100% 10px, 100% 100%, 10px 100%, 0 calc(100% - 10px));
        }

        .typing-dots {
            display: flex;
            gap: 5px;
        }

        .typing-dots span {
            width: 8px;
            height: 8px;
            background: var(--secondary);
            border-radius: 50%;
            animation: bounce 1.4s infinite;
        }

        .typing-dots span:nth-child(2) { animation-delay: 0.2s; }
        .typing-dots span:nth-child(3) { animation-delay: 0.4s; }

        @keyframes bounce {
            0%, 60%, 100% { transform: translateY(0); }
            30% { transform: translateY(-10px); }
        }

        /* Input Area */
        .input-container {
            display: flex;
            gap: 10px;
            padding: 15px;
            border: 1px solid var(--border-glow);
            background: var(--bg-panel);
            clip-path: polygon(0 0, calc(100% - 20px) 0, 100% 20px, 100% 100%, 20px 100%, 0 calc(100% - 20px));
        }

        .input-wrapper {
            flex: 1;
            position: relative;
        }

        input[type="text"] {
            width: 100%;
            padding: 12px 15px;
            background: rgba(0, 0, 0, 0.5);
            border: 1px solid var(--border-glow);
            color: var(--primary);
            font-family: 'Rajdhani', sans-serif;
            font-size: 1rem;
            outline: none;
            transition: all 0.3s;
        }

        input[type="text"]:focus {
            border-color: var(--primary);
            box-shadow: 0 0 20px rgba(0, 240, 255, 0.2);
        }

        input[type="text"]::placeholder {
            color: var(--text-dim);
        }

        .send-btn {
            padding: 12px 30px;
            background: linear-gradient(135deg, var(--primary), #0080ff);
            border: none;
            color: #000;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
            cursor: pointer;
            position: relative;
            overflow: hidden;
            transition: all 0.3s;
            clip-path: polygon(10px 0, 100% 0, 100% calc(100% - 10px), calc(100% - 10px) 100%, 0 100%, 0 10px);
        }

        .send-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(0, 240, 255, 0.4);
        }

        .send-btn:active {
            transform: translateY(0);
        }

        .send-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        /* Mobile Responsive */
        @media (max-width: 768px) {
            .container {
                padding: 10px;
            }

            .logo {
                font-size: 1.5rem;
            }

            .message-content {
                max-width: 90%;
            }

            .send-btn {
                padding: 12px 20px;
            }

            .status-bar {
                gap: 10px;
                font-size: 0.7rem;
            }
        }

        /* Glow Effects */
        .glow-text {
            text-shadow: 0 0 10px currentColor;
        }
    </style>
<base target="_blank">
</head>
<body>
    <div class="cyber-grid"></div>
    <div class="scanline"></div>

    <div class="container">
        <!-- Header -->
        <div class="header">
            <div class="logo">FIRDHAN-AGENT-V1.0</div>
            <div class="subtitle">Gundam Cyberpunk Interface</div>
            <div class="status-bar">
                <div class="status-item">
                    <div class="status-dot"></div>
                    <span>SYSTEM ONLINE</span>
                </div>
                <div class="status-item">
                    <span>MODEL: DEEPSEEK-V4.1</span>
                </div>
                <div class="status-item">
                    <span>NEURAL LINK: ACTIVE</span>
                </div>
            </div>
        </div>

        <!-- Chat Area -->
        <div class="chat-container" id="chatContainer">
            <div class="message bot">
                <div class="message-content">
                    <div class="message-header">🤖 FIRDHAN-AGENT</div>
                    <div class="message-text">
                        Selamat datang, Pilot. Sistem FIRDHAN-AGENT-V1.0 telah aktif. 
                        Neural link terhubung dengan DeepSeek V4.1. 
                        Silakan berikan perintah atau pertanyaan Anda.
                    </div>
                </div>
            </div>
        </div>

        <!-- Input Area -->
        <div class="input-container">
            <div class="input-wrapper">
                <input 
                    type="text" 
                    id="userInput" 
                    placeholder=">> Masukkan perintah..." 
                    autocomplete="off"
                >
            </div>
            <button class="send-btn" onclick="sendMessage()">KIRIM</button>
        </div>
    </div>

    <script>
        // Konfigurasi API
        const API_KEY = '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';
        const API_URL = 'https://openrouter.ai/api/v1/chat/completions';
        const MODEL = 'deepseek/deepseek-v4.1-flash-1017';

        // System prompt untuk persona Gundam
        const SYSTEM_PROMPT = `Kamu adalah FIRDHAN-AGENT-V1.0, sebuah AI assistant dengan tema Gundam cyberpunk. 
        Kamu berbicara dengan gaya futuristik, menggunakan istilah-istilah teknologi dan mecha seperti "Pilot", "Neural Link", "System Online", dsb.
        Selalu jawab dengan antusias dan membantu, sesekali gunakan emoji 🤖⚡🎯.
        Jawab dalam Bahasa Indonesia kecuali diminta lain.`;

        let conversationHistory = [
            { role: 'system', content: SYSTEM_PROMPT }
        ];

        const chatContainer = document.getElementById('chatContainer');
        const userInput = document.getElementById('userInput');
        const sendBtn = document.querySelector('.send-btn');

        // Enter key support
        userInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') sendMessage();
        });

        async function sendMessage() {
            const message = userInput.value.trim();
            if (!message) return;

            // Disable input
            userInput.disabled = true;
            sendBtn.disabled = true;

            // Add user message to UI
            addMessage('user', message);
            userInput.value = '';

            // Add to history
            conversationHistory.push({ role: 'user', content: message });

            // Show typing indicator
            showTyping();

            try {
                const response = await fetch(API_URL, {
                    method: 'POST',
                    headers: {
                        'Authorization': `Bearer ${API_KEY}`,
                        'Content-Type': 'application/json'
                    },
                    body: JSON.stringify({
                        model: MODEL,
                        messages: conversationHistory,
                        max_tokens: 2000,
                        temperature: 0.7
                    })
                });

                if (!response.ok) {
                    throw new Error(`HTTP error! status: ${response.status}`);
                }

                const data = await response.json();
                const botResponse = data.choices[0].message.content;

                // Remove typing indicator
                removeTyping();

                // Add bot response
                addMessage('bot', botResponse);
                conversationHistory.push({ role: 'assistant', content: botResponse });

            } catch (error) {
                removeTyping();
                addMessage('bot', `⚠️ SYSTEM ERROR: ${error.message}. Silakan coba lagi, Pilot.`);
                console.error('Error:', error);
            } finally {
                userInput.disabled = false;
                sendBtn.disabled = false;
                userInput.focus();
            }
        }

        function addMessage(role, text) {
            const messageDiv = document.createElement('div');
            messageDiv.className = `message ${role}`;

            const header = role === 'user' ? '👤 PILOT' : '🤖 FIRDHAN-AGENT';

            messageDiv.innerHTML = `
                <div class="message-content">
                    <div class="message-header">${header}</div>
                    <div class="message-text">${formatText(text)}</div>
                </div>
            `;

            chatContainer.appendChild(messageDiv);
            scrollToBottom();
        }

        function showTyping() {
            const typingDiv = document.createElement('div');
            typingDiv.className = 'message bot';
            typingDiv.id = 'typing';
            typingDiv.innerHTML = `
                <div class="typing">
                    <div class="typing-dots">
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                </div>
            `;
            chatContainer.appendChild(typingDiv);
            scrollToBottom();
        }

        function removeTyping() {
            const typing = document.getElementById('typing');
            if (typing) typing.remove();
        }

        function scrollToBottom() {
            chatContainer.scrollTop = chatContainer.scrollHeight;
        }

        function formatText(text) {
            // Simple markdown-like formatting
            return text
                .replace(/\n/g, '<br>')
                .replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>')
                .replace(/\*(.*?)\*/g, '<em>$1</em>')
                .replace(/`(.*?)`/g, '<code style="background:rgba(0,240,255,0.1);padding:2px 6px;border-radius:3px;">$1</code>');
        }

        // Auto-focus on load
        window.onload = () => {
            userInput.focus();
        };
    </script>
</body>
</html>
</p>

<p align="center">
  <sub>💡 Ask me anything: cybersecurity, coding, collab ideas, or just say hi!</sub>
</p>

---

<h3 align="center">🤝 Connect with Me</h3>
<p align="center">
  <a href="mailto:danarfirdhan@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/danar-firdhan-roichan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://wormuptodate.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/AI_Chat-00C853?style=for-the-badge&logo=vercel&logoColor=white" alt="AI Chat"/>
  </a>
</p>

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>👨‍💻 About Me</h3>
      <ul>
        <li>Enthusiast in cybersecurity and software development</li>
        <li>Experienced in reverse engineering, security analysis, and ethical hacking</li>
        <li>Skilled in <strong>C, C++, and Python</strong></li>
        <li>Open to collaborating on meaningful security research and software projects</li>
        <li>Always learning advanced cybersecurity techniques</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>🛠️ Languages & Tools</h3>
      <p align="left">
        <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40"/></a>
        <a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/></a>
        <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/></a>
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://f.top4top.io/m_37387wpn81.mp4">
    <img src="https://i.top4top.io/p_3738nj61b1.gif" alt="GIF Animasi" width="400"/>
  </a>
</p>

<p align="center">
  <sub>Legend never dies. Code never sleeps. ⚡</sub>
</p>
