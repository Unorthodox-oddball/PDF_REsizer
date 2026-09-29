## 📄 PDF Dimension Resizer for OneNote

> **"원노트에 PDF를 넣으면 너무 커서 메모할 공간이 없나요?"**  
> 이 프로그램은 PDF의 물리적 페이지 크기(mm/inch)를 줄여, 원노트에서 여백을 확보할 수 있게 도와주는 포터블 도구입니다.

---

## 🧠 Origin: AI-Powered Vibe Coding
이 프로젝트는 **AI를 활용한 바이브 코딩(Vibe Coding)** 방식으로 제작되었습니다.  
전통적인 코딩 방식이 문법과 로직을 직접 하나하나 입력하는 것이라면, 이 프로젝트는 개발자의 아이디어(Vision)와 문제 해결을 위한 의도(Vibe)를 AI에게 전달하고, AI가 이를 구체적인 코드와 아키텍처로 구현해내는 현대적인 협업 방식을 따랐습니다.

- **Human**: 문제 정의, 아키텍처 설계 방향 제시, 최종 검증.
- **AI**: 로직 구현, 라이브러리 최적화, 배포 파일 빌드 자동화.

---

## 🚀 Problem Statement
OneNote에 PDF를 삽입할 때, 파일 용량(MB)이 작더라도 페이지 자체의 물리적 크기(예: A3 사이즈)가 너무 크면 화면을 가득 채워버립니다. 이로 인해 PDF 옆에 필기할 공간이 부족해지는 문제가 발생합니다.

## ✨ Key Features
- **Physical Resizing**: 파일 용량이 아닌, 페이지의 가로/세로 규격을 직접 축소합니다.
- **Layout Preserving**: `PyMuPDF`를 사용하여 텍스트와 이미지의 레이아웃을 유지하며 축소합니다.
- **GUI Interface**: 복잡한 명령어 없이 마우스 클릭만으로 사용 가능합니다.
- **Portable**: 파이썬 설치가 필요 없는 단일 `.exe` 파일로 제공됩니다.

---

## 🛠 Tech Stack
| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.10 |
| **Library** | PyMuPDF (fitz), Tkinter |
| **Packager** | PyInstaller |
| **Methodology** | AI-Powered Vibe Coding |

---

## 📥 How to Use (For Users)
1. **[Releases]** 섹션에서 최신 버전의 `PDF_Resizer_Portable.exe` 파일을 다운로드합니다.
2. 프로그램을 실행합니다.
3. 축소하고 싶은 PDF 파일을 선택합니다.
4. 축소 비율(예: 0.5 = 50% 크기)을 입력합니다.
5. 작업이 완료되면 원본 파일 이름 뒤에 `_small_50.pdf`와 같은 이름으로 저장됩니다.
6. 저장된 파일을 OneNote에 삽입하여 넉넉한 메모 공간을 확인하세요!

---

## 💻 Development Guide (For Developers)
이 프로젝트를 직접 빌드하고 싶다면 다음 단계를 따르세요.

1. **Clone the repository**
   
```bash
   git clone https://github.com/Unorthodox-oddball/PDF_REsizer.git
   cd pdf-dimension-resizer
   ```

2. **Set up Virtual Environment**
   
```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # Mac/Linux
   source venv/bin/activate
   ```

3. **Install Dependencies**
   
```bash
   pip install -r requirements.txt
   ```

4. **Build Executable**
   
```bash
   pip install pyinstaller
   pyinstaller --onefile --noconsole --name "PDF_Resizer_Portable" main.py
   ```

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
