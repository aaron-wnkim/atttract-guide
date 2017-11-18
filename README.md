# atttract-guide


### attract mode 설치
attract mode download 후 설치
```$xslt
$ curl -O https://github.com/mickelson/attract/releases/download/v2.2.0/attract-v2.2.0-3-macosx.dmg
```
attract mode를 실행하면 $HOME/.attract directory가 생성된다

### attract mode setting 
자동생성된 $HOME/.attract을 삭제 
```$bash
$ rm -rf $HOME/.attract
```

이미 셋팅된 .attract를 $HOME/.attract로 대체한다 
```$bash
$ pwd
$ $HOME (user home)
$ rm -rf $HOME/.attract
$ tar zxvf attract-lite.tar.gz (적당한 위치에 압축해제)
$ ln -s attract-lite $HOME/.attract (symbolic link)

```

### rom file 추가 
#### 예시
다음과 같이 원하는 rom file을 다운로드
```$xslt
https://www.emuparadise.me/M.A.M.E._-_Multiple_Arcade_Machine_Emulator_ROMs/Street_Fighter_II:_The_World_Warrior_(World_910522)/16419-download

```
다운로드한 rom file을 다음의 경로에 copy
```$xslt
cp ~/Download/sf2.zip ~/.attract/mame0190-64bit/roms/
```

### rom list 생성 및 artwork 다운로드
attract mode에서 추가한 rom file을 인식하려면 롬 목록을 생성 해야한다.

#### rom list 생성 방법
atrract mode 실행후 [tab]키 입력하면 '설정 화면이 열린다.
에뮬레이터 > mame > 롬 목록 생성 선택 후 enter

#### artwork 다운로드 방법
롬 목록 생성 후, 팬 아트워크 다운로드를 선택한다.
에뮬레이터 > mame > 팬 아트워크 다운로드 선택 후 enter

