# STM32F100RBT_robot
三轮全向轮小车stm32驱动层
## 接线定义
| stm32F100RBT6 |  |  |
| --- | --- | --- |
| 功能 | 引脚 |  |
| 数据传输 | uart2-TX | PA2 |
|  | uart2-RX | PA3 |
| m1速度脉冲反馈 | A | PA6 |
|  | B | PA7 |
| m1速度控制 | PWM | PA1 |
| m1方向控制  | 正转 | PC6 |
|  | 反转 | PC7 |
| m2速度脉冲反馈 | A | PB6 |
|  | B | PB7 |
| m2速度控制 | PWM | PB10 |
| m2方向控制 | 正转 | PB12 |
|  | 反转 | PB13 |
| m3速度脉冲反馈 | A | PA8 |
|  | B | PA9 |
| m3速度控制 | PWM | PB11 |
| m3方向控制 | 正转 | PB14 |
|  | 反转 | PB15 |
