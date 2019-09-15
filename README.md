# VkScrapper
 Program for monitor your own online activity on vk.com

## Libraries Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install libraries.

```python
pip install requests
pip install bs4
pip install BeautifulSoup
```

## Usage

### Before you start
Found id of your VK page.

### How to run
For run use python:
```bash
py get_online.py
```
After that, enter id of your page on vk.com:
```bash
Enter user id (Введите id  пользователя): 10000451
```
If monitoring start successful you'll see message like that:
```bash
START: 05-01-1984 00:00 | Guy Montag | URL: https://vk.com/id10000451
05-01-2019 00:00 | заходил 41 минуту назад
05-01-2019 00:01 | заходил 42 минуты назад
05-01-2019 00:02 | Online
```
Don't close the terminal until you didn't finished monitoring.

### After
After you collect some statistic, you can found 2 type of files `05-01-1984_full_log.txt` and `05-01-1984_log.txt`.
`05-01-1984_full_log` - it's log with every minute statistic

`05-01-1984_log` - it's only about online time

## Converting to HTML
For convert your logs to HTML table use [log2html](https://github.com/V1A0/log2html)
```bash
git clone https://github.com/V1A0/log2html.git
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)