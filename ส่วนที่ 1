def add_product_to_list(product_list, name, quantity):
    product = {"name": name, "quantity": quantity}
    product_list.append(product)
    print(f"Added {name} with quantity {quantity} to the list.")

def show_product(product_list):
    if not product_list:
        print("No products in the list.")
    else:
        print("Product List:")
        for product in product_list:
            print(f"- {product['name']}: {product['quantity']} units")

# ตัวอย่างการทดสอบ
product_list = []
add_product_to_list(product_list, "egg", 10)
add_product_to_list(product_list, "milk", 5)
add_product_to_list(product_list, "flour", 20)
show_product(product_list)
