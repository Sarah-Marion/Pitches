# Pitches# 60sec_Pitch

> A web application that allows the users to post pitches, comment and vote on pitches.

## Author

> By **Sarah Marion**

> -----------------------------------------------------------

## Description

> This is a web application that allows various users to submit a short pitch. Users can also be able to view other pitches from different categories (Pick-up Lines, Interview Pitches, Product Pitches, Promotion Pitches), comment and vote. For a user to do any of that, they need to have registered.

## User Stories

As a user I would like:

> * to view the different categories.
> * to see the pitches other people have posted.
> * to comment on the different pitches and leave feedback.
> * to submit a pitch in any category.
> * to vote on the pitch they liked and give it a downvote or upvote.

## How to use it

> * Internet connection
> * Click https://pitchthis.herokuapp.com/) <br/>
  or <br/>
> * Copy https://pitchthis.herokuapp.com/) and  Paste the link on your prefered browser

# How it works

* A user needs to sign up
* A user the needs to sign in to vote and post pitches

## Technologies Used

> * Python3.6
> * Flask framework
> * Bootstrap
> * PostgreSQL

## Setup/Installation Requirements

* git clone https://github.com/sarah-marion/Pitches.git
* cd Pitches
* python3.6 -m venv virtual (install virtual environment)
* source virtual/bin/activate
* python3.6 -m pip install -r requirements.txt (install all dependencies)
* Inside the manage.py module change the config_name parameter from 'production' to 'development' ie app = create_app('production') should be app = create_app('development')
* ./start.sh

## Dependancy Installments

> * pip install python3.6
> * pip install flask
> * pip install flask-bootstrap
> * pip install flask-script
> * pip install flask-wtf
> * pip install flask-migrate
> * pip install flask-login
> * pip install Flask-Mail
> * pip install flask-uploads

## Known Bugs

> It does not have bugs.But if any problems should occur, email me at devsarahmarion@gmail.com

## Support and Contact Details

> You can reach out to me at devsarahmarion@gmail.com
for Reviews, Advice, Collaborations and Comments

## Licence

> MIT License

> Copyright (c) 2018 **Dev Sarah Marion**

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

> --------------------------------------------------------