# MHGU-KoreanPatch
글로벌판인 Generation Ultimate 1.4.0버전

원래 일본판으로 제작됐던 한글패치파일을 포팅함

[PC포팅 버전](https://github.com/morerokk/MHGURecomp) mods 폴더 혹은
에뮬레이터 모드 적용 혹은
스위치 커펌후 모드 적용(테스트 안해봄)

- **일반 / HD** : HD판은 메모리 사용량 다소 증가
- Recomp에서 띄어쓰기가 안되고 붙어서 표시 될 경우 인 게임 옵션에서 **Graphics & Audio** 탭에 있는 `Fix kerning` 옵션을 off로 해주세요.

  한국어로는 **그래픽 및 오디오**탭에 있는 `자간 보정` 옵션을 끄기로 해주세요.

### 호환되는 모드
- [KatSmithy](https://gamebanana.com/mods/737929)

- KatSmithy 모드 이용 시 고려해야 할 사항 :
  - `KatSmithy_MenuText`는 설치하지 말아주세요.
  - KatSmithy 폴더 안에 있는 `strings_ko.tsv`을 지워주세요. (`string_ko.tsv`는 이미 우리 모드 폴더내에 포함되어 있습니다.)
  - v1.0.6 이전부터 KatSmithy를 설치해서 실행했던 유저라면 무기 목록이 일부 영어로 나올 수 있습니다. 이를 해결하기 위해 Recomp save폴더에서 tree_names.txt를 지워주세요. (지워도 다시 생성되는데 다시 생성될때는 한국어로 나옵니다.)

### 한글패치 출처 : https://blog.naver.com/dudaos1123/221390808374
