# Fibonacci.py

def fibonacci(n):
    seq = [0, 1]
    while len(seq) < n:
        seq.append(seq[-1] + seq[-2])
    return seq

# Teste
if __name__ == "__main__":
    num = int(input("Digite a quantidade de termos da sequência: "))
    print(f"Sequência de Fibonacci com {num} termos: {fibonacci(num)}")
