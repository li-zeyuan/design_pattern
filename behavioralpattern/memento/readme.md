# 备忘录模式
### 定义
- 通过记录对象的变化状态，以便需要时，将该对象状态进行恢复
### 成员
- 发起人类：是需要被记录的对象，记录内部状态信息，提供状态保存，状态恢复等方法
- 备忘录类：记录着发起人的状态变化信息
- 管理者类：对备忘录进行保存和获取备忘录功能