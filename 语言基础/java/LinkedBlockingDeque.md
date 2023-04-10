# Deque 
双端队列 Deque 是一个线程安全的队列，它可以在队列的头部和尾部添加和删除元素。
它是一个接口，它的实现类有 ArrayDeque 和 LinkedBlockingDeque。

## ArrayDeque
ArrayDeque 是一个基于数组的双端队列，它的底层是一个数组，它的容量是可变的，当队列满了的时候，它会自动扩容。
它的实现类是 AbstractCollection，它实现了 Deque 接口。

## LinkedBlockingDeque
LinkedBlockingDeque 是一个基于链表的双端队列，它的底层是一个链表，它的容量是可变的，当队列满了的时候，它会自动扩容。
它的实现类是 AbstractCollection，它实现了 Deque 接口。

# Queue
队列 Queue 是一个线程安全的队列，它只能在队列的尾部添加元素，在队列的头部删除元素。
它是一个接口，它的实现类有 ArrayBlockingQueue 和 LinkedBlockingQueue。

## LinkedBlockingQueue
LinkedBlockingQueue 是一个基于链表的阻塞队列，它的底层是一个链表，它的容量是可变的，当队列满了的时候，它会自动扩容。
它的实现类是 AbstractQueue，它实现了 BlockingQueue 接口。

## ArrayBlockingQueue
ArrayBlockingQueue 是一个基于数组的阻塞队列，它的底层是一个数组，它的容量是固定的，当队列满了的时候，它会阻塞。
它的实现类是 AbstractQueue，它实现了 BlockingQueue 接口。
