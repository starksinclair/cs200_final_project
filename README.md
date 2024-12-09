# Digital Privacy Explorer

## Overview
Digital Privacy Explorer is an interactive web-based project designed to educate users about the concept of digital fingerprints. The project introduces users to the concept of a "digital fingerprint," how it is created, how it is used for tracking, privacy laws and which data is being collected during account creation.

This project was built using Twine with the Snowman story format, integrating JavaScript, FingerprintJS for generating digital fingerprints, and custom CSS for styling.

---

## Features

### Interactive Simulations
- **Account Creation Simulation**
  - Hands-on experience with privacy choices during account setup
  - Learn about data sharing implications
  - Understand optional vs. necessary information sharing

- **Digital Fingerprint Simulation**
  - Generate and analyze your unique digital fingerprint
  - Visualize how browsers and devices create identifying patterns
  - Interactive demonstration of tracking mechanisms

- **Privacy Laws Simulation**
  - Explore real-world privacy regulations (GDPR, CCPA)
  - Learn about user rights and company obligations
  - Practice scenarios involving data breach responses

### User Experience
- **Intuitive Interface**
  - Clean, modern design
  - Easy navigation between modules
  - Mobile-responsive layout

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
- Javascript History API [https://developer.mozilla.org/en-US/docs/Web/API/History_API](https://developer.mozilla.org/en-US/docs/Web/API/History_API)
- Assistance with Twine navigation logic and CSS: AI-based guidance.
- Twine Cookbook [https://twinery.org/cookbook/](https://twinery.org/cookbook/)
- Imgbb for free image hosting [https://imgbb.com/](https://imgbb.com/)
- Wikimedia for free licensed images [https://upload.wikimedia.org/wikipedia/commons/9/98/Labyrinth-W%C3%BCrfel_in_Blender-Cycles.png](https://upload.wikimedia.org/wikipedia/commons/9/98/Labyrinth-W%C3%BCrfel_in_Blender-Cycles.png)
- Dr Andrew Harris CS200 class

---

## Challenges
1. **Story Format Transition:**
   - Originally created in the Harlowe format but transitioned to Snowman for greater JavaScript flexibility.
   - Required implementing custom navigation.

2. **Dynamic Back Navigation:**
   - Snowman lacks built-in navigation controls, so had to default to javascript `history.back()` founction which is the browser default navigation for going back or forward.

3. **Fingerprint Generation:**
   - Integrating FingerprintJS and managing  API calls within Twine's environment.

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
1. Click on the link [https://starksinclair.github.io/cs200_final_project/](https://starksinclair.github.io/cs200_final_project/) to see the project
   
---

## Attributions
- **FingerprintJS**: For providing the digital fingerprint generation logic.
- **AI Assistance**: Leveraged for guidance on Twine navigation and css designs.
- **FontAwesome**: For icons enhancing the user interface.
- **CSS Design Inspiration**: Utilized guides and tutorials for styling the project.
- **Imgbb**: For free image hosting

---

## Future Improvements
- Add more scenarios for users to explore various aspects of digital privacy.
- Implement user progress tracking within the simulation.
- Expand educational content with quizzes or interactive Q&A.

---

