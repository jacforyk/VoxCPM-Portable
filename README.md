# VoxCPM-Portable
High-quality voice cloning software for multi-person dialogue synthesis.

It inherently understands contextual nuances, generating appropriate emotions and pauses straight from your text without complex phoneme tagging. It has been trained on over 2 million hours of multi-lingual data, natively supporting **30 languages** (including English, French, German, Japanese, Korean, Spanish, and many more).

### ✨ Core Features & Exclusive Upgrades

**1. Base Capabilities: Zero-Shot Cloning & Voice Design**
* **Voice Cloning:** Provide a clean, few-second reference audio clip, and the model flawlessly replicates the speaker’s unique voice. You can even use text prompts to adjust speed and emotion.
* **Voice Design:** No reference audio? Simply describe your ideal voice in natural language (e.g., *"A young woman with a soft and sweet voice"*), and the model will generate a customized voice from scratch.
* **Context-Aware:** The model automatically infers the correct tone and inflection based on your text's context (e.g., questions, exclamations, or sad dialogue) without any explicit prompts needed.

**2. 🔥 Exclusive Addition: Multi-Speaker Dialogue Synthesis**
*The Pain Point:* The original model only generates one speaker at a time. If you are creating audiobooks, podcasts, or story videos, manually switching voices and splicing audio in a video editor is incredibly time-consuming.
*The Solution:* I have integrated a powerful script-parsing feature directly into the frontend UI.
* **How it works:** Input your script using simple speaker tags (e.g., `[sp1] Hello! \n [sp2] Hi, long time no see!`). Upload a reference audio for each specific speaker.
* **The Result:** The software automatically slices the script, synthesizes each character's lines using the underlying model, and seamlessly merges them into a single, complete multi-speaker audio file, greatly boosting your workflow efficiency.

### 🛠️ How to Use (One-Click Portable)
This is a portable package—no complex installation or environment configuration required!

1.  Download and extract the archive into a folder with a **strictly English path**.
2.  Double-click `Launch the software.exe` to initialize the background model (initial loading time depends on your disk and GPU speed).
3.  A visual Web UI will automatically open in your browser.

<img width="820" height="343" alt="image" src="https://github.com/user-attachments/assets/561bee0f-077f-452c-bcf0-2b6fc787e167" />


**Single-Speaker Modes:**
* **🎨 Voice Design:** Describe the target voice (gender, age, tone, speed) in the *Control Instruction* field to create a voice from scratch.
* **🎛️ Controllable Cloning:** Upload reference audio and optionally use *Control Instructions* to dictate emotion and pacing while preserving the original voice signature.
* **🎙️ Ultimate Cloning:** Turn on "Ultimate Cloning Mode" and provide the transcript of your reference audio. The model treats this as continuous speech, perfectly replicating every audio detail for the subsequent text. *(Note: This disables Control Instructions).*
* *Pro-Tip for Emotions:* When controlling emotion within your text, always use English parentheses `()`. Example: `(terrified) Did you really... never feel anything for me?`

<img width="820" height="396" alt="image" src="https://github.com/user-attachments/assets/bdcd56e7-e61a-4c6e-b6b3-5485370d3988" />


**Multi-Speaker Mode:**
* Supports up to 5 unique speakers at once.
* Upload reference audios sequentially on the left (1st is `[sp1]`, 2nd is `[sp2]`, etc.).
* Format your script on the right, one line per speaker:
    ```text
    [sp1] Hello there.
    [sp2] Hi, nice to meet you!
    [sp1] Let's test the multi-speaker synthesis.
    ```

### ⚠️ Important Requirements & Notes
* **Hardware:** NVIDIA GPU with at least **6GB VRAM**. Please ensure your NVIDIA graphics drivers are up to date.
* **OS:** Windows 10 or 11.
* **Path Warning:** Ensure your extraction path contains **NO spaces, NO special characters, and NO non-English characters**. Failing to do this is the most common reason the program will fail to locate the necessary files.
* **Ethical Use:** Please use the voice cloning features responsibly and within legal boundaries. Do not clone unauthorized voices for illegal, infringing, or fraudulent purposes.

## VoxCPM Multi-Speaker TTS Tool Download Link

https://www.patreon.com/posts/156494916
