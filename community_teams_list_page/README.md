# CC Community Teams Members List

This script pulls tasks from the `Community Teams Tracking` Asana project in CC's Asana organization, 
does some basic cleaning and filtering, then adds the tasks to a template and writes the 
content to [creativecommons/creativecommons.github.io-source](https://github.com/creativecommons/creativecommons.github.io-source).

## Running the Script

1. Install [Pipenv](https://pipenv.readthedocs.io/en/latest/)
2. Navigate to the `communityteams_list_page` folder and run `pipenv install`.
3. Set the ADMIN_GITHUB_TOKEN environment variable with your GitHub token. You will need a GitHub token with read and write permissions to the `creativecommons` GitHub organization.
4. Set the ADMIN_ASANA_TOKEN environment variable with your Asana token.
5. Run the script: `python3 communityteams_list_page.py`.

## Repository README

See repository README for licensing information, etc:
- [`../README.md`](../README.md)
