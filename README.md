# pre-commit-filter

A hook script that checks certain words is in the code during the commit.  
커밋 도중 특정 단어가 코드에 있는지 확인하는 hook script입니다.

## How to use

1. Copy the `pre-commit` file into the `your-project-path/.git/hooks/` folder.  
`pre-commit`파일을 `프로젝트-경로/.git/hooks/` 폴더에 복사하세요.

2. Change mode  
```sh
chmod +x .git/hooks/pre-commit
```

3. run  
`git add` your files and `git commit`. Commit will not be done if haystacks are found in the code.  
원하는 파일을 `git add`한 뒤에 `git commit`을 하세요. 만약 설정한 단어가 코드에서 발견되면 커밋이 되지 않습니다.
