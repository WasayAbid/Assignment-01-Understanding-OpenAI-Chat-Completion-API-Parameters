# OpenAI Chat Completion API Parameters

## **1. Messages**
- **Definition**: Inputs and outputs exchanged in a conversation, including roles like user, assistant, or system.
- **Example**:  
  - User: "Tell me a joke."  
  - Assistant: "Why don’t scientists trust atoms? Because they make up everything!"

## **2. Model**
- **Definition**: The AI system used, such as GPT-4 or GPT-3.5, trained for specific tasks.
- **Example**:  
  - Translating "Bonjour" to "Hello."

## **3. Max Completion Tokens**
- **Definition**: Maximum number of tokens (words and symbols) the model can generate.
- **Example**:  
  - With a 100-token limit, a summary stops at 100 tokens.

## **4. n**
- **Definition**: Number of responses generated for the same input.
- **Example**:  
  - Asking "Why exercise?" with `n=2` might yield:  
    1. "It boosts health."  
    2. "It improves mood."

## **5. Stream**
- **Definition**: Sends responses incrementally instead of all at once.
- **Example**:  
  - A chatbot replying as it types.

## **6. Temperature**
- **Definition**: Controls randomness; lower values make responses precise, higher values make them creative.
- **Example**:  
  - A low temperature generates predictable answers, while a high one might add humor or surprise.

## **7. Top_p**
- **Definition**: Limits token choices to the most probable ones. Lower values focus responses; higher values allow variety.
- **Example**:  
  - With top_p=0.1, the model sticks to the safest options.

## **8. Tools**
- **Definition**: External functions enhancing the model, like accessing APIs or running code.
- **Example**:  
  - A chatbot using a weather API to give live forecasts.
