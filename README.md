# Homework 4
## Working Directory 생성부터 원격 저장소에 README.md 파일을 push 하기 까지의 과정과 셸 명령어

1. 작업 디렉토리 생성:
    ```sh
    mkdir Homework4
    cd Homework4
    ```

2. Git 저장소 초기화:
    ```sh
    git init
    ```

3. README.md 파일 생성:
    ```sh
    echo "# Homework 4" > README.md
    ```

4. README.md 파일을 스테이징:
    ```sh
    git add README.md
    ```

5. 커밋:
    ```sh
    git commit -m "Add README.md file"
    ```

6. 원격 저장소 추가:
    ```sh
    git remote add origin https://github.com/eschoi0830/Homework4.git
    ```

7. 로컬 커밋을 원격 저장소에 푸시:
    ```sh
    git push -u origin main
    ```

위 과정들을 따르면 README.md 파일을 생성하고, 로컬 저장소에 커밋한 후 GitHub 원격 저장소에 푸시할 수 있습니다.
