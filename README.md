# Even-Odd-Game-Winner
 "Even-Odd Game," Raj and Tia alternate turns subtracting an integer   a from Tia's chosen integer  n. Raj must choose even a, while Tia must choose odd  a. The player unable to find a valid   a loses. If   n is even, Raj wins; if odd, Tia wins. The code determines the winner based on n's parity, outputting "Raj" or "Tia" accordingly.

def even_odd_game_winner(n):
    return "Raj" if n % 2 == 0 else "Tia"

n = int(input())

print(even_odd_game_winner(n))
