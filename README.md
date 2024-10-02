# Zero Timeout Message Handler

An object oriented message handler that can toggle its queue timeout to trigger high speed polling.

Useful as a helper loop or a standalone "actor". Great for things like reading/writing IO data, PID control, process monitoring, and front panel updates. The most common use-case is likely for interacting with hardware and doing things that are near-real-time but don't require the execution time guarantees... "Do I need a RTOS? Let's find out..."