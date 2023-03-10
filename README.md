# Моделирование ответа государства на военное вторжение

В данной работе будет использоваться математическая модель иммунного ответа организма на вторжение инфекции Ю.И. Неймарка. Она была разработана для исследований заболеваний инфекционных заболеваний человека, однако её можно интерпретировать в совершенно разных областях науки.

 ̇x = λx-axy/(1+αx)-ε ̅x^2      
 
 ̇y = {((-b ̅xy)/(1+αx)+w=K   если y>0 или y=0 и K>0;
 ̇y = 0                      если y=0 и K=0
 
 τ ̇w + w= {(0                  при x≤x_0
 τ ̇w + w=  ̅Bz(z_0-z)(x+βx^2 )  при x>x_0
 
 ̇z = {(c(z_0-z)/(1+ψx)-ⅆy-ⅇ=F при z>0 или z=0,F≥0
 ̇z = 0                        при z=0,F<0              
 
 В данной работе рассматривается упрощённая система:
 
  ̇x = x-xy/(1+x)- ̅εx^2  
  ̇y = 0                                  при x>x_0   при y=0 и K=0
  ̇y = (-bxy)/(1+x)                       при x≤x_0  и при y>0 или y=0 и K>0
  ̇y = (-bxy)/(1+x)+B(x+βx^2 )=K          при x>x_0  и при y>0 или y=0 и K>0
 
В данном случае x описывает изменение сил вторгающейся стороны, y – реакция властей захватываемого государства, x_0- порог, при котором начинаются серьёзные военные действия. Например, противостояние разведки, стычки на границах нельзя назвать полномасштабным вторжением, однако эти действия влияют на численность обеих армий. 
Первое уравнение показывает, как силы завоевателя снижаются при взаимодействии с армией обороняющейся стороны, а ещё показывают, что при завоевании всё большего количества территорий, активность войны снижается, так как уже завоёванные территории занять уже нельзя.
Константа K в данной интерпретации системы показывает потенциал страны, сопротивление завоеванию.  Первая часть второго уравнения показывает, что если нет ни потенциала, ни армии, то сопротивления завоеванию тоже не будет. Вторая часть говорит о том, что, пока нет активных военных действий, взаимодействие с агрессором будет снижать силу страны. Третья же часть показывает ответ при открытом нападении, с тем условием, что или уже есть активная армия, или есть потенциал для сопротивления.
