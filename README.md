![image](https://user-images.githubusercontent.com/84760072/221398236-45ccef78-f75f-4ac5-93a9-0146bb4d63ed.png)
![image](https://user-images.githubusercontent.com/84760072/221398297-13f4d8e5-9061-4a63-bae6-32ace095d886.png)

<p align="center">
  A small tool for automating collecting data from ChatGPT
</p>

## Install as a Python Library
```
pip install sleepyask
```

## Sample code
Example usage:
```python
from sleepyask.chat import sleepy_ask

# Your ChatGPT login information
config = {
  "email": "Your ChatGPT email",
  "password": "Your ChatGPT password"
}

# List of questions you would like to ask ChatGPT
question_list = [
  'What is 1 + 1?',
  'What is 1 + 2?',
  'What is 1 + 3?'
]

# The filename in which you would like your responses to be stored.
output_file_path = 'draw.json'  

# Run sleepy_ask
sleepy_ask(config=config,
           questions=question_list,
           output_file_path=output_file_path)
```
## Get involved
- 🐛 **Found a bug or interested in adding a feature?** - Create an [issue][issue]  

[issue]: https://github.com/hwelsters/sleepyask/issues
