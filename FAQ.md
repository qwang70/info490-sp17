# JupyterHub

## Q: When I use the url [https://info490rb.studentspace.cs.illinois.edu](https://info490rb.studentspace.cs.illinois.edu), the connection times out and my browser displays `webpage is not available. connection timed out`.

A: To access this system, you must be on the University network.
If you wish to work off campus, you must first
[VPN](https://techservices.illinois.edu/services/virtual-private-networking-vpn)
into campus.

## Q: The terminal doesn't start when I click New -> Terminal.

A: [Force reload](https://en.wikipedia.org/wiki/Wikipedia:Bypass_your_cache)
your browser, or select `Running` -> `>_ terminals/1` on the main page.

## Q: I get a `503: Proxy Target Missing` error when I click on `My Server` on JupyterHub.

A: Email the server administrator (Edward, NetID: jkim575) and he will restart your server.
If you were able to log in before and see this error, you probably didn't close your
browser after a session and let the server sit idle for a while. After each session,
it's a good idea to stop your server from `Control Panel` and/or close your browser.

If you are able to access control panel, try restarting the server by clicking `Stop My Server`
and then `My Server` and see if your server appears. If that doesn't solve the problem,
close your browser completely and restart your browser (or use the incognito mode on Chrome
broswers). If the problem persists, email the server admin. Please state
clearly in the email if you let your session expire, what the error message
was, etc.

## Q: I get a `500: Internal Server Error`.

A: If you see when you log onto the server, e.g.

```
500 : Internal Server Error
Spawner failed to start [status=ExitCode=1, Error='', FinishedAt=2016-09-05T17:31:42.287798982Z]
```

email the server administrator (Edward, NetID: jkim575) and he will restart your server.
If you were able to log in before and see this error, you probably didn't close your
browser after a session and let the server sit idle for a while. After each session,
it's a good idea to stop your server from `Control Panel` and/or close your browser.

# Video

## Q: When I click on a video, it says `access denied`. Can you give me access?

A: Videos are hosted on [media space](https://mediaspace.illinois.edu/), and we
(the instructional staff) do not control students' access to media space.
Please contact
[Illinois Media Space Help](https://mediaspace.illinois.edu/help).

## Q: I watched a video in week &lt;insert week number&gt;, but Moodle shows 0 points. Can you correct this?

A: Videos are hosted on [media space](https://mediaspace.illinois.edu/), and
media space tracks your viewing. Instructors simply download the viewing
history from media space, so if you believe there is an error, please contact
[Illinois Media Space Help](https://mediaspace.illinois.edu/help).

# Python

## Q: Should I use Python 2 or Python 3?

A: We will be using Python 3 in this course.

When creating a new notebook on IPython/Jupyter server, make sure that you choose Python 3 in the dropdown menu that appears when you click `New`.

![](https://github.com/UI-DataScience/info490-fa15/blob/master/images/python_2_or_3.png)