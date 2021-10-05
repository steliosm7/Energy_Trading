## **Stylianos Miliarakis** - Energy Analyst

### Markdown

Simple program to call and edit a file from IPTO 

```markdown
import urllib, json
import requests
import xlrd

from urllib import request
# Define the remote file to retrieve
remote_url = 'https://www.admie.gr/getOperationMarketFilewRange?dateStart=2021-8-01&dateEnd=2021-8-02&FileCategory=ISPWeekAheadLoadForecast'
# Define the local filename to save data
local_file = 'testfile.json'
# Download remote and save locally
request.urlretrieve(remote_url, local_file)

with open('testfile.json') as json_file:
    testfile = json.load(json_file)
testfile
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/steliosm7/Energy_Trading/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
