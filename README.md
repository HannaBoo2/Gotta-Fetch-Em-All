# Project Overview

## Project Name
NostalgiaDex

## Project Description
NostalgiaDex will allow users to search their favorite Pokemon from the original (Red, Blue, and Yellow) games and learn all about them. Just like a real PokeDex!

## API and Data Sample

Poke API https://pokeapi.co/docs/v2#info

```json
{
    "abilities": [
        {
            "ability": {
                "name": "overgrow",
                "url": "https://pokeapi.co/api/v2/ability/65/"
            },
            "is_hidden": false,
            "slot": 1
        },
        {
            "ability": {
                "name": "chlorophyll",
                "url": "https://pokeapi.co/api/v2/ability/34/"
            },
            "is_hidden": true,
            "slot": 3
        }
    ],
    "base_experience": 64,
    "forms": [
        {
            "name": "bulbasaur",
            "url": "https://pokeapi.co/api/v2/pokemon-form/1/"
        }
    ],
    "game_indices": [
        {
            "game_index": 153,
            "version": {
                "name": "red",
                "url": "https://pokeapi.co/api/v2/version/1/"
            }
        },
        {
            "game_index": 153,
            "version": {
                "name": "blue",
                "url": "https://pokeapi.co/api/v2/version/2/"
            }
        },
        {
            "game_index": 153,
            "version": {
                "name": "yellow",
                "url": "https://pokeapi.co/api/v2/version/3/"
            }
        },
```

## Wireframes

Link to my wireframe here: https://wireframe.cc/oKoj6c

### MVP/PostMVP

#### MVP 

- User can search Pokemon by name
- Correct Pokemon info and picture populates on page
- Previous search info clears when a new Pokemon is searched

#### PostMVP  

- Add CSS animation when loading a new Pokemon
- Style the 'submit' button to be an image with some animation

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Jan 25-26| Prompt / Wireframes / Priority Matrix / Timeframes | Complete
|Jan 26| Project Approval/ Core HTML & CSS Setup | Incomplete
|Jan 27| Core JS Functionality / Connect to API  | Incomplete
|Jan 28| Display Correct Data / Finish Basic Styling | Incomplete
|Jan 29| MVP | Incomplete
|Jan 30 & 31| Bonus Styling | Incomplete
|Feb 1| Presentations/Project Submission | Incomplete

## Priority Matrix

Priority Matrix https://res.cloudinary.com/drzmvvogq/image/upload/v1611673089/Screen_Shot_2021-01-26_at_8.57.46_AM_i08mw4.png

## Timeframes


| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Basic HTML Setup | H | 1hr| - | - |
| Basic CSS Setup & Styling | H | 2hr| - | - |
| Connect API| H | 1hr| - | - |
| Make First Get Request| H | 1hr| - | - |
| Target Correct Info from API | H | 2hrs| - | - |
| Target Correct Picture from API | H | 2hr| - | - |
| Creating Dynamic HTML Search Using EventListeners  | H | 3hr| - | - |
| Grab User Input from Search | H | 3hr| - | - |
| Display Correct Name and Info on Page| H | 3hr| - | - |
| Display Correct Picture on Page| H | 2hr| - | - |
| Clear Results After Making a New Search | H | 3hr| - | - |
| CSS Styling of Each Pokemon's 'Page' | L | 3hr| - | - |
| Flexbox Styling | L | 3hr| - | - |
| MediaQuery/(ies) | L | 1hr| - | - |
| Total | H | 30hrs| - | - |

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of and a brief description.  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  
