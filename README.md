# ChanwooChatServer

콘솔 멀티 유저 채팅서버
-----------

- 서버 실행
- 클라이언트에서 telnet, nc명령어를 통해 접속

```
$ nc [ServerIP] [Port]
```

```
$ nc 127.0.0.1 33333
```

#### 명령어
----
> /help
> 명령어 목록을 보여준다.
----
/name
이름을 설정할 수 있다. 최초 접속시 필수.
----
/show
개설된 채팅방 목록을 보여준다.
----
/create [room name]
채팅방을 생성한다.
----
/remove [room name]
채팅방을 삭제한다.
----
/enter [room name] /join [room name]
채팅방에 입장한다.
----
/exit /quit
프로그램을 종료한다.
