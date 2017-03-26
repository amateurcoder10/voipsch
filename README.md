# voip phone with periodic scheduling to send and play packets

uses timerfd to implement periodic scheduling
This timer api is similar to setittimer and timer_create but uses a file descriptor which can be read to get details about the expiration of the timer.

Bandwidth consumed is displayed as a statistic when SIGINT is received on the client.
