import tkinter as tk
from tkinter import messagebox
from random import randint

def run_program():
    n=randint(1, 350)
    if n<300:
        A = [
        "Ого, ром! - Жак Фреско",
        "Ладно. - Жак Фреско",
        "Съел деда. - Жак Фреско",
        "Hello, doomer. - Жак Фреско",
        "Кто прочитал, тот экстремист. - Жак Фреско",
        "... - Жак Фреско",
        "Мемы делают нас огузками. - Жак Фреско",
        "Куда сувать. - Жак Фреско",
        "Лучше выпить литр пива, чем не выпить литр пива. - Джейсон Стетхем",
        "Шаг влево, шаг вправо - два шага. - Джейсон Стетхем",
        "Волк слабее льва и тигра, но в цирке не выступает. - Джейсон Стетхем",
        "Упал - вставай. Встал - упай. Упай - чокопай. Не суди, не гуди, не будай вада буди дабуди дабудай. - Джейсон Стетхем",
        "Абоба. - Вика",
        "Репорт лес. - Хасаги",
        "Ой. - Лёша",
        "Топ диф. - Хасаги",
        "0-10 паверспайк. - Лёша",
        "КТО ИГРАЛ НА ДЖЕТТ?! - Пеп",
        "АРИНА УЛЬТУЙ. - Тимур",
        "Во всём виноват лес. - Лёша", 
        "bruh you fr rn? – Pep", 
        "imnotdealingwiththisbye – Pep", 
        ]
        result = A[randint(0,21)]
    if n==300:
        result = "Сегодня без цитаты."
    if n>300:
        B = [ "грива", " хвост", "уши", "нос", "глаза", "лапы"]
        C = [ "тигра", "медведя", "льва", "волка", "пса", "ягуара"]
        bp = B[randint(0, 5)]
        an = C[randint(0, 5)]
        result = {f}'У вас сегодня {bp} прямо как у {an}'
    output_window = tk.Toplevel(root)
    output_window.title("Цитата дня!")
    output_label = tk.Label(output_window, text=result)
    output_label.pack(padx=20, pady=20)

root = tk.Tk()
root.title("Цитата дня!")

run_button = tk.Button(root, text="Сгенерировать!", command=run_program)
run_button.pack(padx=20, pady=20)

root.mainloop()
