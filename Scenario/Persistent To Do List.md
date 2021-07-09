# Persistent To Do List

내용이 DB에 저장되어 내용이 사라지지 않는 todo 리스트를 만들고자 한다.

사용자는 한 명이고 외부에 공개되지 않으므로 사용자 계정에 대한 기능은 포함하지 않는다.

> GET /todos
>
> ##### 200 OK
>
> ```json
> [
> 	{
> 		"title": "My todo",
>         "content": "This is my job!",
>         "createdAt": "2021-07-08T15:32",
>         "expiredAt": "2021-07-09T18:00"
> 	}
> ]
> ```
>
> createdAt과 expriedAt은 iso 8601 형태를 따름



>POST /todos
>
>###### 201 Created

