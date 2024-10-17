def calculate_motion():
    print("Motion Analysis Program")
    
    # User input
    try:
        x0 = float(input("Enter the initial position (x0) in meters: "))
        v0 = float(input("Enter the initial velocity (v0) in meters/second: "))
        a = float(input("Enter the acceleration (a) in meters/second^2: "))
        t = float(input("Enter the time (t) in seconds: "))
    except ValueError:
        print("Invalid input! Please enter numerical values.")
        return

    # Calculations
    # Final position (x)
    x = x0 + v0 * t + 0.5 * a * t**2

    # Final velocity (v)
    v = v0 + a * t

    # Acceleration (a) is constant and provided by the user

    # Output results
    print(f"\nResults:")
    print(f"Final Position (x): {x:.2f} meters")
    print(f"Final Velocity (v): {v:.2f} meters/second")
    print(f"Acceleration (a): {a:.2f} meters/second^2")

if __name__ == "__main__":
    calculate_motion()
