## 1.1 Interrupciones Externas

| Periférico   | Número de interrupciones | Descripción                                                                  |
|------------- |-------------------------:|------------------------------------------------------------------------------|
| INT (RB0/INT)| 1                       | Activada con un flanco de entrada en el pin RB0/INT (borde de subida/bajada). |

---

## 1.2. Temporizadores (Timers)

| Periférico | Número de interrupciones | Descripción                                                                     |
|----------- |-------------------------:|---------------------------------------------------------------------------------|
| TMR0       | 1                       | Genera interrupción cuando TMR0 desborda (al llegar a 255 en modo 8 bits).      |
| TMR1       | 1                       | Genera interrupción cuando TMR1 desborda (16 bits).                             |
| TMR2       | 1                       | Genera interrupción cuando TMR2 alcanza el valor en PR2 (Registro de Período).  |

---

## 1.3. Módulo CCP (Capture/Compare/PWM)

| Periférico                   | Número de interrupciones | Descripción                               |
|----------------------------- |-------------------------:|-------------------------------------------|
| CCP1 (Capture/Compare/PWM)  | 1                       | Interrupción de captura/compare/PWM.      |
| CCP2 (Capture/Compare/PWM)  | 1                       | Similar a CCP1, pero en un canal diferente|

---

## 1.4. Módulo USART (Comunicación Serial)

| Periférico | Número de interrupciones | Descripción                                                                 |
|----------- |-------------------------:|-----------------------------------------------------------------------------|
| USART      | 1                       | Se activa cuando hay recepción o transmisión lista en el registro de datos. |

---

## 1.5. Módulo SPI (Serial Peripheral Interface)

| Periférico | Número de interrupciones | Descripción                                                      |
|----------- |-------------------------:|------------------------------------------------------------------|
| SPI        | 1                       | Se activa cuando la transferencia de un byte se ha completado.   |

---

## 1.6. Módulo I2C (Inter-Integrated Circuit)

| Periférico | Número de interrupciones | Descripción                                                                 |
|----------- |-------------------------:|-----------------------------------------------------------------------------|
| I2C        | 1                       | Se activa cuando se completa una transmisión/recepción en el bus I2C.       |

---

## 1.7. Convertor Analógico-Digital (ADC)

| Periférico | Número de interrupciones | Descripción                                                   |
|----------- |-------------------------:|---------------------------------------------------------------|
| ADC        | 1                       | Se activa cuando la conversión analógica-digital ha finalizado.|

---

## 1.8. Interrupciones por Cambio de Estado en los Pines

| Periférico       | Número de interrupciones | Descripción                                                            |
|----------------- |-------------------------:|------------------------------------------------------------------------|
| PORTB (RB4–RB7)  | 1                       | Se activa cuando ocurre un cambio de estado en los pines RB4 a RB7.    |

---

## 1.9. Watchdog Timer (WDT)

| Periférico | Número de interrupciones | Descripción                                                  |
|----------- |-------------------------:|--------------------------------------------------------------|
| WDT        | 1                       | Se activa cuando el temporizador Watchdog expira y reinicia el sistema. |
