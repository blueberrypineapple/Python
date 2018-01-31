# Frequencies of words in novels: a Data Science pipeline
You've been hired onto a team working on a newspaper site. The user-facing newspaper site frontend itself, and the database behind it, are already built and running. You've been asked to build an internal reporting tool that will use information from the database to discover what kind of articles the site's readers like. 

## Prerequisites
- Python3 (v. 3.6.4) 
- more?



## Setup
1. Install Vagrant And VirtualBox
2. Clone this repository

## Installing

Launch Vagrant VM by running `vagrant up`, you can the log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Authors
- Articles
- Log

To execute: type `python3 main.py` from the command line.



## Author

* **Constance Howes** - 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
