# Design Engineer Technical Assessment

Design and deliver a solution that meets the following user stories, incorporating the supplied data.  Please submit your code via a link to a Git repository.

intelliHR uses a combination of Postgres, Laravel, NodeJS, GraphQL, React and Typescript.  However, you may use any technology that you are comfortable with to meet the requirements.

---

### Gotta Catch 'Em All!

With the proliferation of mobile devices in all worlds, the age of the dedicated pokedex is passing!  Modern trainers expect a web interface that they can access on their mobile devices.  We've been tasked by Professor Oak to build a prototype web pokedex.

![images/53yxmw.jpg](images/53yxmw.jpg)

### Users

Trainer - Any anonymous user

Professor Oak - Pokedex application manager

### User stories
| ID | Story Description                                                                                                    | Priority    | Details                                                                                                                                            |
|----|----------------------------------------------------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | As a Trainer, I can see a table of pokemon                                                                           | Must have   |                                                                                                                                                    |
| 2  | As a Trainer, I can search the table of pokemon by name or description                                               | Must have   |                                                                                                                                                    |
| 3  | As a Trainer, I can filter the table of pokemon                                                                      | Must have   | Filterable by:      Type                                                                                                                           |
| 4  | As a Trainer, I can sort the table of pokemon                                                                        | Must have   |                                                                                                                                                    |
| 5  | As a Trainer, when I select a pokemon, I can see an image and description                                            | Must have   |                                                                                                                                                    |
| 6  | As a Trainer, when I select a pokemon, I can see its type strengths and   weaknesses                                 | Should have |                                                                                                                                                    |
| 7  | As a Trainer, I can use the interface using a mobile device                                                          | Should have |                                                                                                                                                    |
| 8  | As a Trainer, when I select a pokemon, I can see its evolution path                                                  | Could have  |                                                                                                                                                    |
| 9  | As a Trainer, when I access the device from a mobile device, I see   customised browser background and theme colours | Could have  |                                                                                                                                                    |
| 10 | As a Trainer, I can mark pokemon as 'captured'                                                                       | Could have  | Should include:      Ability to filter/view by 'captured'      Captured state should persist if Trainer navigates away and returns to   interface. |
| 11 | As Professor Oak, I can run unit tests against the new pokedex system                                                | Could have  |                                                                                                                                                    |

You should restrict your submission to around 3 hours of work.  If you do not complete all stories in this time, please also submit an estimation of the time required to complete the remainders (and any related notes/approach you think would be helpful).

### Demo Data

Included in the /data directory is a set of static JSON data sources that you may use for this interface.  You may alter, delete, or add to this data in any way you see fit. It is only included here as a convenience to get started, and should not be taken as a structure or requirement at all.  We recommend using the JSON files to mock an API response.

Alternatively, there are public API resources that you may wish to use instead (eg. [https://pokeapi.co/](https://pokeapi.co/))