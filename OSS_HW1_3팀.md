# **Mozilla Firefox 오픈소스 웹 브라우저 조사**  

### 팀원 
- 응용화학공학부 응용화학전공 / 2020116193 / 박유진(github 이름 : tpfbs2)
- 국어국문학과 / 2021114263 / 신정원(github 이름 : shinjw021)
- 행정학부 / 2020115246 / 이다은(github 이름 : ekdms220)
- 지질학과 / 20181141117 / 이민찬(github 이름 : hodumaroo333)
<br/>

## 1. 개요  

&nbsp; Firefox는 비영리 재단법인 모질라 재단과 모질라 코퍼레이션이 개발한 Gecko 엔진 기반 무료 오픈 소스 웹 브라우저로 2002년에 출시되었다. 파이어폭스는 인터넷 익스플로러(Internet Explorer)의 대안으로 시작되어, 안정성과 보안성, 그리고 다양한 확장 기능을 제공함으로써 사용자들에게 인기를 얻고 있다. 특히 크로스 플랫폼을 지원하며, Windows, Linux, macOS, iOS 등 다양한 운영체제에서 사용할 수 있다.  
 
&nbsp; 사용자 개인정보 보호와 인터넷 속도 향상을 위한 기능을 강화하여 사용자들이 보다 안전하고 편리한 웹 브라우징을 할 수 있도록 지원하는 것이 파이어폭스의 주요 강점이다. Enhanced Tracking Protection (ETP)는 웹사이트에서 사용자의 행동을 추적하는 쿠키나 스크립트를 차단하여 사용자 데이터 보호를 강화하고, 컨테이너 탭 기능을 통해 서로 다른 브라우징 세션을 분리함으로써 더 높은 수준의 개인정보 보호를 제공한다. 이러한 기능은 파이어폭스만의 차별화된 장점으로, 사용자들의 프라이버시를 보호하면서 동시에 편리한 브라우징 환경을 제공한다.  

&nbsp; 파이어폭스는 웹 개발자들 사이에서도 인기가 많으며, 개발자 도구를 통해 웹 사이트 디버깅이나 프론트엔드 개발 등 다양한 작업을 보다 효율적으로 수행할 수 있다. Firefox의 개발자 도구는 HTML, CSS, JavaScript를 실시간으로 테스트하고 디버깅할 수 있으며, 특히 웹 페이지의 성능을 분석하고 최적화하는 데 유용하고 Quantum 엔진을 통해 더 빠르고 효율적인 브라우저 경험을 제공하며, 메모리 사용량도 최적화되어 저사양 컴퓨터에서도 원활하게 작동한다.  

&nbsp; 파이어폭스는 오픈 소스 소프트웨어로 개발되어 누구나 소스 코드에 접근하여 수정 및 개선에 기여할 수 있으며, 다른 웹 브라우저들과 달리 웹 표준을 엄격하게 준수하여 웹 사이트의 호환성 문제를 최소화하는 방향으로 개발되었다. 이러한 특징은 웹 개발자들 사이에서 파이어폭스를 선호하는 이유 중 하나이다. 또한 파이어폭스는 다양한 확장 기능을 제공하여 사용자의 요구에 맞게 커스터마이징할 수 있다. 사용자들은 광고 차단, 비밀번호 관리, 웹 개발 도구 등을 추가할 수 있으며, 2010년 5월 기준으로 모질라는 1억 5000만 개 이상의 부가 기능을 addons.mozilla.org(AMO)를 통해 관리하고 있다. 이와 함께 파이어폭스는 Pocket을 통합해 유용한 웹 콘텐츠를 저장하고 나중에 읽을 수 있는 기능도 제공한다.  

&nbsp; 파이어폭스는 지속적으로 업데이트 및 개선되고 있으며, 사용자들의 요구와 피드백을 반영하여 점진적으로 향상되고 있다. 초기 명칭은 피닉스(Phoenix)였으며, 0.7.1 버전까지는 파이어버드(Firebird)라 불리다가 0.8 버전부터 파이어폭스(Firefox)로 변경되었다. 시장 점유율 면에서는 Chrome 등의 경쟁 브라우저에 비해 낮아졌지만, 여전히 프라이버시와 보안을 중시하는 사용자들 사이에서 높은 선호도를 유지하고 있다. 특히 커뮤니티 및 오픈소스 생태계의 강력한 지원을 바탕으로 전 세계 개발자들이 꾸준히 기여하며 발전을 이어가고 있다.  

  
## 2. 라이선스


## 3. 주요기능
&nbsp; Firefox에는 웹 개발자 도구 세트인 Firefox Developer Tools가 내장되어있다. 이를 사용하여 HTML, CSS 및 JavaScript를 검사, 편집 및 디버깅 할 수 있다.
핵심도구로는 페이지 콘텐츠와 레이아웃을 보고 편집하는 페이지 검사기, 웹 페이지에 기록된 메시지를 보고 Javascript를 사용하여 페이지와 상호 작용할 수 있는 웹 콘솔, 웹사이트나 앱이 다양한 기기와 네트워크 유형에서 어떻게 보이고 작동하는지 확인할 수 있는 반응형 디자인 모드, 페이지의 접근성 트리에 접근하여 누락된 부분이나 주의가 필요한 부분을 확인할 수 있는 수단을 제공하는 접근성 검사관 등이 있다. 
이 외에도 다양한 개발자 도구가 Firefox에는 내장되어 있는데, 이 기능들에 대해 자세히 살펴보고자 한다. 

### (1) Style editor(스타일 편집기)
&nbsp; 스타일 편집기를 사용하면 대표적으로 페이지와 연결된 모든 스타일시트 보기 및 편집, 새 스타일시트를 처음부터 만들어 페이지에 적용하기, 기존 스타일시트를 가져와 페이지에 적용하기를 수행할 수 있다.  
&nbsp; 스타일 편집기는 브라우저 도구 하위 메뉴에서 액세스할 수 있는 웹 개발자 도구에서 스타일 편집기 패널을 선택하면 열 수 있다. 이때, 스타일 편집기는 크게 세 가지 섹션으로 나뉘는데 첫번째는 스타일 시트 창이다.  
&nbsp; 스타일 시트 창에는 현재 문서에서 사용 중인 모든 스타일 시트가 나열되어 있다. 시트 이름 왼쪽에 있는 안구 아이콘을 클릭하여 지정된 시트의 사용을 빠르게 켜고 끌 수 있다. 스타일 시트의 변경 사항은 목록에 있는 각 시트 항목의 오른쪽 하단 모서리에 있는 저장 버튼을 클릭하여 로컬 컴퓨터에 저장할 수 있다. Firefox 40 이후부터는 선택한 스타일 시트를 새 탭에서 열 수 있는 컨텍스트 메뉴도 스타일 시트 창에 포함되어 있다.  
&nbsp; 두번재는 편집기 창이다. 우리는 편집기 창에서 선택한 스타일 시트의 출처를 읽고 편집할 수 있다. 변경한 내용은 페이지에 즉시 적용되기 때문에 변경 사항을 쉽게 실험, 수정 및 테스트할 수 있다. 변경 사항이 만족스러우면 스타일 시트 창에서 시트 항목의 저장 버튼을 클릭하여 사본을 로컬에 저장할 수 있다.

### (2) Storage Inspector(보관 검사관)


### (3) Container Tabs
&nbsp; 웹 브라우징 중 개인 정보를 보호하고 다양한 작업을 효과적으로 관리할 수 있게 해주는 도구이다. 이 기능은 여러 탭을 서로 독립된 "컨테이너"로 분리하여 각 탭이 개별적인 쿠키, 세션, 로컬 스토리지 등을 사용하게 만들어 사용자는 하나의 브라우저 창에서 동일 웹사이트의 여러 계정을 동시에 사용할 수 있으며, 특정 사이트가 다른 탭의 브라우징 활동을 추적하는 것을 방지할 수 있다.  
&nbsp; 예를 들어, 사용자는 한 탭에서 개인 이메일 계정에 로그인하고, 다른 탭에서는 업무용 계정에 동시에 접속할 수 있어 계정 분리 기능으로서, 특히 여러 계정을 동시에 사용하는 사용자들에게 유용하다. 또한, 각 컨테이너는 독립적인 쿠키 세트를 사용하기 때문에 웹사이트가 다른 탭의 쿠키나 세션 정보를 공유하지 못하게 되어 프라이버시 보호 기능이 강화된다.  
&nbsp; Container Tabs는 작업 공간을 업무용, 개인용, 쇼핑용 등으로 구분하여 각각의 브라우징 환경을 독립적으로 관리할 수 있으며, 이는 작업 흐름을 정리하고 혼동을 줄이는 데 효과적이고 쿠키와 세션 격리로 인해 다른 탭에서 사용된 데이터를 공유하지 않아 광고 추적 등을 차단하는 데 매우 유용하다.  
&nbsp; 이 기능은 Mozilla의 Multi-Account Containers 확장 프로그램을 통해 더욱 확장되어, 여러 개의 컨테이너를 유연하게 설정하고 관리할 수 있는 옵션을 제공해 각기 다른 용도에 맞는 브라우징 경험을 제공하며, 사용자는 다양한 계정 간의 충돌을 최소화하고 더 안전한 인터넷 사용을 할 수 있다.

### (4) Firefox Monitor
&nbsp; Firefox Monitor는 Mozilla에서 개발한 개인정보 보호 도구로, 사용자가 등록한 이메일 주소가 과거에 발생한 데이터 유출 사건에 포함되었는지 확인하고 이를 알리는 서비스를 제공한다. 이 도구는 인터넷에서 자주 발생하는 대규모 정보 유출 사건에 사용자들이 더욱 빠르게 대응할 수 있도록 설계되었다.  
&nbsp; Firefox Monitor의 주요 목적은 사용자의 개인정보 보호이다. 이를 위해, 사용자가 Firefox Monitor에 자신의 이메일 주소를 입력하면, 해당 주소가 과거 또는 현재 발생한 데이터 유출 사건에 포함되었는지 확인할 수 있다. 만약 유출된 정보가 있다면, 언제, 어디서, 어떤 정보가 유출되었는지를 알려주고 이에 대한 구체적인 대응 조치를 권장한다. 예를 들어, 비밀번호가 유출되었다면 비밀번호를 즉시 변경하거나 2단계 인증과 같은 추가적인 보안 조치를 적용하는 방법을 안내한다.  
&nbsp; 또한, Firefox Monitor는 지속적인 모니터링 기능을 제공하여, 사용자 이메일을 등록하면 새로운 유출 사건이 발생할 때마다 자동으로 알림을 받을 수 있고 이는 특히 보안이 취약한 웹사이트나 대규모 해킹 사건이 빈번한 현재 상황에서 매우 유용한 기능이다. Mozilla는 이를 통해 사용자의 개인정보 보호에 대한 인식을 높이고, 실제로 보안을 강화할 수 있다..  
&nbsp; Firefox Monitor는 특히 유명한 데이터 유출 확인 사이트인 Have I Been Pwned와 통합되어 운영되는데, 이 통합 시스템은 전 세계에서 발생하는 다양한 데이터 유출 정보를 모아서 사용자에게 제공하며, 이러한 정보를 바탕으로 사용자들이 빠르게 문제를 인식하고 해결할 수 있다.  
&nbsp; 이 외에도, Firefox Monitor는 데이터 유출 사건이 발생했을 때의 구체적인 유출 정보, 즉 유출된 데이터의 종류(예: 비밀번호, 이메일 주소, 전화번호, 신용카드 정보 등)와 유출이 발생한 웹사이트 또는 서비스에 대한 정보를 제공한다. 이러한 세부 정보는 사용자가 어디서 문제가 발생했는지 파악하는 데 중요한 역할을 하며, 개인 정보 유출에 대한 심각성을 인식하고 적극적으로 대응할 수 있게 한다.  
&nbsp; 결론적으로, Firefox Monitor는 사용자가 온라인에서 더욱 안전하게 활동할 수 있도록 도움을 주는 강력한 도구이다.
    
### (5) Accessibility Inspector (접근성 검사기)
&nbsp; 접근성 검사기는 접근성 트리를 통해 현재 페이지에서 보조 기술에 노출된 중요한 정보에 액세스할 수 있는 수단을 제공하는 기능으로, 누락되었거나 주의가 필요한 사항을 확인할 수 있다. 

> ####  Accessibility Inspector 액세스 방법
&nbsp; 처음 다른 DevTools를 열게 되면 접근성 기능이 꺼져있기 때문에(단, 이미 다른 브라우저 탭에서 해당 기능을 켰거나, Firefox 접근성 엔진이 이미 활성화된 경우는 제외) 다음 중 하나의 방식을 수행함으로써 활성화시킬 수 있음. 
  * 도구(Tools)> 브라우저 도구(Browser Tools)에서 접근성(Accessibility) 선택
  * 개발자 도구 상자(Developer Tools toolbox)에서 접근성(Accessibility) 선택
  * 기본 브라우저 창에서 마우스 오른쪽 버튼을 클릭하고 Context 메뉴에서 접근성 속성 검사(Inspect Accessibiliy Properties) 선택
  * `:doc:Page Inspector <../page_inspector/index>`의 HTML 창에서 항목을 마우스 오른쪽 버튼으로 클릭하고 Context 메뉴에서 접근성 속성 표시(Show Accessibility Properties)를 선택
  활성화 되면 개발자 도구 상자를 닫을 때까지 접근성 엔진이 계속 실행됨

<NOTE!>
  * 접근성 엔진은 접근성 기능을 켜면 백그라운드에서 실행되며, 이 기능을 활성화 시킬 시 `:doc:Memory <../memory/index>` 와 `:doc:Performance <../performance/index>`같은 다른 패널의 매트릭과 전반적인 브라우저 성능에 약간의 영향을 미칠 수 있음. 
  * 접근성 기능을 자동으로 활성화하지 않으려면 구성편집기(Configuration Editor, Config)를 사용하여 기본 설정 `devtools.accessibility.auto-init.enabled`을 `False`로 설정하면 됨.
  * 접근성 기능을 전혀 사용하지 않으려면 구성편집기(Configuration Editor, Config)를 사용하여 환경설정 `devtools.accessibility.enabled`을 `False`로 설정하면 됨. 이를 사용할 시, 앞서 언급한 접근성 검사기 활성화 방법을 수행하지 않게 됨.

> #### Features of the Accessibility panel 접근성 패널의 기능
   ![accessibility-inspector-tabbing_order](https://github.com/user-attachments/assets/2057f6cb-f2ad-4736-9568-202630c2addc)
&nbsp; 왼쪽에는 현재 페이지의 접근성 트리에 있는 모든 항목을 나타내는 트리 다이어그램이 나타나있다. 중첩된 항목이 있는 경우, 화살표를 클릭하여 세부 항목을 확인할 수 있다.  
* Role : 

### (6) Address Sanitizer
 Address Sanitizer(ASan)는 C/C++ 프로그램에서 사용 후 사용하지 않는 버그와 범위를 벗어난 버그를 감지하는 빠른 메모리 오류 감지기다. 컴파일 시간 계측기를 사용하여 실행 중에 모든 읽기 및 쓰기를 확인한다. 또한 런타임 부분은 동적으로 할당된 메모리를 확인할 수 있는 ![malloc] 및 ![free] 함수를 대체한다.
 asan-maintenance라는 메타 버그는 ASan에서 발견된 모든 버그를 추적하기 위해 유지 관리된다.

> #### 아티팩트 빌드 다운로드(Downloading artifact builds)
  Linux 및 Windows 사용자의 경우, 주소 소독기를 사용하여 Firefox 빌드를 얻는 가장 쉬운 방법은 모질라 중심의 빌드로 지속적인 통합을 다운로드하는 것이다(최소 매일 업데이트):
 • mozilla-central에 최적화된 빌드 : Linux | Windows(테스트에 권장)
 • mozilla-central 디버깅 빌드 : Linux | Windows(최적화된 빌드가 제대로 작동하지 않는 경우 디버깅에 권장)

  퍼징 팀(fuzzing team)은 또한 이러한 빌드와 기타 많은 CI 빌드를 다운로드할 수 있는 fuzzfetch라는 도구를 제공한다. 이 도구를 사용하면 빌드를 훨씬 쉽게 다운로드하고 풀 수 있으며 퍼징뿐만 아니라 CI 빌드를 다운로드해야 하는 모든 용도로 사용할 수 있다.
  fuzzfetch는 Github 또는 via pip을 통해 다운로드할 수 있다.

   `$ python -m fuzzfetch --asan -n firefox-asan`

  위에서 언급한 최적화된 Linux ASan 빌드를 firefox-asan이라는 디렉토리로 압축 해제한다. --debug 및 --os 스위치를 사용하여 위에 나열된 다른 변형을 가져올 수 있다.

 > #### Creating Try builds
  어떤 이유로 이전 섹션에서 언급한 사전 빌드된 바이너리를 사용할 수 없는 경우(예: Linux가 아닌 빌드를 원하거나 패치를 테스트해야 하는 경우), Firefox를 직접 빌드하거나 (다음 섹션 참조) :ref:'Pushing to Try 서버 <Pushing>'을 사용하여 사용자 지정 빌드를 만들 수 있다. 시도하려면 L1 커밋 액세스가 필요하다. 아직 이 액세스 권한이 없는 경우 액세스를 요청할 수 있다(요구 사항은 Mozilla 커밋 작성자 및 Mozilla 커밋 액세스 정책 참조).

  이 트리에는 빌드로 만들기 위한 여러 mozconfig 파일이 포함되어 있다("nightly-asan" 파일은 릴리스 빌드를 생성하는 반면, "debug-asan" 파일은 디버그+opt 빌드를 생성한다). Linux 빌드의 경우, 적절한 구성 파일이 Linux64-asan 대상에서 사용된다. macOS 또는 Windows 빌드를 만들려면 시도하기 전에 일반 디버그 구성 위에 적절한 구성 파일을 복사해야 한다.
 
  예를 들어: cp browser/config/mozconfigs/macosx64/debug-asan browser/config/mozconfigs/macosx64/debug

  그런 다음 일반적인 방식으로 시도를 누른 다음 빌드가 완료되면 적절한 빌드 아티팩트를 다운로드할 수 있습니다.

 > #### Creating local builds on Windows
  Windows에서는 64-bit 빌드에서만 ASan이 지원된다.
  mach bootstrap을 실행하여 ~/.mozbuild 디렉토리에서 업데이트된 clang-cl을 얻은 다음 다음 :ref:'mozconfig < 빌드 옵션 구성>'을 사용한다:

   ac_add_options --enable-address-sanitizer
   ac_add_options --disable-jemalloc

   export LDFLAGS="clang_rt.asan_dynamic-x86_64.lib clang_rt.asan_dynamic_runtime_thunk-x86_64.lib"
   CLANG_LIB_DIR="$(cd ~/.mozbuild/clang/lib/clang/*/lib/windows && pwd)"
   export MOZ_CLANG_RT_ASAN_LIB_PATH="${CLANG_LIB_DIR}/clang_rt.asan_dynamic-x86_64.dll"
   export PATH=$CLANG_LIB_DIR:$PATH
  
  WinDbg에서 ASan 빌드를 실행하면 가짜 1차 액세스 위반 예외가 표시될 수 있다. 이러한 예외는 ASAN에서 creating shadow memory 페이지를 생성할 때 발생하며, 이것을 무시할 수 있다. 이러한 예외를 무시하려면 sxi av를 실행한다. (실제로 충돌해도 2차 액세스 위반 예외가 적용된다.)

  Windows에서는 LeekSanitizer(LSAN)가 지원되지 않는다.

 > #### Creating local builds on Linux or Mac
  -전제 조건 구축
   ·LLVM/Clang
    ASAN 계측기는 LLVM 패스로 구현되어 Clang에 통합된다. Firefox를 편집할 수 있는 모든 Clang 버전은 ASAN 빌드에 필요한 모든 것을 갖추고 있다.

  -Building Firefox
   ·Getting the source
    해당 수정본 또는 이후 수정본을 사용하려면 :ref: 'mozilla-central의 <Mercurial overview>의 복사품을 작성하기만 하면 된다.

   ·빌드 구성 조정(Adjusting the build configuration)
    mozilla-central 디렉토리에 다음 내용으로 빌드 구성 파일 mozconfig를 만든다:
   `# Combined .mozconfig file for ASan on Linux+Mac

     mk_add_options MOZ_OBJDIR=@TOPSRCDIR@/objdir-ff-asan

     # Enable ASan specific code and build workarounds
     ac_add_options --enable-address-sanitizer

     # These three are required by ASan
     ac_add_options --disable-jemalloc
     ac_add_options --disable-crashreporter
     ac_add_options --disable-elf-hack

     # Keep symbols to symbolize ASan traces later
     export MOZ_DEBUG_SYMBOLS=1
     ac_add_options --enable-debug-symbols
     ac_add_options --disable-install-strip

     # Settings for an opt build (preferred)
     # The -gline-tables-only ensures that all the necessary debug information for ASan
     # is present, but the rest is stripped so the resulting binaries are smaller.
     ac_add_options --enable-optimize="-O2 -gline-tables-only"
     ac_add_options --disable-debug

     # Settings for a debug+opt build
     #ac_add_options --enable-optimize
     #ac_add_options --enable-debug

     # MacOSX only: Uncomment and adjust this path to match your SDK
     # ac_add_options --with-macos-sdk=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.8.sdk

    browser/config/mozconfigs/linux64/nightly-asan(자동 테스트에 사용되는 Address Sanitizer 빌드에 사용되는 구성 파일)에서 볼 수 있듯이 이 파일이 필요할 수도 있다:
     # ASan specific options on Linux
     ac_add_options --enable-valgrind`

   ·빌드 프로세스 시작
    이제 일반 ./mach build 명령을 사용하여 빌드 프로세스를 시작한다.

   ·Firefox 시작
    빌드가 완료된 후 디버거에서 실행할 수 있는 일반적인 옵션(gdb, lldb, rr 등)으로 ./mach run은 --disable-e10s 및 기타 옵션과 마찬가지로 정상적으로 작동한다.

   ·자바스크립트 쉘만 구축하기(Building only the JavaScript shell)
    전체 Firefox 빌드를 수행하는 대신 JavaScript shell만 빌드하려면 아래 빌드 스크립트가 도움이 될 것이다. 이 스크립트를 js/src/ 하위 디렉토리에서 실행하고 첫 번째 매개 변수로 디렉토리 이름을 전달한다. 그런 다음 빌드는 해당 이름의 새 하위 디렉토리에 생성된다.

    `#! /bin/sh

     if [ -z $1 ] ; then
          echo "usage: $0 <dirname>"
     elif [ -d $1 ] ; then
          echo "directory $1 already exists"
     else
          autoconf2.13
          mkdir $1
          cd $1
          CC="clang" \
          CXX="clang++" \
          CFLAGS="-fsanitize=address" \
          CXXFLAGS="-fsanitize=address" \
          LDFLAGS="-fsanitize=address" \
          ../configure --enable-debug --enable-optimize --enable-address-sanitizer --disable-jemalloc
     fi`

  -Getting Symbols in Address Sanitizer Traces
   기본적으로 ASAN 트레이스는 기호화되지 않고 binary/library와 메모리 오프셋만 인쇄한다. 기호가 포함된 더 유용한 트레이스를 얻으려면 두 가지 접근 방식이 있다.

   ·Using the LLVM Symbolizer (recommended)
    ··
