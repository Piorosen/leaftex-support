---
title: LeafTeX Privacy Policy
permalink: /privacy/
---

# LeafTeX Privacy Policy

_Last updated: 2026-10-07 (LeafTeX Pro)._

LeafTeX is a LaTeX editor for iPhone and iPad published by **JooHyoung Cha**.
Questions about this policy: [open an issue](https://github.com/Piorosen/leaftex-support/issues).

## Summary

LeafTeX has no user accounts, no analytics, no advertising and no tracking. The
developer of LeafTeX does not operate servers for the app and does not receive
your documents, API keys, tokens or usage data.

## Data stored on your device

- **Projects** are stored where you choose: in the app's folder on your device,
  in your iCloud Drive, or in folders you link from the Files app. A project
  copied from a Git repository or from an FTP, SFTP or SSH server is kept as a
  copy on your device. Typesetting (turning your LaTeX into PDF) happens
  entirely on your device.
- **API keys, Git tokens and server passwords or private keys** you choose to
  save are stored in your device's Keychain,
  are not included in backups to other devices and are not synced by iCloud
  Keychain.
- **Preferences** (editor settings, your AI data-sharing choices) are stored in
  the app's local settings. The identity keys of SSH servers you connected to
  and the state of each project's last server sync are stored in the app's
  private folder on the device.

## Data sent to third parties, only when you use these features

| Feature | What is sent | Sent to | Under |
|---|---|---|---|
| iCloud Drive projects | Your project files | Apple | Your Apple Account and Apple's Privacy Policy |
| Git sync | Your project files, commit messages, the name and email you set for commits, and your Git credentials | The Git server you configure (for example `github.com`) | That service's terms and privacy policy |
| FTP, SFTP and SSH projects | Your project files, your user name and password or key-based sign-in | The server you configure | The terms of whoever runs that server |
| AI assistant with a cloud provider | Your instructions, the selected text, an excerpt of the open file, and compile messages | The AI provider you choose: **Anthropic** (Claude) or **OpenAI** | That provider's API terms and privacy policy ([Anthropic](https://www.anthropic.com/legal/privacy), [OpenAI](https://openai.com/policies/privacy-policy)) |
| AI assistant with your own server | The same as above | The Ollama or OpenAI-compatible server at the address you enter | The terms of whoever runs that server |
| Downloading an on-device model | The name of the model you download (no text from your documents) | Hugging Face, which hosts the model files | [Hugging Face's privacy policy](https://huggingface.co/privacy) |

With an **on-device model** — Apple Intelligence's built-in model or a model
you download — the assistant runs entirely on your device: your text is not
sent anywhere. Downloaded models are stored in the app's private
storage and are not backed up.

For servers and cloud providers, the AI assistant asks for your explicit
permission before the first request (for a server, again whenever its address
changes) and sends requests directly from your device. Keys you enter are
yours and stay in the Keychain. You can revoke permissions and delete keys and
models at any time in **Settings › AI Assistant**. LeafTeX never sends your
whole project to an AI provider.

## Purchases

LeafTeX Pro is bought through the App Store. Apple handles the payment;
LeafTeX never sees your payment details. The app checks on your device,
with Apple's StoreKit, whether your Apple Account has LeafTeX Pro. The
developer receives only the sales reports Apple provides to developers,
which do not identify you.

## Children

LeafTeX is not directed at children and does not knowingly collect personal
information from anyone.

## Your choices

You can delete projects in the app or in the Files app, remove keys, tokens and
saved server logins in Settings, revoke AI data sharing in Settings, and stop
using iCloud Drive or Git sync at any time.

Deleting the app deletes the projects in its own folder, its settings and its
downloaded models; projects in iCloud Drive or in linked folders stay where
they are. iOS keeps Keychain items when an app is deleted: LeafTeX removes the
keys, tokens and passwords it saved when it is installed again and first
opened. To remove them right away, delete them in Settings before deleting the
app.

## Changes

We will update this page when the app's data practices change, and the app
will ask again before sending data to an AI provider under changed terms.

---

# LeafTeX 개인정보 처리방침

_최종 수정일: 2026-10-07._

LeafTeX는 **JooHyoung Cha**가 제공하는 iPhone·iPad용 LaTeX 편집기입니다.
이 방침에 대한 문의: [이슈 남기기](https://github.com/Piorosen/leaftex-support/issues).

## 요약

LeafTeX에는 회원 계정, 분석 도구, 광고, 추적이 없습니다. 개발자는 앱을 위한 서버를
운영하지 않으며 사용자의 문서, API 키, 토큰, 사용 기록을 받지 않습니다.

## 기기에 저장되는 정보

- **프로젝트**는 사용자가 고른 위치(기기 안 앱 폴더, 사용자의 iCloud Drive, Files 앱에서 연결한 폴더)에
  저장되며, Git 저장소나 FTP·SFTP·SSH 서버에서 가져온 프로젝트도 기기 안의 사본으로 보관합니다.
  LaTeX를 PDF로 조판하는 작업은 모두 기기 안에서 이루어집니다.
- 저장하기로 한 **API 키, Git 토큰, 서버 비밀번호와 개인 키**는 기기의 키체인에 저장되며 다른 기기로의 백업이나 iCloud 키체인 동기화에
  포함되지 않습니다.
- **설정**(편집기 설정, AI 데이터 공유 동의 여부)은 앱의 로컬 설정에 저장됩니다. 접속한 SSH 서버의 식별 키와
  프로젝트별 마지막 서버 동기화 상태는 기기 안 앱 전용 폴더에 저장됩니다.

## 기능을 사용할 때만 제3자에게 전송되는 정보

| 기능 | 전송 항목 | 수신자 | 적용 약관 |
|---|---|---|---|
| iCloud Drive 프로젝트 | 프로젝트 파일 | Apple | 사용자의 Apple 계정과 Apple 개인정보 처리방침 |
| Git 동기화 | 프로젝트 파일, 커밋 메시지, 커밋 작성자 이름/이메일, Git 자격 증명 | 사용자가 설정한 Git 서버(예: `github.com`) | 해당 서비스의 약관과 개인정보 처리방침 |
| FTP·SFTP·SSH 프로젝트 | 프로젝트 파일, 사용자 이름과 비밀번호 또는 키 기반 로그인 | 사용자가 설정한 서버 | 해당 서버 운영자의 약관 |
| AI 어시스턴트(클라우드 제공자) | 입력한 지시문, 선택한 텍스트, 열린 파일의 일부, 컴파일 메시지 | 사용자가 고른 AI 제공자: **Anthropic**(Claude) 또는 **OpenAI** | 해당 제공자의 API 약관과 개인정보 처리방침 |
| AI 어시스턴트(사용자의 서버) | 위와 같음 | 사용자가 입력한 주소의 Ollama 또는 OpenAI 호환 서버 | 해당 서버 운영자의 약관 |
| 온디바이스 모델 내려받기 | 내려받는 모델의 이름(문서 내용은 보내지 않음) | 모델 파일을 제공하는 Hugging Face | [Hugging Face 개인정보 처리방침](https://huggingface.co/privacy) |

**온디바이스 모델**(Apple Intelligence의 기본 모델 또는 내려받은 모델)을 쓰면 어시스턴트가 기기 안에서만 동작하며 텍스트를 어디로도 보내지 않습니다.
내려받은 모델은 앱 전용 저장 공간에 보관되며 백업에 포함되지 않습니다.

서버와 클라우드 제공자는 처음 요청을 보내기 전에(서버는 주소가 바뀔 때마다 다시) 명시적인 동의를 받고,
요청을 기기에서 직접 보냅니다. 동의 철회, 키와 모델 삭제는 언제든 **설정 › AI Assistant**에서 할 수 있습니다.
LeafTeX는 프로젝트 전체를 AI 제공자에게 보내지 않습니다.

## 구매

LeafTeX Pro는 App Store에서 구입합니다. 결제는 Apple이 처리하며 LeafTeX는 결제 정보를 보지 않습니다. 앱은
Apple의 StoreKit으로 기기에서 사용자의 Apple 계정에 LeafTeX Pro가 있는지만 확인합니다. 개발자는 Apple이 개발자에게
제공하는, 개인을 식별하지 않는 판매 보고서만 받습니다.

## 아동

LeafTeX는 아동을 대상으로 하지 않으며 누구의 개인정보도 의도적으로 수집하지 않습니다.

## 선택권

앱이나 Files 앱에서 프로젝트를 삭제할 수 있고, 키·토큰·저장한 서버 로그인은 설정에서 지울 수 있으며,
AI 데이터 공유 동의는 설정에서 철회할 수 있습니다. iCloud Drive나 Git 동기화는 언제든 그만 쓸 수 있습니다.

앱을 삭제하면 앱 폴더 안의 프로젝트, 설정, 내려받은 모델이 함께 삭제됩니다. iCloud Drive나 연결한 폴더의
프로젝트는 그 자리에 남습니다. iOS는 앱을 삭제해도 키체인 항목을 남겨 두므로, LeafTeX는 다시 설치된 뒤 처음
열릴 때 이전에 저장한 키·토큰·비밀번호를 지웁니다. 바로 지우려면 앱을 삭제하기 전에 설정에서 삭제하세요.

## 변경

데이터 처리 방식이 바뀌면 이 문서를 갱신하며, 바뀐 조건으로 AI 제공자에게 데이터를 보내기 전에 다시 동의를 받습니다.
