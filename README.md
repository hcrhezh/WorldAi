# Create the full README.md content as a string
readme_content = """\
# WorldAi - Smart AI Assistant App

WorldAi is a smart AI-powered mobile assistant app built using Niotron.  
It supports voice/text input, Sinhala & English language, dark mode, and rewarded ads on generate.

---

## ⚡ Features
- AI Text Generation (powered by OpenAI)
- Voice Input and Output (Text-to-Speech)
- Sinhala & English language support
- Text Tools: Summarize, Translate, Rephrase
- Dark Mode user interface
- Rewarded Ads integration (Unity Ads)
- Exportable as APK / AAB

---

## 📸 Screenshots

| Result Display |
|----------------|
| ![Result](docs/ResultPageDesign.png) |

---

## 🚀 How to Build / Use

1. Clone this repository or download the `.aia` file  
2. Open [Niotron Builder](https://builder.niotron.com/)  
3. Import `WorldAi.aia` project  
4. Add your OpenAI API key inside the relevant variable  
5. Add your Unity Ads ID:
   - Game ID: `5840005`
   - Placement ID: `Rewarded_Android`
6. Build and export the app as APK or AAB

---

## 📁 Project Structure

WorldAi-Mobile-App/ ├── WorldAi.aia ├── README.md ├── docs/ │ └── ResultPageDesign.png └── assets/ ├── icons/ └── screenshots/

yaml



---

## 🙏 Credits
- Developed using [Niotron](https://niotron.com)
- Powered by [OpenAI API](https://openai.com/)
- Unity Ads for monetization
- Designed by hcrhezh

---

## 📄 License
This project is open-source and free to use under the MIT License.
"""

# Save to a file
readme_path = "/mnt/data/README.md"
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path

