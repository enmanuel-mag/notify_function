# Notifier Function Status
This library use a decorator to show a toast in your screen.

## Requeriments

All requeriments will be installed when install this module, but if something was wrong this is the list (all this install by pip):

- win10toast (only if you are using windows)
- py-notifier

## Usage

All that you need is use a decorator and specific some parameters, next explain it:

Import: ```from notifier_function.notifier import notifer_decorator```

Decorator to use: ```@notifer_decorator()```

### Parameters

- **title** is the title of toast notification, by defult is: Function finished.
- **msg** is the message of toast notification, by default is: Your function has finished.
- **duration** is the time, in seconds, that the nottications will show, by default is 8.
- **urgency** is the urgency of the notifcation. By defualt is URGENCY_NORMAL. The options are:
  - URGENCY_LOW.
  - URGENCY_NORMAL.
  - URGENCY_CRITICA.
