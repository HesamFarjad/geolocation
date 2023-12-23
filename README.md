# geolocation
This repository contains a React functional component, useGeolocation, designed to simplify the retrieval of a user's geolocation.


The hook manages state variables for loading status, current position, and potential errors during the geolocation request. The useGeolocation hook is encapsulated in the main component, App, showcasing its usage in a practical context.
Features:
* Loading Management: The hook handles loading state, allowing developers to provide feedback to users while waiting for geolocation data.
* Error Handling: In case of errors during geolocation retrieval, the hook sets an error state, enabling developers to communicate issues to users.
* Position Tracking: The hook maintains state for latitude and longitude, making it easy to access and display the user's current position.
* Usage Tracking: The component keeps track of the number of times the user requests their position, providing a count for reference.
Usage:
* 		Import the useGeolocation hook from the provided file.
* 		Invoke the hook within your component to access loading status, position data, and error messages.
* 		Implement the provided getPosition function to trigger geolocation retrieval.
* 		Integrate the hook with your UI to display loading indicators, error messages, and the user's position.
