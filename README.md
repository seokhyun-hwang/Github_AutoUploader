# ✨ Github 업로드 딸깍! ✨

### 🖱️ GitHub 자동 동기화 프로그램 🖱️

> **복잡한 Git 명령어는 이제 그만! 👋**
> <br> GUI로 간편하게 파일을 관리하고, 자동으로 잔디를 심어주는 강력한 데스크톱 애플리케이션
> <br>
> **Developed by. 딸깍눌러조** ([HARMAN]python_project)

<br>

| Category | Stack |
| :--- | :--- |
| **APPLICATION** | ![Desktop App](https://img.shields.io/badge/Desktop_Application-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) |
| **LANGUAGE** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **GUI LIB** | ![Tkinter](https://img.shields.io/badge/Tkinter-GUI-blue?style=for-the-badge) ![ttkbootstrap](https://img.shields.io/badge/ttkbootstrap-Theme-success?style=for-the-badge) |
| **CORE** | ![GitPython](https://img.shields.io/badge/GitPython-Automation-F05032?style=for-the-badge&logo=git&logoColor=white) ![Requests](https://img.shields.io/badge/Requests-API-orange?style=for-the-badge) |

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/29f09aa8-ae8e-4cbe-bbbd-fd2ead800d9a" width="90%" alt="메인 실행 화면" />
</div>

<br>

## 📖 프로젝트 소개

**"Github 업로드 딸깍!"** 은 로컬 컴퓨터의 특정 폴더를 깃허브 저장소와 실시간으로 동기화하여 파일 관리를 자동화해주는 프로그램입니다.

코딩에 집중하기도 바쁜데 Git 명령어까지 신경 쓰기 힘드셨죠? 이 프로그램을 사용하면 파일을 저장하는 순간 자동으로 깃허브에 업로드됩니다. 초보자도 쉽게 본인의 GitHub에 자료를 정리하고, 매일매일 잔디를 심는 즐거움을 느낄 수 있습니다.

<br>

## 🚀 주요 기능 (Key Features)

### 1️⃣ 🔄 실시간 양방향 동기화
더 이상 수동으로 `add`, `commit`, `push`를 할 필요가 없습니다.

* **자동 업로드:** 지정된 로컬 폴더에 파일을 추가하거나 수정하면, 별도의 작업 없이 자동으로 감지하여 깃허브 저장소에 업로드합니다.
* **안전한 삭제 (휴지통):** 로컬 폴더에서 파일을 삭제하면 깃허브에서 영구 삭제하는 대신 `_recycle_bin` 폴더로 이동시켜, 실수로 인한 파일 유실을 방지합니다.
* **초기 동기화:** 프로그램 시작 시 로컬 폴더를 기준으로 깃허브 저장소를 정리(로컬에 없는 파일은 휴지통으로, 로컬에만 있는 파일은 업로드)하여 상태를 일치시킵니다.

### 2️⃣ ⚙️ 사용자 친화적 GUI
직관적인 제어판과 다양한 편의 기능을 제공합니다.

* **직관적인 제어판:** '동기화 & 업로드 시작', '업로드 종료' 버튼으로 동기화 프로세스를 쉽게 제어할 수 있습니다.
* **상세 설정 창:** 깃허브 토큰, 사용자 이름, 저장소, 브랜치, 감시 폴더 등 모든 설정을 UI를 통해 관리하고 `config.json`에 영구 저장합니다. (토큰은 별도 보안 저장)
* **실시간 로그 뷰어:** 파일이 처리되는 모든 과정을 실시간 로그로 확인할 수 있어, 프로그램의 동작 상태를 명확히 파악할 수 있습니다.
* **다양한 UI 테마:** `ttkbootstrap`을 활용하여 사용자가 원하는 여러 가지 UI 테마를 선택할 수 있습니다.

### 3️⃣ 🧩 플러그인: 백준 문제 찾기
알고리즘 공부를 돕는 강력한 부가 기능!

* **Solved.ac 연동:** 웹사이트의 Class별 문제 목록을 크롤링하여 보여주는 기능이 별도의 창으로 통합되어 있습니다.
* **즉시 바로가기:** 문제 목록에서 원하는 문제를 더블클릭하면 즉시 웹 브라우저의 새 탭으로 해당 문제 페이지를 열어줍니다.

<br>

## 📂 발표 자료 (Materials)

프로젝트 발표 자료는 아래 버튼을 클릭하여 확인하실 수 있습니다.

[![PDF Report](https://img.shields.io/badge/📄_PDF_Report-View_Document-FF0000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/seokhyun-hwang/files/blob/main/Github_AutoUploader.pdf)



<br>

## 🛠️ 기술 스택 (Tech Stack)

* **Language:** Python 3.x
* **GUI:** Tkinter, ttkbootstrap
* **Automation:** GitPython (Git Automation), Watchdog (File System Monitoring)
* **Network:** Requests (Solved.ac API)

<br>

---
Copyright ⓒ 2024 딸깍눌러조 All rights reserved.
