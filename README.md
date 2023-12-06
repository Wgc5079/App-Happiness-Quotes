# App-Happiness-Quotes

The application came from the idea of being able to help people with problems and using the application they can create or have some quotes that cheer them up during the day. 

When you start the application, the first thing it will ask the user would be if the user want to write a quote which is number 1 or read one that is already saved in the database which is number 2 and there would be another question that would be exit which is number 3 based on the user's response, the application would work somewhat differently after the user chose the aplication will ask the user's name.

1.If the user responded by writing a quote which is number 1, the application would work this way. After responding, the user would have to write the quote and after it finished it, it would be saved in the database. 

2.If the user responded to read a quote wich is number 2, the application would work this way. After having responded, the application would review its database and choose an quote and then the application would show an quote to the user. 

3.If the user responded exit which is number 3, the application would work this way. After answering the application, it would finish working. 

This app helps people write their own quotes or quotes they find on the internet. 

This application is to make people happy when they have a problem, they can read a happy quote and be able to improve their days. 

Users can use the app every day and have a quote so they can start the day and try to follow the quote that day. 

This app allows the user to add their own happiness quote to the database. The quote can be anything and anything they like; the quote will be stored and can be displayed whenever the user wants to access it. 



# Explanation of the code

class called HappinessQuotes,for managing and displaying happiness quotes

The HappinessQuotes class has the following methods:
We __init__ method to initializes an empty dictionary self.quotes to store the quotes.
Method add_quotes takes a name and a quote as input and adds the quote to the dictionary of quotes. If it already exists in the dictionary, the quote is appended to the existing list of quotes for that name. If the name does not exist, a new one created in the dictionary. (Attributes: name, quote)
Method display_quotes iterates through the dictionary of quotes and displays the quotes for each name.
Method main_menu provides a simple text-based menu for the user to interact with the app. It allows the user to add a new quote, display existing quotes, or exit the app.

__name__ == "__main__" creates an instance of the HappinessQuotes class and calls the main_menu method to start the app.

When the app is run, it presents a menu to the user, allowing them to add new happiness quotes, display existing quotes, or exit the app. The quotes are stored in a dictionary where the key is the name of the person and the value is a list of their quotes. The app provides a simple way to manage and display happiness quotes.
