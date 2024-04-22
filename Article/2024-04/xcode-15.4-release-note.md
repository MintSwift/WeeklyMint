![header](https://miro.medium.com/v2/resize:fit:828/format:webp/1*hh05jQ_xT8liY5LmZBbfrg.png)

![Date](https://img.shields.io/badge/날짜-2024.04.15-orange?style=flat-round) ![번역](https://img.shields.io/badge/번역-DeepL-yellowgreen?style=flat-round) ![카테고리](https://img.shields.io/badge/Xcode-orange?style=flat-round) ![카테고리](https://img.shields.io/badge/번역-orange?style=flat-round)
### Overview

Xcode 15.4 베타 버전에는 iOS 17.5, iPadOS 17.5, tvOS 17.5, watchOS 10.5, macOS Sonoma 14.5 및 visionOS 1.2용 SDK가 포함되어 있습니다. Xcode 15.4 베타 릴리스는 iOS 12 이상, tvOS 12 이상, watchOS 4 이상 및 visionOS에서 온디바이스 디버깅을 지원합니다. Xcode 15.4 베타를 사용하려면 macOS Sonoma 14 이상을 실행하는 Mac이 필요합니다.

### App Shortcuts Preview

#### 알려진 문제

* 앱 바로 가기 미리 보기를 사용하도록 설정했지만 앱의 기본 Locale 실패할 수 있습니다. (125556990)

### Asset Catalogs

#### 해결된 문제

* Swift 엄격한 동시성 검사를 활성화한 상태에서 생성된 에셋 심볼(asset symbols)이 경고를 표시하던 문제를 수정했습니다. (124156187)

### Devices

#### 해결된 문제

* 특정 상황에서 앱이 Xcode 또는 devicectl을 사용하여 데이터 컨테이너의 콘텐츠를 교체한 후 자체 데이터 컨테이너의 콘텐츠를 읽을 수 없습니다. (116698465) (fb13253099)

### Simulator

#### 해결된 문제

* XProtect 업데이트가 설치된 후 시뮬레이터 장치를 부팅하려고 할 때 Gatekeeper 검사로 인해 일시적으로 부팅되지 않을 수 있습니다. 이는 "시뮬레이터를 부팅할 수 없음" 또는 "-308" 오류로 나타날 수 있습니다. (124502668)

### Testing

#### 해결된 문제

* actor-isolated 테스트 메서드에서 XCTestCase.fulfillment(of:)를 사용하면 경고가 생성됩니다. (124112256)


### 출처

* Apple, [Xcode 15.4 Release Notes](https://developer.apple.com/documentation/xcode-release-notes/xcode-15_4-release-notes), Apple Developer Documentation, 2024.05.12 접속
