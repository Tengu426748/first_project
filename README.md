# Мой первый проект на GitHub
___
## Тест Markdown
___
### Все мои знания
___
**bold** *itallic* ***text*** ~~text~~
***~~abrakadabra~~*** :white_check_mark:
> 1 Цитата
> > 2 Цитата 2-го уровня
> 
> 
> 
`Код` моего проекта



```python
def snejinka(iterations = 4, axiom = "F--F--F", rules = {"F":"F+F--F+F"}, angle = 60, length=8, size=2, y_offset=0, x_offset=0, offset_angle=0, width=450, height=450):

    
    inst = create_l_system(iterations, axiom, rules)
    
    t = turtle.Turtle()
    wn = turtle.Screen() #комментарий
    wn.setup(width, height)
    t.up()
    t.backward(-x_offset)
    t.left(90)
    t.backward(-y_offset)
    t.left(offset_angle)
    t.down()
    t.speed(0)
    t.pensize(size)
    draw_l_system(t, inst, angle, length)
    t.hideturtle()

    wn.exitonclick()
```
- [x] Task List
- [ ] Task


[Мой гит профиль](https://github.com/Tengu426748)

![Мечта](https://baulo.club/uploads/posts/2023-03/1678911585_baulo-club-p-dizain-komnati-programmista-krasivo-2.jpg "dream")