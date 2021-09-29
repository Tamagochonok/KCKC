# KCKC
Туболов КН-19-1

Список параметров
x --> первая координта( задаётся в десятичной системе счисления; от 0 до 800 )

y --> вторая координта( задаётся в десятичной системе счисления; от 0 до 600)

x1 --> третья координата( задаётся в десятичной системе счисления; от 0 до 800)

y1 --> четвёртая координата( задаётся в десятичной системе счисления;от 0 до 600)

w --> ширина объекта ( задаётся в десятичной системе счисления; от 0 до 800 )

h --> высота объекта ( задаётся в десятичной системе счисления; от 0 до 600)

radx --> первый радиус ( задаётся в десятичной системе счисления; от 0 до 300)

rady --> второй радиус ( задаётся в десятичной системе счисления; от 0 до 300)

цвет --> формат RGB565 ( указывать в виде строкового представлений шестнадцатиричниго цисла)

 _ --> разделитель параметров
 
Очистить дисплэй(залив цветом):
clear display:color --> FD:цвет

Пример команды: 	FD:319F

Нарисовать точку(пиксель):
draw pixel: x0, y0, color --> PI:x_y_цвет

Пример команды:	PI:100_200_319F

Нарисовать линию:
draw line: x0, y0, x1, y1, color --> LI:x_y_x1_y1_цвет

Пример команды:	LI:100_200_150_250_319F

Нарисовать четырёхугольник:
draw rectangle: x0, y0, w, h, color --> REC:x_y_w_h_цвет

Пример команды:	REC:100_200_150_250_319F

Нарисовать заполненный четырёхугольник:
fill rectangle: x0, y0, w, h, color --> FREC:x_y_w_h_цвет

Пример команды:	FREC:100_200_150_250_319F

Нарисовать элипс:
draw ellipse: x0, y0, radius_x, radius_y, color --> EL:x_y_radx_rady_цвет

Пример команды:	EL:100_200_20_30_319F

Нарисовать заполненный элипс:
fill ellipse: x0, y0, radius_x, radius_y, color --> FEL:x_y_radx_rady_цвет

Пример команды:	FEL:100_200_20_30_319F
