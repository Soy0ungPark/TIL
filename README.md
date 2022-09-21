# TIL

## 2022-09-21

### 리눅스 커맨드라인 기초
```
# print working directory
pwd
```

```
# change directory
cd
```

```
ls // list
```

- ls 뒤에는 -a나 -l 옵션을 붙일 수 있음


### vim 에디터 커맨드
```
# 입력 모드 진입
i 

# 명령 모드 전환
esc
```

```
# 파일 저장 후 vim 에디터 빠져나오기
:wq

# 저장하지 않고 vim 에디터 빠져나오기
:q
```

### 버전관리를 위한 git 커밋
```
#스테이지 영역에 코드 파일 추가
git add

# 커밋
git commit
```

#### gitignore
- 저장소 파일마다 갖춰져야 하는 파일
- 깃허브 저장소 생성 옵션, gitignore generator, VScode 플러그인 등 사용


### 브랜치
- 협업을 위해 사용
- 특정한 목표를 갖고 코드를 수정하기 시작할 때 생성

```
# 깃허브 저장소 만들기
mkdir
```

```
# 깃 초기화
git init
```


### vim 사용법
>window에서 git bash를 사용할 때, ㅇㅇefault editor로 vim을 세팅했기 때문에 git을 사용하려면 반드시 vim을 사용할 줄 알아야 함.

#### 명령모드 vs 입력모드
1. vim 에디터를 처음 켜면 명령모드로 진입
- 입력 불가능
2. 입력하려면 입력 모드로 바꿔야함
- 입력 모드로 바꾸려면 키보드에서 `i`키 (insert) 등을 누름
3. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령모드로 돌아가야함
- 명령모드로 바꾸려면 키보드에서 `esc`키를 누름
- 명령모드에서 `:w`를 입력하고 `enter`키를 누르면 저장만 됌 (write)
- `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음 (write and quit)
- `:q`를 입력하면 에디터에서 빠져나올 수 있음 (quit)


### commit
#### 정의
  - The "commit" command is used to save your changes to the local repository.
  - 커밋 하나는 독립적인 버전을 나타냄
  - The git commit command captures a snapshot of the project's currently staged changes.
  - 스냅샷(사진)과 유사

#### 언제 커밋을 만드는가
  - logical한 변경이 있을때 커밋을 하나 만듬
  - 가능하면 커밋 단위는 작을 수록 좋음
