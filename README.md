# Digital Privacy Explorer

## Overview
Digital Privacy Explorer is an interactive web-based project designed to educate users about the concept of digital fingerprints. The project introduces users to the concept of a "digital fingerprint," how it is created, how it is used for tracking, and steps they can take to protect their privacy online.

This project was built using Twine with the Snowman story format, integrating JavaScript, FingerprintJS for generating digital fingerprints, and custom CSS for styling.

---

## Features
- **Interactive Fingerprint Simulation:** Users can generate a simulated digital fingerprint and learn how such identifiers are used.
- **Educational Content:** A dedicated section explaining what a digital fingerprint is, its usage, and factors influencing it.
- **Dynamic Navigation:** Includes back buttons and dynamic navigation support, overcoming challenges from changing the story format.

---

## Technologies & Resources

### Technologies Used
- **Twine:** Snowman story format for building interactive storytelling.
- **JavaScript:** For handling logic and fingerprint generation.
- **CSS:** Custom styles for an engaging UI/UX.
- **FingerprintJS:** Library for generating digital fingerprints.

### Resources
- [FingerprintJS Documentation](https://fingerprint.com)
- FontAwesome for icons: [https://fontawesome.com](https://fontawesome.com)
- CSS design inspiration: Tutorials and guides on modern web design principles.
- Assistance with Twine navigation logic and transitions: AI-based guidance.

---

## Challenges
1. **Story Format Transition:**
   - Originally created in the Harlowe format but transitioned to Snowman for greater JavaScript flexibility.
   - Required implementing custom navigation and managing state between passages.

2. **Dynamic Back Navigation:**
   - Snowman lacks built-in navigation controls, necessitating manual implementation of a history stack for back button functionality.

3. **Fingerprint Generation:**
   - Integrating FingerprintJS and managing asynchronous API calls within Twine's environment.

---

## Pseudocode

### Generate Digital Fingerprint
```plaintext
Define a function `generateFingerprint`
    Get the display element for the fingerprint (`fingerprintDisplay`)
    Clear the previous fingerprint result

    Import FingerprintJS library
    Load the FingerprintJS object

    Generate the fingerprint
        Extract the `visitorId` and confidence score from the result
        Display the fingerprint and confidence score in the `fingerprintDisplay`

    Handle errors
        Display an error message if fingerprint generation fails
End function
```
---

## How to Run
1. Open the Twine project in your preferred browser.
2. Click on the "Start" button to navigate to the Digital Fingerprint Simulation.
3. Generate your digital fingerprint and explore the related educational content.

---

## Attributions
- **FingerprintJS**: For providing the digital fingerprint generation logic.
- **AI Assistance**: Leveraged for pseudocode drafting and guidance on Twine navigation.
- **FontAwesome**: For icons enhancing the user interface.
- **CSS Design Inspiration**: Utilized guides and tutorials for styling the project.

---

## Future Improvements
- Add more scenarios for users to explore various aspects of digital privacy.
- Implement user progress tracking within the simulation.
- Expand educational content with quizzes or interactive Q&A.

---

Enjoy exploring the world of digital privacy!
 change this to markdown code

