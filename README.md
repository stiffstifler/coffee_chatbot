# Coffee Bot  

## Overview  
Coffee Bot is an interactive chatbot designed to streamline the process of ordering drinks at a café. The bot guides users through a step-by-step drink selection process, offering customizable options for drink types, sizes, and special additions.  

## Features  
- **Interactive Drink Ordering**: Users can choose from a variety of drink types, including brewed coffee, mocha, and latte.  
- **Customizable Options**:  
  - Drink sizes: Small, Medium, Large.  
  - Special options for mochas and lattes, such as peppermint flavor or different milk types.  
- **Order Management**:  
  - Users can order multiple drinks in one session.  
  - A summary of the complete order is displayed before finalizing.  
- **User-Friendly Interface**: Clear prompts and error messages ensure smooth interaction with the chatbot.  

## Technologies and Structure  
- **Python**: The project is implemented using Python, focusing on modular design.  
- **Utils Module**: Helper functions like `print_message`, `get_size`, and `order_latte` are separated into a utility file for cleaner code organization.  

## How It Works  
1. The chatbot welcomes the user and starts the drink selection process.  
2. Users are prompted to:  
   - Select a drink size.  
   - Choose a drink type and any special additions (e.g., peppermint mocha or milk type for lattes).  
3. Users can add multiple drinks to their order.  
4. Once all drinks are selected, the chatbot confirms the order and collects the user's name.  

## Example Interaction  
```text
Welcome to the cafe!  
What size drink can I get for you?  
[a] Small  
[b] Medium  
[c] Large  
> b  
What type of drink would you like?  
[a] Brewed Coffee  
[b] Mocha  
[c] Latte  
> c  
And what kind of milk for your latte?  
[a] 2% milk  
[b] Non-fat milk  
[c] Soy milk  
> a  
Alright, that's a medium latte!  
Would you like to order another drink? (y/n)  
> n  
Okay, so I have:  
- medium latte  
Can I get your name please?  
> John  
Thanks, John! Your order will be ready shortly.
```

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/stiffstifler/coffee-bot.git  
2. Run the script:
    ```bash
    python script.py  

## Future Improvements
- Add a database to store orders for analytics.
- Expand the menu with additional drink types and customization options.
- Implement natural language processing for more flexible user interaction.