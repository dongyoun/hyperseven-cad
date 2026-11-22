# 하이퍼세븐 캐드 · HyperSeven CAD

도면부터 BIM까지, 하나의 모델로. DWG·SKP·3DM·IFC 파일을 오가던 작업을 한 화면에서 이어 가는 캐드입니다. 모든 기능을 무료로 씁니다. 하이퍼세븐(HyperSeven)은 히스테리시스(HYSTERESIS)의 제품입니다.

- 홈페이지: https://hypersevenlabs.com/cad
- 설치: 지금 판은 **1.3.7**입니다. 맥(Apple Silicon·인텔)과 윈도우 zip 은 이 저장소의 [Releases](../../releases)에 있습니다. 윈도우는 [Microsoft Store](https://apps.microsoft.com/detail/9N3V14L2F5MW)에서도 받습니다 — 스토어는 심사를 거쳐 조금 늦게 새 판으로 바뀝니다.
- 문의·버그 알리기: [Issues](../../issues), 또는 앱 안 **도움말 → 불편 신고(⌘⇧F)**
- 회사·기관·단체 맞춤 도입, 후원·투자 문의: hypersevenlabs@gmail.com (자세히: https://hypersevenlabs.com/business)

이 저장소에는 설치 파일만 있습니다.

## 해 볼 것

- 시작 화면의 **예제 둘러보기**: 마을 도서관과 도면 시트, 열주 미술관, 중정 주택, 벽돌 주택, 핀 파사드 오피스, 곡면 지붕 파빌리온, 기계 부품도, 가구·그릇·지형 등 16 가지.
- DWG·DXF·SKP·3DM·RVT·IFC·PDF 등을 끌어다 놓아 엽니다. DWG·DXF 는 층·종이 공간·유형 표·블록을 그대로 되씁니다.
- 익숙한 명령 이름과 단축키를 씁니다. 키 방식은 설정에서 고릅니다. 한글로도 찾을 수 있습니다(⌘K).
- AI 와 함께 씁니다. 앱 안의 하이퍼 AI 는 로그인하고 내 Anthropic API 키를 연결하면 쓸 수 있습니다. Claude 같은 에이전트를 MCP 로 연결할 수도 있습니다(아래).

## AI 에이전트 연결(MCP)

앱에 MCP 서버가 들어 있습니다. 맥에서 Claude Code 에 붙이려면:

```bash
claude mcp add hyperseven-cad -- "/Applications/HyperSeven CAD.app/Contents/MacOS/supercad" mcp
```

윈도우와 다른 에이전트의 설정은 앱의 AI 탭 '연결 방법'에 있습니다. 앱 창이 떠 있으면 에이전트가 그 창의 문서를 사람이 보는 앞에서 고칩니다. 에이전트가 바꾼 것은 제안(보라)으로 남고, 사람이 받거나 버립니다.

## 문제·불편 알림

앱은 처음 쓸 때 한 번 묻습니다. 오류가 나거나 막힌 순간(찾았는데 없는 명령, 바로 되돌린 명령 같은 것)을 **도면 내용 없이** 자동으로 알려도 되는지입니다.
- 동의하면 판·운영체제·최근 명령 이름·오류 글(경로는 지움)·횟수만 보냅니다.
- 도면 내용·파일 이름·경로는 보내지 않습니다.
- 설정 → 일반 → 함께 고치기에서 언제든 끄고, 보내는 내용을 볼 수 있습니다.

AutoCAD·Revit 은 Autodesk, SketchUp 은 Trimble, Rhino·Grasshopper 는 Robert McNeel & Associates, Archicad 는 Graphisoft 의 상표입니다. 하이퍼세븐 캐드는 이 회사들과 관계가 없습니다.
