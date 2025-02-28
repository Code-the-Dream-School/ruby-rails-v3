### Project rubric
The project you build throughout the course should demonstrate the course objectives (as they apply). Here they are as applied to your project.

- Design and implement a data model using appropriate associations, data types and constraints
  - Demonstrate `belongs_to`, `has_many` and `has_many :through` relationships where it makes sense.
  - Include data constraints at the database level and at the model level where it makes sense. For example, consider what attributes should never be null.
  - Include other validations in models where it makes sense. (`presence`, `inclusion`, etc)
- Add behavior to models where appropriate
  - In addition to validations, consider what behavior your models should be responsible for and add any behaviors that make sense.
- Design and implement CRUD-based behaviors for resources where appropriate
  - Create an intentional design that only includes the CRUD functionality that makes sense for each resource.
  - Choose non-resourceful routes when appropriate. Your application should have at least one route (and possibly view) that displays data from multiple models, or that updates multiple models for post and patch/put routes.
- Write rspec tests that cover the most critical functionality
  - Include model specs that test any special behaviors you added. If you've added any custom validations, you can test that as well.
  - Include request specs especially for non-resourceful routes, or any routes with special requirements for parameters, access, etc.

### Project ideas
CTD projects in classes and practicums have traditionally allowed students to come up with their own ideas for their projects, so long as the project can fulfill the rubric. For some students, this is exciting and makes the project more fun, but some students may have trouble coming up with an idea that fits the rubric nicely. If you're one of those students, feel free to use any of these ideas directly, or as inspiration.

- A simplified Bookreads clone
  - A logged-in user may create, update and delete book entries.
  - A logged-in user may create, update and delete book reviews.
  - Each book review must be associated with a book in the database.
  - A user can view the list of the books they've created.
  - A user can view the list of the reviews they've created.
  - A user can view the list of reviews for a book (by any user).
- A personal online journal
  - The journal admin can create, update and delete journal entries.
  - Journal entries may be made public or private.
  - For public entries, non-logged-in users may leave comments on the entry.
  - The journal writer can create, update and delete journal categories.
  - Each entry must belong to a category.
  - The journal writer can create, update and delete "tags" or labels.
  - Each entry may have one, many or no tags/labels.
- Music or other media collection manager
  - Users can create, update, delete album/mp3/movie/book entries.
  - Users can view a list of other users who own an album/mp3/movie/book.
  - Users can view a list of their own albums/mp3s/movies/books.
  - Users can comment on an album/mp3/movie/book.
  - Users can view the list of comments for an album/mp3/movie/book.
