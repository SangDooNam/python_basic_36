[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/hKm-d3Ce)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12002011&assignment_repo_type=AssignmentRepo)
# Task - Convert keys between cases

Different programming languages use different kind of schemes to name things. For example Python uses `snake_case`, JavaScript uses `camelCase`. You might also come across `kebap-case` - sometimes also called `dash-case`. You can read more about naming conventions in programming the [matching Wikipedia article](https://en.wikipedia.org/wiki/Naming_convention_(programming)).

When an API you are using is implemented using a different language it might not match Python's convention of naming things. Hence your task is to implement a method that converts a dictionary with natural cased keys like `A random key` to `a_random_key`.

## Input A:

```python
natural_case = {
  'Company name': 'Digital Career Institute',
  'Street': 'Vulkanstraße',
  'House Number': 1,
  'City': 'Berlin'
}
```

## Output A:

```python
snake_case = {
  'company_name': 'Digital Career Institute',
  'street': 'Vulkanstraße',
  'house_number': 1,
  'city': 'Berlin'
}
```

## Input B:

```python
natural_case = {
  'Movie name': 'James Bond 007: Skyfall',
  'Director': 'Sam Mendes',
  'Production Year': 2012,
  'Duration in minutes': 143,
  'Production countries': ['US', 'UK']
}
```

## Output B:

```python
snake_case = {
  'movie_name': 'James Bond 007: Skyfall',
  'director': 'Sam Mendes',
  'production_year': 2012,
  'duration_in_minutes': 143,
  'production_countries': ['US', 'UK']
}
```
