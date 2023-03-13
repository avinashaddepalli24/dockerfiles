#### STOPSIGNAL

STOPSIGNAL is used to how to  exit the container.
* By default docker request for exit and wait for some time.
* If it is not exiting it can force kill.
* WHen you container receives stop signal your azpplication can perform
  * You can close DB connections
  * You can do some backup.