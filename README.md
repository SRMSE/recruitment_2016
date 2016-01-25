# SRMSE 2016 Recruitment Tasks

There are two tasks to be submitted:
-   Open Task
    -  In this task you can submit any app,website etc or basically any code written by you. There are no language constraints on it.
-   Domain Specific Task
    - In this task you have to submit solution to any one problem from below given domains. You can solve any domain any number of problems. There are no constraints on that issue.

##### Deadline : 2nd Feb 2016
##### Submission Method :
-   If you are familier with git
    -  Open an issue in this repo as `Task submission <YOUR REG NUMBER>`.And paste the link of your github repo with your task.
-   If you are not familier with git
    -   Just email your zip file with your registeration number in subject as `Recruitment task <YOUR REG NUMBER> ` at srmsesrmse@gmail.com


_Please submit your tasks before deadline. Even incomplete tasks are appreciated._

_Questions will be asked from your code._
## Domain Specific Questions
### Domain1: Web Scraping Tasks

#### Task 1: Design a scrapper for differencebetween.com
You have to write a script in any language (preferably Python) to scrape data from website http://www.differencebetween.com/.
##### Key Points
- The script should be able to scrape data from all the pages Ex http://www.differencebetween.com/page/2/
- The data should be stored into `MySQL`.
- Attributes required in the table
    - `id`
    - `item1`
    - `item2`
    - `body`

#### Example

Difference Between Challenge and Problem

| id | item1     | item 2  | body                                                                                                                                                                                                                                                                                                                        | page no |
|----|-----------|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| 1  | Challenge | Problem | Key Difference – Challenge vs Problem, In day to day life we often encounter challenges and problems on our way to success. These can often hinder our progress and make it difficult for us to achieve our goals. Most people consider challenges and problems to be synonymous as both create a barrier for the individual. | 1       |

_Preferred Language is Python!! But it is upto you how much you want to write the code!!_

#### Task 2: Design a scrapper for LinkedIn people directory


In this task below are the two LinkedIn directory links which you have to crawl:-
-   https://in.linkedin.com/directory/people-u/
-   https://in.linkedin.com/directory/people-s/

Here you have to write a scraper which will give us the Linkedin profiles present. They are actually the link of the root directory of names starting from U and S.Your scrapper should recursively walk through the directory and fetch profile links. 

##### Key Points
-   Your job is to get these links and store them in MySQL.
-   There should be a single scrapper where you have to just change the link and it should go as per hierarchy and get the links and store it in the MySQL format.

_Preferred Language is Python!! But it is upto you how much you want to write the code!!_

#### Example
| id | Letter | Link                                      | Person_name |
|----|--------|-------------------------------------------|-------------|
| 1  | U      | https://in.linkedin.com/pub/dir/Uday/Gour | Uday Gour   |

#### Task 3: Design a scrapper for wiki table


In this task below is the sample link for scraping.
-   https://en.wikipedia.org/wiki/Minister_of_Agriculture_(India)

Here you have to write a scraper for scraping data from the table given in the web page.


##### Key Points
-   Your job is to get these links and store them in `MySQL`.
-   Also, save the image link.
_Preferred Language is Python!! But it is upto you how much you want to write the code!!_

#### Example
| id | Name                 | Image                                                                                                                              | start_term | end_term | prime_minister   |
|----|----------------------|------------------------------------------------------------------------------------------------------------------------------------|------------|----------|------------------|
| 1  | Surjit Singh Barnala | https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/H_E_Shri_Surjit_Singh_Barnala.jpg/75px-H_E_Shri_Surjit_Singh_Barnala.jpg | 1948       | 1952     | Jawaharlal Nehru |

### Domain2: Web Development Tasks

_In this category you can submit any website or webapp or even the link of website you have made._

### Domain3: Natural Language Processing

#### Task 1: Write a stemmer for any Indian language


#### Task 2: Sentimental Analysis (Binary Classifier)
##### Key Points
- Only positive and negative analysis of sentence.
- Testing data and training data is given in this git repo.

### Domain4: Linux

##### Task 1

Make a `bash` script, which does the following tasks in this order

- Unzip the `.gz` file
- Delete all the `pycache files`.
- Remove the comments in all the files present. And by comments we mean `python` comments
- Replace the occurence of the word **Tasdik Rahman** in all the files with **Your name**

##### Task 2

You are given a log file inside inside the `logs` directory.

Write a script which parses the log file for the date `Jan 21` in a line and then in that line searches for the words

- `ERROR`
- `SUCCESS`
- `INFO`

and store(append) those lines into seperate files. i.e a line with `ERROR` should be stored in the file `error.txt` and so on. 

##### Task 3

Install Hadoop (Single Node)(run all nodes and a screenshot of `jps`) and apache spark(screen shot when installation completed)

##### Task 4

Host server on local PC and set up virtual hosts on same PC (screenshot of the config files whatever altered and a screenshot of virtual host with name `yourname.com` opened in browser)

Happy Hacking! :smile:


