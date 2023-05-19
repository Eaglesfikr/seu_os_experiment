# seu_os_experiment
szw老师 课后操作系统实验
# 1.用信号量表示独木桥实验：
  Single-Lane Bridge Problem is illustrated in the following figure: A bridge over a river is only wide enough to permit a single lane of traffic. Consequently, cars can only move concurrently if they are moving in the same direction. If two cars that move in different directions enter the bridge at the same time, then the safety rule is violated. 

More specifically, the management rules for the single-lane bridge is given as follows, assuming the two entrances of the bridge are denoted by ‘A’ and ‘B’. 
When the single-lane bridge is empty, cars moving by any driving direction can enter. However, we must ensure that cars moving in different directions cannot concurrently enter the bridge, which will cause a deadlock.
When the single-lane bridge is occupied, there are cars driving through the bridge by a same direction (for example, AB). If a car moving by the opposite direction (for example, BA) attempts to enter the bridge, it must wait outside of the entrance (for example, entrance B).
When all the cars moving by the same direction leave the bridge, the bridge becomes empty. In this case, if there exist opposite-direction cars that wait outside of the bridge entrance, they must be notified to enter.
Use semaphore to design an algorithm that can ensure the orderly operation of this single-lane bridge. A framework of the pseudocode has been given as follows.

# 2.睡觉的助教
（课本上的课后编程项目1）
