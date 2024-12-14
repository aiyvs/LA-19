# LA-19

class Ice_cream:
    def __init__(self, chocolate, whole_milk, heavy_cream):
        self.chocolate = chocolate
        self._whole_milk = whole_milk
        self.__heavy_cream = heavy_cream
        
    def __str__(self):
        return f"My ice cream has {self.chocolate}, {self._whole_milk}, {self.__heavy_cream} ingredients."
    
choco = Ice_cream("Chocolate", "Whole Milk", "Heavy Cream")
mat = Ice_cream("Matcha", "Whole Milk", "Heavy Cream")
van = Ice_cream("Vanilla", "Whole Milk", "Heavy Cream")
    
print(choco)
print(mat)
print(van)
print(choco._Ice_cream__heavy_cream)
