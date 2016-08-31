    def temp():
        degrees = int (input("So what’s the temperature outside?"))
        if degrees > 60 and degrees < 90:
            print("Nice and warm, huh?")
        elif degrees >=90:
            print("That is hot!")
        elif degrees < 60:
            print("That’s a little chilly...")
    temp()
