# shooterr
back = (200,255m255)
win_width=600
win_heig = 500
window = display.set_mode((win_width,win_height))
window.fill(back)

game = True 
finish = False
clock=time.Clock()
FPS = 60

raket1 = Player('racket.png',30,200,4,50,150)
raket2 = Player('racket.png',520,200,4,50,150)
ball = GameSprite('tenis_ball.png,',200,200,4,50,50)

font.init()
font = font.font ('calibri.ttf',35)
lose1 = font.render('PLAYER 1 LOSE!',teue,(180.0.0))
lose2 =font.render('PLAYER 12 LOSE!',teue,(180.0.0))
