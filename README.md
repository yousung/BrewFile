# MAC 한번의 명령어로 모두 설치하기

## Homebrew 
MAC에서 개발 패키지를 관리하는 유명한 패키지 매니저이다. 우리는 이중에서, cask, mas의 기능을 쓸것 입니다.
- homebrew : 개발 패키지 
- cask : 웹사이트에서 받을 수 있는 어플리케이션 설치
- mas : 스토어에서 받을수 있는 어플리케이션 설치

## 설치
- homebrew 설치
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- cask 설치
cask 는 homebrew 에 이미 포함되어 있습니다.

- mas 설치
```shell
brew install mas
```

- 함께 포함된 BrewFile 과 같은 경로에서
```shell
brew bundle
```