# Exploring-the-history-of-lego
The Rebrickable database includes data on every LEGO set that has ever been sold; the names of the sets, what bricks they contain, what color the bricks are, etc. It might be small bricks, but this is big data! In this project, you will get to explore the Rebrickable database and answer a series of questions related to the history of Lego!

# Introduction



Let's look at Lego sets!
Lego is a household name across the world, supported by a diverse toy line, hit movies, and a series of successful video games. In this project, we are going to explore a key development in the history of Lego: the introduction of licensed sets such as Star Wars, Super Heroes, and Harry Potter.

It may not be widely known, but Lego has had its share of ups and downs since its inception in the early 20th century. This includes a particularly rough period in the late 90s. As described in this article, Lego was only able to survive due to a successful internal brand (Bionicle) and the introduction of its first licensed series: Star Wars. In the instructions panel are the two questions you will need to answer to complete this project.

Before diving into our analysis though, let's become familiar with the two datasets that will help you with this project:


# datasets/lego_sets.csv    
  set_num: A code that is unique to each set in the dataset. This column is critical, and a missing value indicates the set is a duplicate or invalid!  
  set_name: A name for every set in the dataset (note that this can be the same for different sets).  
  year: The date the set was released.  
  num_parts: The number of parts contained in the set. This column is not central to our analyses, so missing values are acceptable.  
  theme_name: The name of the sub-theme of the set.  
  parent_theme: The name of the parent theme the set belongs to. Matches the `name` column of the `parent_themes` csv file.  
  
# datasets/parent_themes.csv
  id: A code that is unique to every theme.  
  name: The name of the parent theme.  
  is_licensed: A Boolean column specifying whether the theme is a licensed theme.  
