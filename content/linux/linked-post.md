+++
title = "LINUX 역사"
date = "2023-05-28T21:49:20+02:00"
tags = ["golang", "programming", "theme", "hugo"]
categories = ["History"]
banner = "img/banners/banner-4.jpg"
authors = ["김정진"]
+++

역사
2.1. 초기
1991년 당시 핀란드 헬싱키 공대 대학생이었던 리누스 토르발스가 미닉스 OS를 사용하는 컴퓨터에서 작업해서 만들었다. 참고 기사 미닉스를 쓰면서 마음에 안 드는 점이 있을 때마다 커널에 여러 가지 기능을 추가했고, 어느새 운영체제에 가까울 정도로 기능이 늘어났다.

리누스는 이 커널을 처음 릴리스 할 때, 무료이니 'Free', 매니아이니 'Freak', 그리고 Unix와 유사하니 'x'를 조합해 'Freax'라고 부르길 원했다고 한다. 그러나 FTP 서버에 소스 파일을 업로드해줬던 아리 렘케는 차라리 리누스가 개발했으니 '리눅스'라고 부르는 게 낫겠다 싶어 리누스의 허락 없이(...) 이름을 '리눅스'로 바꿨고, 리누스도 이 이름이 마음에 들어 새 운영체제의 이름은 리눅스로 확정됐다. 나중에 리누스 토르발스는 BSD OS가 실패한 원인이 "이름에 쓸데없이 약자를 써서 그렇다."라고 말한 적이 있다.
2.2. 성장
리눅스는 거의 공개 직후부터 가히 폭발적인 성장세를 보인다. 여러 가지 원인들이 겹친 결과였다. 유닉스의 일종인 BSD OS가 소송에 휘말리면서 대체품에 대한 관심이 커진 것도 큰 역할을 했다. 극성 BSD 빠들 중에서는 그 소송만 없었다면 리눅스는 존재하지도 않았을 거라고 주장하는 사람도 있을 정도였다. 또한, 리눅스 OS 커널 소스코드에 GPL 라이선스를 선택하고, 현재 오픈 소스 개발 모델의 모체가 된, 소스 코드 공개와 공개적 개발 모델을 선택한 것도 매우 유효했다. 이전에는 오픈 소스 소프트웨어라도 핵심 개발자 집단이 개발 과정을 독점하고, 릴리스할 준비가 되었다고 판단될 때에야 소스를 공개하는 방식을 사용했다. 그런데 리눅스는 누구나 소스를 읽은 후 패치를 작성해 보낼 수 있도록 했다. 패치가 받아들여지면 그 패치를 보낸 사람은 기여자가 되어 다음 릴리스 노트에 이름이 박혔다. 에릭 레이먼드의 표현을 빌리자면 이는 사람들의 과시욕을 충족시키는 방식이었고 사람들은 돈을 받지 않고도 커널 버그 수정과 기능 추가에 매달렸다.

초기 리눅스는 기능이 불완전한 운영체제였다. 그러나 자체 커널[3] 개발에 난항을 겪고 있던 GNU 프로젝트가 리눅스 커널에 관심을 가졌고, 리눅스 커널과 GNU 유틸리티가 결합하면서 비교적 완전한 운영체제로 거듭났다. 18개월여만인 1994년에는 리눅스 커널 1.0 버전이 나왔다. 이후 썬 마이크로시스템즈나 IBM 등의 대기업들이 리눅스 개발을 지원하기 시작하는 등, 리눅스가 IT 세계에서 가지는 입지는 빠르게 탄탄해졌다.
2.3. 현재
데스크톱/랩톱 용도뿐만 아니라 웹 서버, 클라우드 컴퓨팅, 모바일 기기, 임베디드 기기 등 여러 분야에서 폭넓게 사용되고 있다.

반도체 회사 및 레드햇 등 리눅스 운영체제 배포자들이 주로 리눅스 커널에 참여하고 있다. 모바일 시장에서 리눅스 커널을 쓰는 안드로이드의 위상이야 더 말할 필요가 없을 정도이다.

Microsoft Windows 운영체제에도 리눅스 커널을 탑재한 WSL(Windows Subsystem for Linux)을 포함시켜 리눅스 환경을 지원하고 있다.