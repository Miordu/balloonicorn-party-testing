# Balloonicorn's Party Testing

This Flask application is for Balloonicorn's party with added tests. The app allows users to RSVP for a party, view party details, and see treats being brought to the party.

## Features
- Homepage with RSVP form
- Party details view (after RSVP)
- List of treats being brought to the party
- Special handling that prevents Mel from attending

## Tests Added
- Doctests for the `is_mel` function to verify user identification
- Doctests for the `most_and_least_common_type` function to verify treat analysis

## Setup Instructions
1. Create a virtual environment: `virtualenv env`
2. Activate: `source env/bin/activate`
3. Install requirements: `pip3 install -r requirements.txt`
4. Run the server: `python3 party.py`
5. Visit http://127.0.0.1:6060/ in your browser
