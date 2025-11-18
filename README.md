from datetime import datetime
import rando

def new_things_every_day_25():
    now = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    message = random.choice([
        "Show up today — even one line matters.",
        "Keep coding, keep leveling up.",
        "Daily habits create lifelong skills.",
        "Your consistency is your superpower.",
        "Every commit is a step forward."
    ])
    print(f"[#25] {message} — {now}")

if __name__ == "__main__":
    new_things_every_day_25()
