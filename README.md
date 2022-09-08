# TIL

## 리눅스 명령어

1. ls

   > list (목록)

2. cd
   change directory (작업 경로 변경)

3. rm
   remove (파일 삭제)

4. mkdir
   make directory (작업 목록 생성)

5. rmdir  
   remove directory (작업 목록 삭제)

6. touch  
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init

   git 생성

2. add <파일명>

   staging area로 이동

3. commit -m <메세지>

   Repository로 이동

4. push <원격저장소><브랜치>

   원격(Github)으로 이동

5. pull <원격저장소><브랜치>

   원격에서 로컬로 복사

6. clone <원격저장소><브랜치>

   원격에서 로컬로 복제

7. status

   staging Area의 상태

8. log

   repository의 상태

9. git commit --amend

   바로 전 commit과 Staging Area의 Merge을 할 때 사용

10. git restore --staged <파일명>
    Staging Area의 파일을 working Directory로 가져옴

![Git Sheat Sheet](asset/git_terminal.gif)

## 문자코드

1. 문자와 숫자를 1:1 매핑시켜놓은 값이다.

2. 컴퓨터가 사용하는 0과 1로 변환할 때 사용되는 기준

3. 종류

   ASCII코드 (7비트)

   확장 ASCII(8비트) (=ANSI: 8비트)

   유니코드

   EUC-KR코드

   ※ code page : 각 나라 별로 제공 (cp949)

## 인코딩

(<->디코딩)

    유니코드 (utf-8, utf-16, utf-32)
    utf파일로 통일해서 사용함

## 진법(진수)

    Bit: 0이나 1만 저장할 수 있는 단위
    Byte: bit 8개가 모여서 만들어진 것

1. 2진법: 0과 1
2. 8진법: 0~7
3. 10진법: 0~9
4. 16진법: 0~9 A(10) B(11) C(12) D(13) E(14) F(15)
