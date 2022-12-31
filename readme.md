## CaseStyles

### Install
```
pip install casestyles
```

### Import
```python
from casestyles import Name
```

### Create name
```python
name = Name.from_snake_case("snake_case_name")
```

```python
name = Name.from_camel_case("camelCaseName")
```

```python
name = Name.from_pascal_case("PascalCaseName")
```

### Transform name
snake_case_name = name.snake_case
camel_case_name = name.camel_case
pascal_case_name = name.pascal_case
```