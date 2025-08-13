# random_quotes.py
import random

quotes = [
    "امروز بهترین روز برای شروعه.",
    "با هر قدم، به هدفت نزدیک‌تر میشی.",
    "آرام ولی پیوسته حرکت کن.",
    "هر چالش فرصتی برای رشد است.",
    "تو توانایی انجامش رو داری!"
]

def show_random_quote():
    print("\n✨ نقل‌قول الهام‌بخش امروز:")
    print("»", random.choice(quotes), "\n")

if __name__ == "__main__":
    show_random_quote()
