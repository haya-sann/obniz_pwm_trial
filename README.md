# obniz_pwm_trial
Experiment of a program for smooth light intensity adjustment by PWM using obniz block program

obnizのPWM機能を使って照明の明るさをコントロールする実験。子供たちにも遊んでもらうためにブロックプログラムにした。
スムーズな光量変化を目指して、デューティ比は整数ではなく小数点数値で与える。

変数powerがPWMのディーティー比を決めるパラメータ。
初期値を30/100で与えた後、ボタン操作で照明の明るさを変える。

![](./obnizPWM-01-19%2022.56.36.png)

コードはこちら

https://github.com/haya-sann/obniz_pwm_trial/blob/master/obniz_2020_1_19_18_41_20blockprogram.xml
