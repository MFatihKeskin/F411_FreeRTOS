# F411_FreeRTOS
### İt's my FreeRTOS Test &amp; Task development repo

##### User LD3
The orange LED is a user LED connected to the I/O PD13 of theSTM32F411VET6.
##### User LD4
The green LED is a user LED connected to the I/O PD12 of theSTM32F411VET6.
##### User LD5
The red LED is a user LED connected to the I/O PD14 of the STM32F411VET6.
##### User LD6
The blue LED is a user LED connected to the I/O PD15 of theSTM32F411VET6
##### B1 USER
User and Wake-Up button connected to the I/O PA0 of the STM32F411VET6

##### USART 2
PA3->Rx
PA2->Tx
Baudrate->115200
WordLength->8Bits(İncluding Parity)
StopBits->1
Parity->None

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### DEFAULT TASK
Orange Led Blink 100ms delay and osDelay(1)
#### TASK 2
Green Led Blink 200ms delay and osDelay(1)
#### TASK 3
Red Led Blink 300ms delay and osDelay(1)
#### TASK 4
Blue Led Blink 400ms delay and osDelay(1)
#### TASK5
USART Communication via USART 2
