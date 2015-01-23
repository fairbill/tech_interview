# tech_interview

# Rate my professor
  Overview:
  This is an interview Rails project intented to mimic some of the behaviors of http://www.ratemyprofessors.com/

# Some of the functionalities you're going to implement in this mini Rails project:
  1. Use one of these free bootstrap templates: http://bootswatch.com/
  2. A frontpage. The frontpage will have the following items:
    * A title, a description, a logo (you can use a random pic) to indicate what this site does (Rate my professor).
    * A search Box that uses autocomplete to find an existing professor, just like the real http://ratemyprofessors.com does at the top of their page (Hint: I would use: https://select2.github.io/examples.html) Once the user chooses a professor from the dropdown, it should take to a professor's profile page.
    * A frontpage should also have a list/table of professors sorted by their ratings (highest on top). Each professor row in the list/table should have the following columns: first_name, last_name, university_name, rating, and a link to their profile page. The list/table should be paginated (Hint: https://github.com/amatsuda/kaminari).
  3. A professor profile page. The profile page will have the following items:
    * Pofessor's name and rating
    * Professor's university's address display in a small google map.
    * A brieft description for the professor (bio, background, etc.)
    * A photo of the professor (could be random)
  4. A professor can sign-up/sign-in using Devise (https://github.com/plataformatec/devise) to create/edit information on his profile page (name, address, description, photo)


# Technical requirements:
  1. Use either MySQL, PostgreSQL, SQLite to store data. Implement the correct data models and their relationships. Please keep Object Oriented Design in mind.
  2. Use RSpec to write some tests to demontstrate your code is correct.
  
# Note:
  1. Complete as much as you can. I'm looking for code quality and good implementations of Object-Oriented design.
  2. It's okay if you haven't used Rails. I'd highly suggest going through some tutorials such as Rails for Zombies.
  

    
