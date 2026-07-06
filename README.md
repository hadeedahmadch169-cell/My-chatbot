# My-chatbotprint("=== Cashier Assistant Chatbot ===")
print("Ask me about M. Khalid Nadeem, cashier duties, working hours, skills, payments, or customer service.")

while True:
    user = input("You: ").lower()

    if "name" in user:
        print("Bot: My father's name is M. Khalid Nadeem.")

    elif "occupation" in user or "job" in user:
        print("Bot: He works as a Cashier at METRO Mall, Multan.")

    elif "working hours" in user or "hours" in user or "shift" in user:
        print("Bot: A cashier typically works 8 to 9 hours per day and may have morning, evening, or weekend shifts.")

    elif "responsibility" in user or "duties" in user:
        print("Bot: Cashiers scan products, prepare bills, accept payments, issue receipts, and assist customers.")

    elif "payment" in user:
        print("Bot: Cashiers handle cash, debit cards, credit cards, and digital payments.")

    elif "receipt" in user:
        print("Bot: A receipt is given to customers after a successful transaction.")

    elif "skills" in user:
        print("Bot: Important skills include communication, honesty, computer knowledge, mathematics, and customer service.")

    elif "customer" in user:
        print("Bot: Cashiers help customers during checkout and answer billing-related questions.")

    elif "rules" in user:
        print("Bot: Cashiers should be punctual, polite, accurate, and follow company policies.")

    elif "security" in user or "safety" in user:
        print("Bot: Cashiers must keep cash secure, verify transactions carefully, and report suspicious activities.")

    elif "workplace" in user:
        print("Bot: M. Khalid Nadeem works at METRO Mall in Multan.")

    elif "metro" in user:
        print("Bot: METRO Mall is a large retail store where cashiers help customers complete their purchases.")

    elif user == "bye":
        print("Bot: Thank you for using Cashier Assistant Chatbot. Goodbye!")
        break

    else:
        print("Bot: Sorry, I don't know the answer to that question.")
