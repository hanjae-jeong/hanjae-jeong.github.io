---
date: 2021-02-27 10:08:00 +0900
title: "xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun"
tags: ['애플', 'm1', '맥os', '빅서', '에러', 'apple', 'macos', 'big sur', 'git', 'error']
category: ['이슈/맥os']
use_math: true
---

# git 이 안 됨

분명 xcode command line tools (CLI) 설치해서 git 을 사용했었는 데 아래와 같이 에러가 났다.

'''
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
'''

# 해결

구글링 해보니 다행히 해결책은 간단하다. 

'''
% xcode-select --install
'''
