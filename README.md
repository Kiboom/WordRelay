# Git 끝말잇기 게임

## 게임 설명

끝말잇기를 통해 Git의 Push와 Pull을 연습하는 실습을 해보겠습니다.

## 절차

1. **저장소 복제**: 저장소를 로컬에 복제합니다.
    ```bash
    git clone https://github.com/Kiboom/WordRelay.git
    ```

2. **브랜치 생성**: 각 팀에 맞는 브랜치로 이동합니다.
    ```bash
    git checkout team1
    ```

3. **최신 변경 사항 가져오기**: `git pull`을 사용하여 최신 변경 사항을 가져옵니다.
    ```bash
    git pull origin team1
    ```

4. **단어 추가**: `words.txt` 파일을 열어 마지막 단어의 끝 글자로 시작하는 새로운 단어를 추가합니다.
    ```txt
    - 사과
    - 과일
    - 일반쓰레기
    - 기차
    - 차돌박이
    ```

5. **커밋**: 변경 사항을 커밋합니다.
    ```bash
    git add words.txt
    git commit -m "후후 과연 이 단어를 이을 수 있을까"
    ```

6. **푸시**: 변경 사항을 원격 저장소에 푸시합니다.
    ```bash
    git push origin team2
    ```


## 규칙
- 단어는 중복되지 않아야 합니다.
- 사전에 존재하는 단어여야 합니다.
- 한 번 사용된 단어는 다시 사용할 수 없습니다.