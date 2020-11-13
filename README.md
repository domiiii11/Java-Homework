# Java-Homework

## Alarm system

Most cars these days come with an alarm that can be triggered on and off. Such alarm is usually controlled through
a remote controller. Remote controllers can be 2 kinds:
TypeA- 2 functions. 
- Lock- used for locking and turning alarm on. Pressing this button again, does not unlock, but in either case, it blinks car lights.
- Unlock- used for unlocking and turning alarm off. Pressing this button when a car is locked- unlocks it, otherwise it does nothing.

TypeB- 1 function. 
Toggle
- If a car is unlocked, locks the car and blinks car lights and turns on the alarm.
- If a car is locked, unlocks the car and blinks car lights and turns off the alarm.

Presented with a model of a `car(isLocked, lights)`, `alarm(isOn)`, and a `RemoteAlarmController(car, alarm)`
You have been put to a task to create such an alarm system and you also need to test it.
You need to simulate 2 situations, for type A and type B controllers:
- Opening a locked door rings an alarm. This should call `alarm.Beep()` method.
- Opening a 

And other controller specific, lights related functionality.

Are you up for a challenge?