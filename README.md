# pipe_iocp
a tiny pipe ipc framework using  I/O completion port in win32

author:fangqing0827@126.com

Src\pipe_imp: 	the implement of pipe communication using iocp
Src\pipe_imp\PipeApi.h:   C style interface  which is a simply warpper of the  CPipeLink Class. you must call "InitPipe"  when application launch and call
"UnInitPipe" when application exit.
	
Src\PipeClient: the demo client source
Src\PipeServer: the demo server source