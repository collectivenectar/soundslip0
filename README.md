# soundslip - 0(v0)
An audio NFT platform for artists and fans

# Current State:

This is in research and planning phase, with a focus on getting to stage 1 of 5 stages
as an MVP (Minimum viable product). 

*Current Task* as of 06/04/24

Tech Stack Research



Being heavily dependent on the chia blockchain, which
would normally require a private node, I'm starting out by building on mintgardens API,
to familiarize myself with the requirements and get up to speed quickly.

If you have any suggestions feel free to reach out!


# MVP stages:

## Version 1: Basic Audio Discovery and Management

Objective: Launch a foundational browser-based platform for users to discover and manage NFT-based audio files.

### Features:

    NFT Search: Implement basic functionality to search for audio NFTs using filters and keywords.
    Sound Library Tools: Enable users to create and manage playlists, group tracks into albums, and sort content by date, popularity, title, and artist.
    Audio Streaming: Facilitate simple streaming of audio files directly from the platform.
    Basic Caching: Develop rudimentary caching of audio files to enhance playback performance.

### Development Focus:

    Establish the core architecture of the platform.
    Integrate with the MintGarden blockchain API to fetch NFT data.
    Implement service workers for effective streaming and caching of audio files from IPFS or other endpoints.
    Design a straightforward yet functional user interface for navigating and organizing audio files.

## MVP Version 2: Enhanced User Experience and Social Features

Objective: Improve user engagement with advanced playback features and initial social functionalities.

### Features:

    Advanced Audio Player: Integrate advanced features like shuffle, repeat, queue management, album covers, and trig-based visualizations.
    User Profiles: Enable users to create and customize their profiles, linking them with decentralized identifiers (DIDs) and aggregating NFT data.
    Social Interactions: Incorporate commenting capabilities and integrated social sharing (e.g., to platforms like Twitter, TikTok).
    Chat: Implement DID-based chat functionality using libp2p for secure communication.

### Development Focus:

    Enhance security by integrating DID authentication and libp2p encryption.
    Make iterative improvements to the audio player to support new functionalities.

## MVP Version 3: Artist Tools, Custom Smart Coins

Objective: Introduce specialized tools for audio producers and artists, focusing on commerce capabilities through smart coins.

### Features:

    Artist Dashboard: Provide artists with insights into listener activities such as playlists, listens, and comments.
    Artist Singleton Coins: Develop 'buy now' or 'subscribe' functionalities linked to Chia offers, using singleton smart coins for access verification.
    Periodical Singleton: Allow artists to establish subscription-based access to their content.
    Notifications and Alerts: Set up system notifications for new releases, subscriptions, and other interactions.

### Development Focus:

    Extend backend functionality for NFT management.
    Develop and audit custom smart coins tailored for commerce transactions.
    Establish a robust system for managing and reacting to event streams from the Chia blockchain.

## MVP Version 4: Advanced Caching and Offline Access

Objective: Boost the platform’s performance and accessibility by enhancing caching mechanisms and enabling offline playback.

### Features:

    Advanced Caching Mechanisms: Deploy sophisticated caching strategies to reduce load times and improve user experience.
    Offline Playback: Allow content to be saved for offline access, leveraging Progressive Web App (PWA) technology.
    Quality of Service Enhancements: Adapt streaming quality based on user connection speeds.

### Development Focus:

    Implement advanced caching solutions, including service workers.
    Develop capabilities for storing and playing back content offline.
    Optimize adaptive streaming technologies to accommodate varying network conditions.

## MVP Version 5: Community Features and Expansion

Objective: Expand the platform with additional community engagement features and explore new market integrations.

### Features:

    Live Events: Incorporate live streaming functionalities, potentially using technologies like Jacktrip.
    AR/VR Integration: Explore AR/VR capabilities to enhance user experience, possibly through API exposure or widget development.
    Brand Strategy and Community Building: Develop analytics dashboards, establish artist brand funds, and set up incubator programs.
    P2P Discoverability: Enhance content discoverability through recommendations based on the user's node network, emphasizing a non-ad-based model.

### Development Focus:

    Establish live streaming capabilities with real-time user interaction.
    Create spaces for community engagement and support.
    Design and document public APIs to facilitate external integrations and collaborations.