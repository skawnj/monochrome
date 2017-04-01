---
title: VirtualBox 게스트, 호스트 간 클립보드(복붙) 공유, 드래그앤드롭
description: VirtualBox 게스트, 호스트 간 클립보드(복붙) 공유, 드래그앤드롭
header: VirtualBox 게스트, 호스트 간 클립보드(복붙) 공유, 드래그앤드롭
---
* VirtualBox로 설치한 Ubuntu Linux 환경
	- 호스트 OS: Windows 10
	- 게스트 OS: Ubuntu 16.04 LTS
	- VirtualBox 버전 5.1.18 r114002 (Qt5.6.2)
* VirtualBox Guest Additions의 설치
	1. Ubuntu를 부팅시킨 VirtualBox 창 메뉴바
	2. '장치' → '게스트 확장 이미지 CD 삽입...'
		![](http://cfile24.uf.tistory.com/image/273EB64755F5A1CB0BB0DE)
	3. 설치(터미널 창 발생해 설치 진행)
	4. 설치 완료 후(터미널에서 엔터 키) 게스트 OS와 호스트 OS 모두 리부팅
* 호스트와 게스트 간 가능해지는 일
	- 복붙(Ctrl-C, V)
	- 파일 드래그 앤 드롭
* 참고 자료
	- [ask ubuntu - How do I install Guest Additions in a VirtualBox VM?](http://askubuntu.com/questions/22743/how-do-i-install-guest-additions-in-a-virtualbox-vm/22745#22745)
	- [Real Book(티스토리) - VirtualBox 화면 크기 설정 가능하게 / 게스트 확장 설치](http://real-book.tistory.com/entry/VirtualBox-%ED%99%94%EB%A9%B4-%ED%81%AC%EA%B8%B0-%EC%84%A4%EC%A0%95-%EA%B0%80%EB%8A%A5%ED%95%98%EA%B2%8C-%EA%B2%8C%EC%8A%A4%ED%8A%B8-%ED%99%95%EC%9E%A5-%EC%84%A4%EC%B9%98)