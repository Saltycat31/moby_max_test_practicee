# moby_max_test_practicee
no
import random

def get_random_answer():
    return random.randint(1, 4)

def simulate_moby_max_test(total_questions=100):
    correct_answers = total_questions // 2

    for _ in range(total_questions):
        question_number = _ + 1
        selected_answer = get_random_answer()
        print(f"Question {question_number}: Selected answer {selected_answer}")

    print(f"Total correct answers: {correct_answers}/{python moby_max_test_simulator.py 50}")

if __name__ == "__main__":
    simulate_moby_max_test()
