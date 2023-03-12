{% set author = load_data(path="data/author.toml") %}
[{{ text }}](mailto:{{ author.email }})
