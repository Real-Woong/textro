📄 Textro — Local PDF Text Extraction Tool (Tesseract OCR)

🇺🇸 English

Overview

Textro is a local PDF text extraction tool powered by Tesseract OCR, designed to reduce inefficient manual retyping of documents in administrative and public-sector workflows.

Many organizations still receive documents as scanned PDFs or image-based files, which require staff to manually retype the contents into digital systems.

Textro automates this process by detecting the type of PDF and applying the appropriate extraction method.

The system supports both:
	•	Text-based PDFs — direct text extraction
	•	Scanned image PDFs — OCR-based extraction using Tesseract OCR

All processing is performed entirely on the local machine, ensuring that no documents are transmitted externally.

This design makes the tool suitable for security-sensitive environments such as government agencies, public institutions, and internal administrative systems.

⸻

Key Notes
	•	Tesseract OCR-based text recognition
	•	Handles both text PDFs and scanned PDFs
	•	Fully local execution (no cloud services)
	•	Output format: TXT only
	•	Designed and tested on macOS
	•	Repository contains Python source code only
	•	No packaged executable included

⸻

Technical Scope
	•	Language: Python
	•	PDF Processing: PyMuPDF
	•	OCR Engine: Tesseract OCR (local)
	•	Image Preprocessing: Pillow
	•	Platform: macOS
	•	Output Format: Plain text (.txt)

This project intentionally avoids cloud-based OCR services and focuses on secure local processing using Tesseract OCR.

⸻

🇰🇷 한국어

개요

Textro는 Tesseract OCR 기반의 로컬 PDF 텍스트 추출 도구로,
행정 및 공공기관 업무에서 발생하는 문서 수기 타이핑 작업을 줄이기 위해 개발된 프로젝트입니다.

많은 공공기관 및 행정 환경에서는
스캔된 PDF 문서나 이미지 기반 문서를 시스템에 입력하기 위해
직접 내용을 다시 타이핑해야 하는 비효율적인 작업이 발생합니다.

Textro는 PDF 유형을 자동으로 판단하여 다음과 같이 처리합니다.
	•	텍스트 기반 PDF → 직접 텍스트 추출
	•	스캔된 이미지 PDF → Tesseract OCR 기반 텍스트 인식

모든 처리는 로컬 환경에서만 수행되며,
외부 서버나 클라우드 API를 사용하지 않습니다.

따라서 보안 요구사항이 높은 공공기관 및 내부 행정 환경에서도 사용할 수 있도록 설계되었습니다.

⸻

주요 특징
	•	Tesseract OCR 기반 텍스트 인식
	•	텍스트 PDF와 스캔 PDF 자동 처리
	•	완전한 로컬 실행 (클라우드 사용 없음)
	•	출력 형식: TXT 파일
	•	macOS 환경에서 개발 및 테스트
	•	본 저장소에는 Python 소스 코드만 포함
	•	실행 파일(PyInstaller 등)은 포함되어 있지 않음

⸻

기술 스택
	•	언어: Python
	•	PDF 처리: PyMuPDF
	•	OCR 엔진: Tesseract OCR (로컬)
	•	이미지 전처리: Pillow
	•	플랫폼: macOS
	•	출력 형식: Plain text (.txt)

이 프로젝트는 클라우드 OCR 서비스를 사용하지 않고
Tesseract OCR을 기반으로 로컬 환경에서 안전하게 문서를 처리하는 워크플로우를 구현하는 데 목적이 있습니다.
