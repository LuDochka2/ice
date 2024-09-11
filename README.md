# iceclass IceFormation:
    def __init__(self, temperature):
        self.temperature = temperature  # Temperature in Celsius

    def freeze(self):
        if self.temperature <= 0:
            print("The water has frozen into ice!")
        else:
            print("The water is still liquid.")

# Example usage:
water = IceFormation(temperature=-5)  # Set the temperature below freezing point
water.freeze()
