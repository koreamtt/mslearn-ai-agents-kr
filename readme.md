# Develop AI Agents in Azure

The exercises in this repo are designed to provide you with a hands-on learning experience in which you'll explore common tasks that developers perform when building AI agents on Microsoft Azure.

> **Note**: To complete the exercises, you'll need an Azure subscription in which you have sufficient permissions and quota to provision the necessary Azure resources and generative AI models. If you don't already have one, you can sign up for an [Azure account](https://azure.microsoft.com/free). There's a free trial option for new users that includes credits for the first 30 days.

한국어 실습은 [이 저장소의 GitHub Pages 사이트](https://koreamtt.github.io/mslearn-ai-agents-kr/)에서 확인합니다.

## 한국어 사이트 구성

기존 Microsoft Learning Jekyll 테마와 문서 구조를 그대로 사용합니다. 별도의 웹 앱이나 배포 워크플로를 만들지 않고 GitHub Pages의 브랜치 게시 기능으로 제공합니다.

| 경로 | 역할 |
| --- | --- |
| `Instructions/` | 영문 원본: 개별 실습 10개와 워크숍 문서 25개 |
| `Instructions-kr/` | 동일한 구조의 한국어 번역본과 미디어 |
| `Labfiles/` | 실습용 Python 코드, 데이터 및 Azure 리소스 템플릿. 사이트에 복사하지 않으며 저장소를 복제하여 사용합니다. |
| `index.md` | 한국어 개별 실습과 워크숍 목록을 자동으로 생성하는 홈페이지 |
| `_config.yml` | 기존 Jekyll 테마, 조직 URL 및 저장소 경로 설정 |
| `tools/checks/` | 문서 메타데이터, 코드 블록, 링크 등의 정적 검사 |

### GitHub Pages 게시

- 공개 주소: <https://koreamtt.github.io/mslearn-ai-agents-kr/>
- 저장소: `koreamtt/mslearn-ai-agents-kr`
- 게시 원본: `main` 브랜치의 루트(`/`), **Deploy from a branch**
- `_config.yml`의 `url`: `https://koreamtt.github.io`
- `_config.yml`의 `baseurl`: `/mslearn-ai-agents-kr`
- `main`에 변경 사항을 푸시하면 GitHub Pages가 기존 Jekyll 사이트를 다시 빌드합니다.
- 한국어 개별 실습은 `Instructions-kr/Exercises/<파일명>.html`, 워크숍은 `Instructions-kr/Consolidated/<파일명>.html`로 제공됩니다.
- 기존 `workshop.html`, `explore.html`, `labs.json`은 영문 워크숍 보조 화면·데이터로 유지합니다. 한국어 학습의 진입점은 홈페이지입니다.

번역 기준과 검증 방법은 [한국어 번역 유지관리 지침](Instructions-kr/README.md), 정적 검사 명령은 [콘텐츠 검사 안내](tools/checks/README.md)를 참조합니다.

> **Note**: While you can complete these exercises on their own, they're designed to complement modules on [Microsoft Learn](https://learn.microsoft.com/training/paths/develop-ai-agents-azure/); in which you'll find a deeper dive into some of the underlying concepts on which these exercises are based.

If you choose to run the code from applications in this repository locally, it will require Python 3.13+.

## Reporting issues

If you encounter any problems in the exercises, please report them as **issues** in this repo.
