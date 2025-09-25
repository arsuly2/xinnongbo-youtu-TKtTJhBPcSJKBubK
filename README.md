[合集 - 技术札纪——有限硬件与无限计算的权衡艺术(36)](https://github.com)

[1.书本介绍：技术札纪——有限硬件与无限计算的权衡艺术07-24](https://github.com/poemyang/p/19002322)[2.书本大纲：从芯片、分布式到云计算AI时代07-25](https://github.com/poemyang/p/19004265)[3.我的代码背叛了我？为什么 a=1, b=2，最后x和y都等于0？07-25](https://github.com/poemyang/p/19004704)[4.我的代码出现幻觉？说好的a = 1； x = b，怎么成了x = b； a = 1？07-28](https://github.com/poemyang/p/19008983)[5.为什么i++不是原子操作？一个让无数并发程序崩溃的“常识”07-29](https://github.com/poemyang/p/19010948)[6.没有Happens-Before？你的多线程代码就是‘一锅粥’！07-30](https://github.com/poemyang/p/19012883)[7.Hello World背后藏着什么秘密？一行代码看懂Java的“跨平台”魔法07-31](https://github.com/poemyang/p/19014740)[8.a+b=c，处理器一步搞定，Java虚拟机为啥要四步？08-01](https://github.com/poemyang/p/19016482)[9.“同声传译”还是“全文翻译”？为何HotSpot虚拟机仍要保留解释器？08-04](https://github.com/poemyang/p/19020937)[10.“代码跑着跑着，就变快了？”——揭秘Java性能幕后引擎：即时编译器08-05](https://github.com/poemyang/p/19022518)[11.Java编译器优化秘籍：字节码背后的IR魔法与常见技巧08-06](https://github.com/poemyang/p/19024509)[12.解锁硬件潜能：Java向量化计算，性能飙升W倍！08-07](https://github.com/poemyang/p/19026352)[13.new出来的对象，不一定在堆上？聊聊Java虚拟机的优化技术：逃逸分析08-08](https://github.com/poemyang/p/19027777)[14.性能优化之母：为什么说“方法内联”是编译器优化中最关键的一步棋？08-11](https://github.com/poemyang/p/19031406)[15.从纳秒到毫秒的“时空之旅”：CPU是如何看待内存与硬盘的？08-12](https://github.com/poemyang/p/19033086)[16.硬盘性能提升100倍的秘密：看懂顺序I/O的魔力08-14](https://github.com/poemyang/p/19038725)[17.十年大厂员工终明白：MySQL性能优化的尽头，是对B+树的极致理解08-18](https://github.com/poemyang/p/19043960)[18.Facebook内部都在用的存储引擎，LSM凭什么能硬扛亿级写入流量？08-21](https://github.com/poemyang/p/19050442):[pure加速器](https://puregw.com)[19.千亿消息“过眼云烟”？Kafka把硬盘当内存用的性能魔法，全靠这一手！08-22](https://github.com/poemyang/p/19052513)[20.RPC的三大问题：跨语言、跨平台通信的终极解决方案是如何炼成的？08-27](https://github.com/poemyang/p/19060527)[21.从文本到二进制：HTTP/2不止于性能，更是对HTTP/1核心语义的传承与革新08-28](https://github.com/poemyang/p/19061836)[22.从HPACK到多路复用，揭秘HTTP/2如何终结网络拥堵08-29](https://github.com/poemyang/p/19063734)[23.站在巨人的肩膀上：gRPC通过HTTP/2构建云原生时代的通信标准09-01](https://github.com/poemyang/p/19068100)[24.gRPC不是银弹：为内网极致性能，如何设计自己的RPC协议？09-03](https://github.com/poemyang/p/19071487)[25.从JSON到Protobuf，深入序列化方案的选型与原理09-04](https://github.com/poemyang/p/19073206)[26.“卧槽，系统又崩了！”——别慌，这也许是你看过最通俗易懂的分布式入门09-05](https://github.com/poemyang/p/19074847)[27.海量数据如何“安家”？一文读懂哈希、范围和一致性哈希三大分片策略09-08](https://github.com/poemyang/p/19079520)[28.“你还活着吗？” “我没死，只是网卡了！”——来自分布式世界的“生死契约”09-09](https://github.com/poemyang/p/19082361)[29.“凭什么说你比我先？”——没有上帝时钟，如何判断“谁先谁后”？09-12](https://github.com/poemyang/p/19087563)[30.“鸡蛋不能放一个篮子里”，如何确保千亿数据万无一失？09-15](https://github.com/poemyang/p/19092154)[31.系统里数据又“打架”了？让“少数服从多数”来终结这场混乱！09-18](https://github.com/poemyang/p/19097975)[32.技术圈的“绯闻女孩”：Gossip是如何把八卦秘密传遍全网的？09-19](https://github.com/poemyang/p/19100196)[33.绯闻女孩不只会八卦：从“验明正身”到“抓内鬼”，Gossip的进阶玩法09-20](https://github.com/poemyang/p/19101931)[34.从混沌到秩序：Java共享内存模型如何通过显式约束驯服并发？09-23](https://github.com/poemyang/p/19106679)[35.一把锁的两种承诺：synchronized如何同时保证互斥与内存可见性？09-24](https://github.com/poemyang/p/19108676)

36.从MESA模型到锁升级：synchronized性能逆袭的底层逻辑09-25

收起

管程（Monitor）是一种用于管理共享资源访问的程序结构，能确保同一时刻只有一个线程访问共享资源，解决并发编程中的互斥和同步问题。MESA模型是管程的经典实现，主要由入口等待队列和条件变量等待队列构成。
1）入口等待队列‌：确保线程互斥，多个线程试图进入管程时，仅一个线程能成功，其余线程在入口等待队列中排队。
2）条件变量等待队列‌：解决线程同步问题，线程在管程内执行时，若条件不满足需等待其他线程操作结果，则进入相应条件变量的等待队列。
当线程被notify或notifyAll唤醒后，不会立即执行，而是先进入入口等待队列竞争管程的锁。只有竞争到锁后，线程才能继续执行。因此，被唤醒的线程需循环检验条件是否满足，即采用while (条件不满足) { wait(); } 的编程范式，以避免条件不一致问题。

![image](https://img2024.cnblogs.com/blog/757914/202509/757914-20250925103236605-1938196816.png)

synchronized参考了MESA管程模型，对MESA模型进行了精简。在MESA 模型中，一个管程可以有多个条件变量，而Java中的synchronized机制只对应一个条件变量。

```
public class Test {
    public static void main(String[] args) {
        // 同步代码块方式加锁
        synchronized (Test.class) {

        }
        // 同步方法方式加锁
        func();
    }
    
    public static synchronized void func() {
    }
}
```

先使用javac编译，生成Test.class的文件。使用javap -c命令来查看字节码。

```
public static void main(java.lang.String[]);
    descriptor: ([Ljava/lang/String;)V
    flags: ACC_PUBLIC, ACC_STATIC
    Code:
      stack=2, locals=3, args_size=1
         0: ldc           #2                  // class com/tencent/trpcprotocol/dayu/identify/Test
         2: dup
         4: monitorenter
         6: monitorexit
        12: monitorexit
        15: invokestatic  #3                  // Method func:()V
        18: return

  public static synchronized void func();
    descriptor: ()V
    flags: ACC_PUBLIC, ACC_STATIC, ACC_SYNCHRONIZED
    Code:
      stack=0, locals=0, args_size=0
         0: return
      LineNumberTable:
        line 25: 0
```

从字节码可以看出，同步代码块通过monitorenter和monitorexit指令实现锁的获取与释放，而同步方法通过ACC\_SYNCHRONIZED标记隐式管理锁。无论采用哪种方式，其本质是对一个对象（Object）的监视器锁（Monitor locking）进行获取，它与synchronized 所在的对象一一对应。
当一个线程进入一个synchronized方法或代码块时，它会尝试获取该对象的监视器锁。如果锁没有被其他线程占用，该线程会获取到锁，并执行临界区的代码。如果锁已经被其他线程占用，该线程会进入阻塞（BLOCKED）状态，并进入同步队列等待锁的释放。
Java 中的 Object 类提供了wait()、notify() 和 notifyAll()方法，这些方法正是基于MESA 模型中的条件变量实现的。当线程执行wait()方法时，会释放锁，并将线程从运行状态转移到等待队列中；当线程被notify或notifyAll 唤醒后，会重新进入同步队列，参与锁的竞争，竞争成功后才能继续执行。
![image]()

**synchronized性能优化**
synchronized在早期仅支持‌重量级锁‌（Mutex locking），依赖操作系统内核态与用户态的切换，性能较差。JDK 6后引入多级锁优化。
1）偏向锁（Biased Locking）：针对同一线程反复获取同一锁的场景，偏向锁会记录首次获取锁的线程ID。后续该线程再次获取锁时，无需同步操作即可直接执行，从而消除不必要的锁竞争开销。
2）轻量级锁（Lightweight Locking）：通过‌CAS操作和锁标记位实现。线程尝试以CAS方式将锁标记为轻量级状态，若成功则直接获取锁；若失败，则通过自旋等待锁释放。此机制在竞争不激烈时避免了内核态切换，显著提升锁操作效率。
3）自旋锁（Spin Locking）：当锁获取失败时，线程会在有限次数内循环等待（自旋），而非立即进入阻塞状态。适用于锁持有时间极短的场景，通过减少线程挂起与唤醒开销提升性能。
4）锁消除（Lock Elimination）：Java虚拟机的即时编译器在运行时分析代码，若检测到某些锁操作（如对局部对象的加锁）无实际意义，会自动移除这些锁，从而优化程序性能。

**synchronized使用注意**
1）避免死锁‌：如果两个或多个线程互相等待对方释放锁，会导致死锁。由于synchronized 不提供超时机制，可以使用 JUC并发包的ReentrantLock 并设置超时时间来避免死锁。

```
public class DeadlockAvoidance {
    private final Object lock1 = new Object();
    private final Object lock2 = new Object();

    // 线程1
    public void method1() {
        synchronized (lock1) {
            System.out.println(Thread.currentThread().getName() + " locked lock1");
            synchronized (lock2) {
                System.out.println(Thread.currentThread().getName() + " locked lock2");
            }
        }
    }

    // 线程2
    public void method2() {
        synchronized (lock1) {
            System.out.println(Thread.currentThread().getName() + " locked lock1");
            synchronized (lock2) {
                System.out.println(Thread.currentThread().getName() + " locked lock2");
            }
        }
    }
}
```

‌2）锁粒度：锁粒度指的是对共享资源加锁的范围。锁的粒度过大，会导致并发性能下降；锁的粒度过小，会增加锁管理的开销。

```
public class SynchronizedBlockExample {
    private int count = 0;

    // 只同步增量操作部分，避免同步无关代码
    public void increment() {
        synchronized (this) {
            count++;
        }
    }

    public int getCount() {
        return count;
    }
}
```

3）理解可重入性：synchronized 是可重入的，也就是说，同一个线程可以多次获得同一个锁而不会发生死锁

```
public class ReentrantLockExample {
    // 如果一个线程在同步方法内部调用了另一个同步方法，它仍然能获取锁
    public synchronized void methodA() {
        System.out.println("Entering method A");
        methodB();  // 调用另一个同步方法
    }

    public synchronized void methodB() {
        System.out.println("Entering method B");
    }
}
```

**未完待续**

**很高兴与你相遇！如果你喜欢本文内容，记得关注哦**
