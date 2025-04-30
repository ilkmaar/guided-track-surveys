# GuidedTrack Surveys for Game Design

This repository contains GuidedTrack code for interactive surveys designed to collect feedback from children about a game design project. The surveys are structured as a "choose your own adventure" experience to engage participants while gathering their preferences on various game elements.

## Project Overview

These surveys were created to collect user feedback about a game design concept called "Ilkmaar" - a multiplayer game set in a world of magical islands inhabited by different creature factions. The surveys progress through chapters that introduce different aspects of the game world:

1. **Chapter 1: Intro to Ilkmaar** - Initial introduction to game concepts, art style, and character design
2. **Chapter 2: The Indigo Isles** - Exploration of islands, creatures, and game mechanics
3. **Chapter 3: Joining Your Guild** - Deeper exploration of player roles, avatar customization, and faction affiliations

## Repository Structure

- **Chapter folders** - Each chapter has its own folder containing:
  - Main GuidedTrack script file (the survey content)
  - `AirtableFormula` utility program
  - `Encode characters for URLs` utility program
- **CSV files** - Each chapter has a corresponding CSV file storing data related to the survey

## Survey Features

### Shared Components

- **Airtable Integration** - All surveys store responses in Airtable
- **Personalization** - Surveys greet participants by name when possible
- **Response Validation** - Error handling for data submission problems
- **Choice-based Navigation** - Participants can make choices that influence survey flow
- **Image Visualization** - Extensive use of images to showcase game concepts
- **Data Collection** - Structured collection of both multiple-choice and open-ended responses

### Chapter-Specific Content

1. **Chapter 1: Intro to Ilkmaar**
   - Game concept choices (Ilkmaar Island vs. Camp Ilkmaar)
   - Art style and mood board preferences
   - Character design preferences
   - Creature design preferences

2. **Chapter 2: The Indigo Isles**
   - Narrative elements about the islands
   - Setting exploration (Main Town, Indigo Island)
   - Creature interactions (Lifeweavers, Rock Golems)
   - Shop and marketplace mechanics

3. **Chapter 3: Joining Your Guild**
   - Avatar customization
   - Island factions (Growth, Light, Stability, Shadow)
   - Creature faction affiliations
   - Player roles and social dynamics

## Technical Implementation

The surveys use GuidedTrack's programming features:
- **Variables** - Store user choices and survey state
- **Dictionaries** - Map options to descriptions and image URLs
- **Conditional Logic** - Control survey flow based on responses
- **External Services** - Airtable integration for data storage
- **Utility Programs** - Handle URL encoding and Airtable formula generation

## Usage

These surveys were designed to be shared with participants via unique links containing respondent IDs (`r_id`). The survey then:
1. Retrieves any existing data for the participant
2. Guides them through the interactive experience
3. Stores their responses in Airtable for analysis

## Data Collection

The surveys collect:
- **Demographic Information** - Basic information about participants
- **Preferences** - Game style, character design, and feature preferences
- **Open-ended Feedback** - Qualitative responses about various game elements
- **Rankings** - Priority ordering of different game activities
- **Creative Input** - Participant ideas for game development

This data was intended to inform the development of the "Ilkmaar" game, ensuring it aligned with the preferences and interests of its target audience.