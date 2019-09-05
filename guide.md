# User Guide

This guide describes how to manage and review submissions for an 
OpenJournal. We make use of `OJ` as a placeholder for the name of the 
journal.

## For Authors

### Create Submission

To create a new submission:

 1. Go to the GitHub project page of the OJ you want to submit to.

 2. Click on the `articles.md` file and add a new entry to the table. 
    A new entry has the following format:

    ```
    <Title> | <Authors> | <URL> |
    ```

    Where `Title` is the title of your article, `Author` is a list of 
    comma-separated names and `URL` is a link to the article. Note 
    that the `|` symbols separate each field and its important to 
    include them.

 3. After accomplishing the above, you will see a new page containing 
    a form for creating a pull request (PR) like the following:


    Click on the `Create Pull Request` button to create a new 
    submission.

#### Attaching Files to Your Submission

TBD

#### Adding the manuscript as part of your submission

TBD

### Respond to Comments from Reviewers

Once you create a submission, the editors of the journal will receive 
a notification and will assign reviewers to your submission. Once 
reviewers read your article, they will leave comments on the Pull 
Request associated to your submission. To respond to their comments, 
you can use the text form found in this page (see [here for 
more][gh-pr])

[gh-pr]: https://help.github.com/en/articles/about-pull-request-reviews

## For Reviewers

### Add Review (On GitHub)

TBD

### Add Review (On [`hypothes.is`](https://hypothes.is))

TBD


## For Editors

### Journal Setup

To create a new journal:

 1. Click "Use this template" on the main page of the repository
 2. From the template cloned in you repository, edit the "Readme.md" file to create the main page of your journal. 
 3. You are done! Your journal will be hosted at (<youraccount>.github.io/<your_journal_name>)

### Assign Reviewers

As submission is handled via a pull request, the editor assign reviewers using github assignments as described [here](https://help.github.com/en/articles/assigning-issues-and-pull-requests-to-other-github-users).


### Approve Submission

Once the paper is approved, the editor merges the pull request to add the paper to the journal record as described [here](https://help.github.com/en/articles/merging-a-pull-request) using the "squash and merge" option. 
