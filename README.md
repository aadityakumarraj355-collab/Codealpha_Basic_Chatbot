# Codealpha_Basic_Chatbot
def chatbot():
    print("Chatbot: Hello! I am a simple rule-based chatbot. Type 'bye' to exit.")
        print("-" * 50)
            
                while True:
                        # Get input from the user and normalize it (lowercase, strip whitespace)
                                user_input = input("You: ").strip().lower()
                                        
                       # Rule-based matching
                         if "hello" in user_input or "hi" in user_input:
                             print("Chatbot: Hi!")
                                                                                
                                                                                                 elif "how are you" in user_input:
                                                                                                    print("Chatbot: I'm fine, thanks!")
                                                                                                                
                                                                                                elif "bye" in user_input:
                                                                                                       print("Chatbot: Goodbye!")
                                                                                                            break
                                                                                                # Exit the loop and end the program
                        else:
                           print("Chatbot: I'm sorry, I didn't quite understand that. Try saying 'hello', 'how are you', or 'bye' )
                       # Run the chatbot function
                           if __name__ == "__main__":
                               chatbot()