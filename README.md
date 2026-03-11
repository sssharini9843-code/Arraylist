class ArrayListADT:
    def __init__(self):
        self.items = []

    def insert(self, value):
        self.items.append(value)

    def delete(self, value):
        if value in self.items:
            self.items.remove(value)
        else:
            print(f"Value {value} not found.")

    def display(self):
        print("Array List:", self.items)



output:
Array List: [10, 20, 30]
Array List: [10, 30]


