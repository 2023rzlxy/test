    class Restaurant:
        def __init__(self,restaurant_name,cuisine_type):
            self.restaurant_name = restaurant_name
            self.cuisine_type = cuisine_type
    
        def describe_restaurant(self):
            print(self.restaurant_name)
            print(self.cuisine_type)

        def open_resturant(self):
            print(self.restaurant_name.title() + "'s resturant is currently open for business!")

    delicious_restaurant = Restaurant("laoliu","daily food")
    delicious_restaurant.describe_restaurant()
    delicious_restaurant.open_resturant()
