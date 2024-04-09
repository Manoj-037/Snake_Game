# Snake_Game
Using Python language with importing , Turtle(Python library) and Python random module in IDLE python || VS_code || Jupyter Notebook || others
def get_random_food_pos():
    x = random.randrange(1,250)#(-WIDTH / 2 + FOOD_SIZE, WIDTH / 2 - FOOD_SIZE)
    y = random.randrange(1,250)#(-HEIGHT / 2 + FOOD_SIZE, HEIGHT / 2 - FOOD_SIZE)
    return (x, y)
    In the above function,you can use this expression(-WIDTH / 2 + FOOD_SIZE, WIDTH / 2 - FOOD_SIZE) but
    'float' object cannot be interpreted as an integer so that, I have declare it in randrange(): It makes the target within the range
