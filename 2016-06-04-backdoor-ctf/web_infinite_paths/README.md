## Infinite Paths (Web)
	tl;dr Make requests for http://hack.bckdr.in/INFINITE-PATHS/path/..../path//path

Each request to `http://hack.bckdr.in/INFINITE-PATHS/path/path/path/path/path/path/...` returns `Keep roaming buddy!`

Surprisingly `http://hack.bckdr.in/INFINITE-PATHS//path` gives us `A part of the flag(length=50) is: "Y"`

It turns out that we just have to make 50 requests to `"http://hack.bckdr.in/INFINITE-PATHS"+"/path"*N +"//path"` to get the full flag