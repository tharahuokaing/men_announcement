// =================================================================
// MATRIX CANVAS BACKGROUND (Streaming SENG CHHAT, MEN & HUOKAING THARA)
// =================================================================
(function initHUOKAINGTHARABackground() {
  const canvas = document.getElementById('hologram-canvas');
  if (!canvas) return;
  const ctx = canvas.getContext('2d');

  function resize() {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  }
  resize();
  window.addEventListener('resize', resize);

  const phrase = "HUOKAING THARA BANK ISP SENG CHHAT MEN CEO DIRECTOR CYBERSECURITY ";
  const fontSize = 16;
  const columns = Math.floor(canvas.width / fontSize);
  const drops = Array(columns).fill(1);
  const charOffsets = Array.from({ length: columns }, () => Math.floor(Math.random() * phrase.length));

  function drawMatrix() {
    ctx.fillStyle = 'rgba(3, 7, 18, 0.15)';
    ctx.fillRect(0, 0, canvas.width, canvas.height);

    ctx.fillStyle = '#00f0ff';
    ctx.font = fontSize + 'px monospace';

    for (let i = 0; i < drops.length; i++) {
      const charIndex = (charOffsets[i] + drops[i]) % phrase.length;
      const text = phrase[charIndex];
      ctx.fillText(text, i * fontSize, drops[i] * fontSize);

      if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
        drops[i] = 0;
      }
      drops[i]++;
    }
  }
  setInterval(drawMatrix, 40);
})();

// =================================================================
// AI VOICE PRESENTATION ENGINE (Updated with CEO Mr. Men)
// =================================================================
const announcementSpeech = [
  {
    langCode: 'km',
    langName: 'Khmer',
    locale: 'km-KH',
    lines: [
      "សេចក្តីប្រកាសព័ត៌មានផ្លូវការ ពីលោក ហួរ និងគណៈគ្រប់គ្រង ធនាគារ ហួកាំង ថារ៉ា។",
      "អំពីការបើកដំណើរការ ធនាគារ ហួកាំង ថារ៉ា និង ហួកាំង ថារ៉ា អាយអេសភី ជាផ្លូវការ។",
      "លោក ម៉ែន ត្រូវបានតែងតាំងជា នាយកប្រតិបត្តិ ឬ ស៊ីអ៊ីអូ។",
      "លោក សេង ឆាត់ ត្រូវបានតែងតាំងជា នាយក។",
      "លោក ហួកាំង ថារ៉ា ត្រូវបានតែងតាំងជា ប្រធានផ្នែកសន្តិសុខសុវត្ថិភាពឌីជីថល និងប្រធានផ្នែកទីផ្សារ។",
      "ក្រុមហ៊ុន ហួកាំង ថារ៉ា ប្តេជ្ញាផ្តល់ជូននូវសេវាកម្មអុីនធើណេត និងប្រព័ន្ធធនាគារដែលមានសុវត្ថិភាពខ្ពស់បំផុត។"
    ]
  },
  {
    langCode: 'en',
    langName: 'English',
    locale: 'en-US',
    lines: [
      "Official announcement decided by Mr. HUO and the executive management of HUOKAING THARA BANK.",
      "Regarding the upcoming grand launch of HUOKAING THARA BANK and HUOKAING THARA ISP.",
      "Mr. MEN is appointed as Chief Executive Officer, or CEO.",
      "Mr. SENG CHHAT is appointed as Director.",
      "Mr. HUOKAING THARA is appointed as Chief Cybersecurity Officer and Head of Marketing.",
      "HUOKAING THARA is committed to providing secure internet and digital banking services."
    ]
  }
];

let currentLangIdx = 0;
let currentLineIdx = 0;
let isVoiceActive = false;

function highlightActiveButton(langCode) {
  document.querySelectorAll('.voice-btn').forEach(btn => {
    if (btn.getAttribute('onclick')?.includes(`'${langCode}'`)) {
      btn.classList.add('active');
    } else {
      btn.classList.remove('active');
    }
  });
}

function speakNextLine() {
  if (!isVoiceActive || !('speechSynthesis' in window)) return;

  const currentLangObj = announcementSpeech[currentLangIdx];

  if (currentLineIdx >= currentLangObj.lines.length) {
    currentLineIdx = 0;
    currentLangIdx = (currentLangIdx + 1) % announcementSpeech.length;
    setTimeout(() => { speakNextLine(); }, 1000);
    return;
  }

  const lineText = currentLangObj.lines[currentLineIdx];
  const transcriptEl = document.getElementById('voice-transcript');
  if (transcriptEl) {
    transcriptEl.textContent = `[${currentLangObj.langName.toUpperCase()}] ${lineText}`;
  }
  highlightActiveButton(currentLangObj.langCode);

  const utterance = new SpeechSynthesisUtterance(lineText);
  utterance.lang = currentLangObj.locale;
  utterance.rate = 0.95;

  utterance.onend = function() {
    currentLineIdx++;
    if (isVoiceActive) setTimeout(speakNextLine, 350);
  };

  utterance.onerror = function() {
    currentLineIdx++;
    if (isVoiceActive) setTimeout(speakNextLine, 350);
  };

  speechSynthesis.speak(utterance);
}

function startSequentialPresentation(langCode) {
  if (!('speechSynthesis' in window)) {
    alert("Speech Synthesis API is not supported on this browser.");
    return;
  }
  speechSynthesis.cancel();
  isVoiceActive = true;

  const targetIdx = announcementSpeech.findIndex(p => p.langCode === langCode);
  currentLangIdx = targetIdx !== -1 ? targetIdx : 0;
  currentLineIdx = 0;

  speakNextLine();
}

function stopVoiceAI() {
  isVoiceActive = false;
  if ('speechSynthesis' in window) speechSynthesis.cancel();
  highlightActiveButton(null);
  const transcriptEl = document.getElementById('voice-transcript');
  if (transcriptEl) {
    transcriptEl.textContent = "Voice reader stopped by user command.";
  }
}

// =================================================================
// COUNTDOWN TIMER (1 Year Target Timeline)
// =================================================================
const grandOpeningDate = Date.now() + (365 * 24 * 60 * 60 * 1000);
function updateCountdown() {
  const diff = grandOpeningDate - Date.now();
  const countdownEl = document.getElementById('countdown');
  if (!countdownEl) return;

  if (diff <= 0) {
    countdownEl.textContent = "GRAND OPENING ACTIVE!";
    return;
  }
  const days = Math.floor(diff / (1000 * 60 * 60 * 24));
  const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
  const seconds = Math.floor((diff % (1000 * 60)) / 1000);

  countdownEl.textContent = `${days}d ${hours}h ${minutes}m ${seconds}s`;
}
updateCountdown();
setInterval(updateCountdown, 1000);

// =================================================================
// LIVE TELEMETRY BROADCAST FEED (Includes CEO Mr. Men)
// =================================================================
const feedList = document.getElementById("feed-list");
if (feedList) {
  setInterval(() => {
    const logs = [
      "CEO APPOINTED: Mr. MEN assigned Chief Executive Officer of Corporate Strategy.",
      "DIRECTOR APPOINTED: Mr. SENG CHHAT assigned Director of Corporate Operations.",
      "APPOINTMENT VERIFIED: Mr. HUOKAING THARA assigned Chief Cybersecurity Officer & Head of Marketing.",
      "EXECUTIVE DECREE: Signed by Mr. HUO & Board of Directors of HUOKAING THARA BANK.",
      "SECURITY MATRIX: Cyber defense and digital banking encryption initialized."
    ];
    const randomLog = logs[Math.floor(Math.random() * logs.length)];
    const item = document.createElement("li");
    item.innerHTML = `<span style="color:var(--neon-gold)">[${new Date().toLocaleTimeString()}]</span> <strong>${randomLog}</strong>`;
    feedList.insertBefore(item, feedList.firstChild);
    if (feedList.children.length > 5) feedList.removeChild(feedList.lastChild);
  }, 4500);
}

// =================================================================
// SECURITY PROTECTIONS
// =================================================================
document.addEventListener('contextmenu', e => { e.preventDefault(); return false; });
document.addEventListener('keydown', e => {
  if (['F12', 'KeyI', 'KeyU', 'KeyS'].includes(e.code) || (e.ctrlKey && ['u','s','i'].includes(e.key))) {
    e.preventDefault();
    return false;
  }
}, true);
