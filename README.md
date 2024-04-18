![GitHub Banner](https://github.com/Jadieljade/Jadieljade/blob/main/banner.gif)

<h1 align="center">Hi there, I'm <a href="https://github.com/Jadieljade">Jadiel Njuguna (jadieljade) </a>!</h1>
<h3 align="center">I am a data science and machine learning enthusiast trying to build real-world ML products. I also write blogs about data science and machine learning </h3>


````python
class Developer:
    def __init__(self, name):
        self.name = name
        self.coding = True
    
    def is_coding(self):
        return self.coding
    
    def listen_to_music(self):
        print(f"{self.name} is listening to music.")
    
    def open_stack_overflow(self):
        print(f"{self.name} is browsing Stack Overflow.")
    
    def drink_coffee(self):
        print(f"{self.name} is drinking coffee.")

name = 'Jadiel'
dev = Developer(name)

while dev.is_coding():
    dev.listen_to_music()
    dev.open_stack_overflow()
    dev.drink_coffee()

