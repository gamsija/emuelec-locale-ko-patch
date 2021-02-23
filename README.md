# emuelec-locale-ko-patch
EmuElec 기반의 펌웨어에서 한글언어 수정본.

### 수정내용

원본 한글언어 번역에는 크게 문제없으나 EmuELEC 4.0과 EmuELEC 4.0K 에서 커스텀 컬렉션을 설정하면 무한로딩 걸리는 문제 발생. 타 언어들은 이상없음.

EmuELEC 4.0K의 게임목록 화면에서 Y버튼을 누르면 ES가 재시작 되는 문제. 타 언어들 문제 없음.

이런 문제로 수정하게 됨.

Linguist/po에디터에서 검증을 실행하여 문제 있는 부분들과 일본어 언어파일과 비교분석하여 이상한 부분들 수정함.

번역 내용중 변경된 것은 이용가능한 롬 갯수 표기하는 부분

원본은 *"%i 게임"* 이었는데 ArkOS에서 번역된것이 더 마음에 들어 *"%i개의 게임 이용가능"*으로 수정함


### 적용방법

> 파일 : emulationstation2.po 작업용 언어 파일
> 파일 : emulationstation2.mo 컴파일된 언어 파일

실제 적용해야 할 파일은 emulationstation2.mo 파일이다.

*만약을 위해서 기존 파일은 백업을 받아놓고 작업을 하도록 합시다.*

emulationstation2.po과 emulationstation2.mo 파일을 아래의 경로로 복사(덮어쓰기) 하도록 한다.

> */emuelec/configs/locale/ko/LC_MESSAGES*


