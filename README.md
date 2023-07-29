# Movie Recommendation System

This repository contains a simple movie recommendation system that uses collaborative filtering to suggest movies to users based on their historical movie ratings.

## How it works

The movie recommendation system is built using Python and leverages the `numpy` library for numerical operations. It takes into account a movie rating dataset (`train`) where each row corresponds to a user's movie ratings. The recommendation system uses a pre-trained predictive model (`model`) to estimate the ratings for unrated movies and then suggests the top N movies with the highest predicted ratings.

## Requirements

- Python 3.x
- numpy (install using `pip install numpy`)

## Usage

1. Clone the repository:

```bash
[git clone https://github.com/your-username/movie-recommendation.git](https://github.com/Sanmuga/Simple-movie-recommendation-system.git)
```

2. Ensure you have the required dataset (e.g., `train`) and the pre-trained predictive model (`model`) available.

3. Modify the code to include the list of movie names (`movie_names`) according to your dataset.

4. Run the movie recommendation script by replacing `<user_id>` with the ID of the user you want to get recommendations for:

```bash
python recommend_movies.py <user_id>
```

The script will print the top recommended movies for the given user.

## Example

```bash
python recommend_movies.py 25
```

Output:
```
Recommended movies:
- Movie A
- Movie B
- Movie C
```

## Note

Please make sure to update the necessary variables, such as `movie_names`, `train`, and `model`, according to your dataset and pre-trained model.

Feel free to experiment with different recommendation strategies or models to improve the movie recommendations further.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

This simple movie recommendation system demonstrates collaborative filtering for suggesting movies to users based on their past movie ratings. You can customize the dataset, model, and recommendation strategy to suit your specific needs and data. Have fun recommending movies! 🎬🍿
