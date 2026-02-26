Global Wanderer AI is a full-stack travel app I created using Gemini to help people choose and plan thier vacations. 
Using this app is fairly easy. After accessing it through the URL, the user takes a short quiz based on thier wants and needs in a trip.
Then, they are shown the top three places that align with thier choices and the current weather in those locations.
Then, they have the ability to click the "Explore This Trip" button which provides a gemini-powered itinerary based on thier choices and chosen location.
I am most proud of the incorporation of a LLM into my project as this was the most dificult aspect. It adds another level of complexity and 
customization. I spent about a day and a half debugging this section of my code solely and trying out many different ways to connect
to Gemini in order to create an itinerary. In order to run this locally, you would need to have your own API keys for OpenWeather and Gemini
set up in an .env file. Then you would use 'from dotenv import load_dotenv' and 'load_dotenv()' to access these keys. The two API keys I am using
are kept secret through render. My personal API keys are not avalible through my repository, render, or anyone else that is not me. Additionally,
I am really proud of how the UI looks. I spent a lot of time refining this as I don't really like how AI designs websites. I tried to make it more
visually appealing and more user-friendly. I heavily modified lots of my code. The most important segments are the quiz questions/responses,
the set up of visual aspects (like text, theme, color, and formatting), and most importantly, I spent a lot of time changing and modifying my backend
to communicate with the APIs correctly and efficiently. Enjoy!
