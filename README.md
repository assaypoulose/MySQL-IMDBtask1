MySQL task - IMDB database

This schema follows normalization principles and captures the relationships between movies, media, genres, reviews, users, artists, skills, and roles.

Movies table stores information about movies.
Media table stores media files associated with movies.
Genres table stores different genres.
MovieGenres table captures the many-to-many relationship between movies and genres.
Reviews table stores reviews written by users for movies.
Users table stores user information.
Artists table stores information about artists.
Skills table stores different skills that artists can have.
ArtistSkills table captures the many-to-many relationship between artists and skills.
Roles table stores different roles that artists can perform.
MovieArtists table captures the many-to-many relationship between movies, artists, and roles.
This design allows for flexibility and scalability, accommodating IMDb-like functionalities such as associating multiple media types with movies, assigning multiple genres to movies, capturing multiple reviews per movie from users, managing artists with multiple skills performing multiple roles in movies, and more.
