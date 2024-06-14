//# whispering-winds
//the wind's whispers guide protagonists through ancient forests and mystical seas
import random

def whispering_winds_story():
    print("Welcome to Whispering Winds...")
    print("You find yourself standing at the edge of a serene forest, where the winds whisper secrets of the past and future.")

    while True:
        print("\nThe winds whisper softly...")
        input("Press Enter to listen closely...")

        event = random.randint(1, 3)

        if event == 1:
            print("You hear echoes of ancient tales, carried by the winds.")
        elif event == 2:
            print("The winds reveal a hidden path through the forest.")
        elif event == 3:
            print("A gentle breeze brings a message of hope and renewal.")

        choice = input("\nContinue to listen to the whispers? (yes/no): ").lower()
        if choice != 'yes':
            break

    print("\nThe whispers of the winds fade away...")
    print("Thank you for listening to the tales of Whispering Winds.")

# Start the storytelling
whispering_winds_story()
