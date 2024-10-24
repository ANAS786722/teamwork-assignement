# teamwork-assignement
# Teamwork by Anas & Fahad:                                            # improved version by Fahad
                                                                        def display_options():
                                                                            print("Select an option:")
                                                                            print("1. Learn Python")
                                                                            print("2. Learn Java")
                                                                            print("3. Go swimming")
                                                                            print("4. Have dinner")
                                                                            print("5. Go to bed")
                                                                            print("6. Go to gym")
                                                                            print("0. Exit")
                                                                        
                                                                        
                                                                        def handle_choice(choice):
                                                                            options = {
                                                                                '1': "You selected: Learn Python",
                                                                                '2': "You selected: Learn Java",
                                                                                '3': "You selected: Go swimming",
                                                                                '4': "You selected: Have dinner",
                                                                                '5': "You selected: Go to bed",
                                                                                '6': "You selected: Go to gym",
                                                                                '0': "Exiting the program. Goodbye!"
                                                                            }
                                                                        
                                                                            if choice  in options:
                                                                                print(options[choice])
                                                                            else:
                                                                                print("Invalid choice. Please try again.")
                                                                        
                                                                        while True:
                                                                            display_options()
                                                                            choice = input("Enter your choice: ")
                                                                        
                                                                            if choice == '0':
                                                                                handle_choice(choice)
                                                                                break
                                                                            else:
                                                                                handle_choice(choice)
                                                                                break
def display_options():
    print("Select an option:")
    print("1. Learn Python")
    print("2. Learn Java")
    print("3. Go swimming")
    print("4. Have dinner")
    print("5. Go to bed")
    print("6. Go to gym")
    print("0. Exit")

while True:
    display_options()
    choice = input("Enter your choice: ")

    if choice == '1':
        print("We selected, Learn Python")
    elif choice == '2':
        print("We selected, Learn Java")
    elif choice == '3':
        print("We selected, Go swimming")
    elif choice == '4':
        print("We selected, Have dinner")
    elif choice == '5':
        print("We selected, Go to bed")
    elif choice == '6':
        print("We selected, Go to gym")
    elif choice == '0':
        print("Exiting the program. Goodbye!")
        break
    else:
        print("Invalid choice. Please try again.")
