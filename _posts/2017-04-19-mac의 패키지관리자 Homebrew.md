---
layout: post
title: 맥의 패키지관리자 HomeBrew
date: 2016-04-19
excerpt: "과거 리눅스에서 작업을 할 때..."
tags: [Homebrew, How to, mac]
comments: true
---

# Mac의 패키지 관리자 HomeBrew
과거 리눅스에서 작업을 할 때 개발환경셋팅이나 필요한 프로그램을 다운받으려 할때, `apt-get install`을 이용하여 다운받곤 하였습니다. 그러나 맥에서는 `apt-get`을 사용하지 않고 MacPort나 Homebrew를 사용한다고 합니다. 대부분의 맥 사용자들은 Homebrew를 사용한다고 하기에, Homebrew를 설치해보려 합니다.

# Homebrew 설치 방법
다운 및 설치는 아주 간단합니다. 터미널에 가서 아래의 명령어를 입력하면 다운로드부터 설치까지 한번에 됩니다. 
{% raw %}
	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
{% endraw %}
<img src="https://nine-hundred.github.io/Blog/assets/brewInstall.jpeg">
    
설치에 대한 자세한 사항은 <a href="https://brew.sh/index_ko.html">Homebrew</a>를 참조하시면 됩니다.
