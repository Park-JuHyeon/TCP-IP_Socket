# TCP-IP_Socket (교재: 윤성우의 열혈 TCP/IP 소켓 프로그래밍)

## Day 01
- 리눅스 명령어 종류 (기본)
	1. 파일 생성 :  mkdir
	2. 파일 삭제 :  rm-rf [삭제할 폴더명/파일]
	3. 현재 폴더 확인 : ls
	4. 현재 위치 확인 : pwd
	5. 기본 편집기 열기 : nano
	6. 폴더 이동 : cd [이동할 폴더명]
	7. ./현재폴더 , ../바로 위폴더로 이동 ,
	8. 컴파일 : gcc 파일명.c -o 실행파일명 
	9. 라즈베리 종료 : sudo shutdown now

- Class A : 0 ~ 127 	  0 ~ 0111 1111
- Class B : 128 ~ 191	  128 ~ 1011 1111
- Class C : 192 ~ 223	  192 ~ 1101 1111

- IP : 내컴퓨터로 찾아오는 길
- PORT : 내 컴퓨터에 실행되는 응용프로그램을 찾아오는 길

## Day 02
- TCP 기반 서버/클라이언트 (chapter 4)
	- TCP 서버 : hello_server.c(hserver) 실행
	- TCP 클라이언트 : hello_client.c(hclient) 실행
	- 서버와 클라이언트 통신
		- hserver 실행 후 포트번호 할당 : ex) ./hserver 9000
		- hclient + ip번호 + 포트번호 실행 : ex) ./hclient 127.0.0.1 9000
		
## Day 03
- TCP 기반 서버/클라이언트 (chapter 5)
		- echo_server(eserver), echo_client(eclient) 실행 구현

- UDP 기반 서버/클라이언트 (chapter 6)
	
