---
layout: post
title: Pyharm SFTP Auto Syncronize Setting
subtitle:
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
tags: [FQE]
comments: true
---

[Reference](https://youtrack.jetbrains.com/issue/PY-46637)

## Error
- Pycharm에서 SFTP연동 시 종종 로컬에서 수정했던 내용들이 동기화되지 않는 오류가 발생


## Solution
- Mapping되는 디렉토리를 변경해서, SFTP 추가 시에 Default SFTP의 변경이 필요함
- __File | Settings | Build, Execution, Deployment | Deployment__ 에 진입하여, 추가했던 SFTP를 체크표시 하여, Default SFTP로 사용

![](/assets/img/setting_screenshot.png)