# Lions Next Game

A Bash script that prints when the Detroit Lions play next, right in your terminal.

## Project Goal

I'm a Detroit Lions fan, and I plan my schedule around their games so I'm free to watch them. Every time I want to know when the next game is, I have to open ESPN and dig through the site. I want a simple, fast way to see the Lions' schedule without leaving my terminal.

## MVP Scope

- Get the Lions schedule from ESPN's API with `curl`
- Find the next upcoming game and extract the opponent, date, and kickoff time
- Convert the kickoff to local time and print it, with a clear message if there's no upcoming game

## Future Plans

- [ ] Show the result of the most recent game
- [ ] Countdown to kickoff
- [ ] Run automatically every morning with cron

## Tech Stack

- **Language:** Bash
- **Tools:** curl, jq, date
- **Data source:** ESPN's unofficial NFL API
