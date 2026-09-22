# CSE 4/535 Project 2: Starter Kit

This codebase is a starter kit for Project 2. Usage of this toolkit is **RECOMMENDED**.


## Requirements

Use the package manager [pip3](https://pip.pypa.io/en/stable/) to install the requirements. 
s
```bash
sudo apt-get update
sudo apt install python3-pip -y
pip3 install tqdm Flask nltk
```

## Files and Tasks

1. `run_project.py` is the driver file, which will create the Flask app. Implement the logic for getting the postings list, executing DAAT AND query, merging linked list. etc. in this file.
2. `indexer.py` contains code to create and manipulate the index. Implement the necessary functions in indexer.
3. `preprocessor.py` contains code to pre-process documents & queries. Implement the necessary functions in preprocessor.
3. `linkedlist.py` defines the basic data structures for the postings list and the nodes of the postings list. It also contains code to manipulate the postings list. . Implement the necessary functions in linkedlist.
4. Execute `run_project.py` to create your index and start your API endpoint. Your endpoint will be available at `http://<public ipv4:9999>/execute_query`

## Strategies for completing the project efficiently

- Make sure the instance is running during grading.
- Run `run_project.py` using the command `python3 run_project.py --corpus ./data/input_corpus.txt --output_location ./data/output.json --username your_UB_username` 
- Don't forget to open the port 9999 on your instance for TCP connections.


## Contributing

#### Acknowledgement: Credit goes to (former UB student and instructor) Sougata Saha for his code contribution.

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)