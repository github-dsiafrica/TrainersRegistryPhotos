# Trainers Registry Photos

This repository's main function is to hold photos that are linked to on the [DS-I Africa Trainers Registry](https://dsi-africa.org/trainer-registry).

This repo also holds a script that processes the response from the REDCap API. It does the following:

- Creates a new field for the profile picture URL on GitHub that uses the record ID of the trainer.
- Trims the job title to not be longer than 100 characters.
- Sorts trainers alphabetically by first name.

## How to Run

To run the script, you need to have Node.js installed. Thereafter you can run `node script.js`. This will generate a JSON file that can then be used for rendering content on the front-end.
