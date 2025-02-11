# Val
This simple and fun web app is built using Streamlit, where you can propose a special question to someone in a fun and interactive way. The app uses cute visuals, custom text styling, and a bit of logic to engage with the user.

Features
Display a customized message asking the question "Will you be my Valentine?"
A cute animated image from Podgorica to warm up the user.
Buttons for the user to respond with either "Yes! 💘" or "No...😡".
Confetti and success message when the user says "Yes!"
The app handles session state to track the user’s response and displays appropriate reactions.

Run the app with Streamlit:

How It Works
The app displays a styled title and a warm message with a cute image from Podgorica.
An expandable section gives a more casual setup for the question.
Once the user clicks on one of the responses, the app will either show a success message with balloons or prompt the user to try again with a playful tone.
Customization
You can easily personalize the app by:

Changing the question in the st.write() function.
Replacing the image URL with any other image or GIF in the st.image().
Modifying the button labels and responses for different occasions.
