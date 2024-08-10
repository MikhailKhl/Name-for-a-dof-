import random

def choose_dog_name():
    dog_names = ["Buddy", "Max", "Charlie", "Bailey", "Lucy", "Daisy", "Luna", "Rocky", "Coco", "Milo"]
    return random.choice(dog_names)

print("Your dog's name is:", choose_dog_name())
