# User Guide

This guide describes how to manage and review submissions for an 
Open Journal. We make use of `OJ` as a placeholder for the name of the 
journal.

## For Authors

### Create Submission

To create a new submission:

 1. Go to the GitHub project page of the OJ you want to submit to. The 
    URL will look something like:

    ```
    https://github.com/<ORG>/<OJ>
    ```

    where `<ORG>` is the name of the organization and `<OJ>` the 
    Github project name of the journal.

 2. Click on the `articles.md` file:

    ![](https://user-images.githubusercontent.com/473117/64357693-0ccdcc00-cffd-11e9-9597-63bc735cf53a.png)

    then click on the `Edit` button:

    ![](https://user-images.githubusercontent.com/473117/64357695-0d666280-cffd-11e9-8c5c-88694d7e0ee3.png)

    The above will open an editing window where you can modify the 
    `articles.md` file. In order to add a new submission to the table 
    of accepted articles, add a new entry to the exsiting table. A new 
    entry has the following format:

    ```
    <Title> | <Authors> | <URL> |
    ```

    Where `Title` is the title of your article, `Author` is a list of 
    comma-separated names and `URL` is a link to the article. Note 
    that the `|` symbols separate each field and its important to 
    include them.

 3. After accomplishing the above, go the bottom of the page, where 
    you will find a form with a `Propose change` button:

    ![](https://user-images.githubusercontent.com/473117/64357696-0d666280-cffd-11e9-9743-6f18c0d5838d.png)

    you will see a new page containing a form for creating a pull 
    request (PR) like the following:

    ![](https://user-images.githubusercontent.com/473117/64357694-0d666280-cffd-11e9-8aea-d8441fb44026.png)

    Click on the `Create Pull Request` button to create a new 
    submission.

#### Adding Files to Your Submission

Attaching a file to the submission (see [help here][gh-addfile]). This 
allows you to attach files such as `.docx` files.

[gh-addfile]: https://help.github.com/en/articles/adding-a-file-to-a-repository)).

### Respond to Comments from Reviewers

Once you create a submission, the editors of the journal will receive 
a notification and will assign reviewers to your submission. Once 
reviewers read your article, they will leave comments on the Pull 
Request associated to your submission. To respond to their comments, 
you can use the text form found in this page (see [here for 
more][gh-pr])

[gh-pr]: https://help.github.com/en/articles/about-pull-request-reviews

## For Reviewers

When an editor assigns you as a reviewer to a submission, you will get 
[a notification sent by Github][gh-notify]. Opening the associated 
link will take you to the pull request associated to the submission.

[gh-notify]: https://help.github.com/en/articles/about-notifications

## For Editors

### Journal Setup

To create a new journal:

 1. Click "Use this template" on the main page of the repository.
 2. From the template cloned in you repository, edit the `README.md` 
    file to create the main page of your journal.
 3. You are done! Your journal will be hosted at:

    ```
    `<youraccount>.github.io/<your_journal_id>`.
    ```

### Assign Reviewers

As submission is handled via a pull request, the editor assign 
reviewers using github assignments as described 
[here][gh-assign].

[gh-assign]: https://help.github.com/en/articles/assigning-issues-and-pull-requests-to-other-github-users

### Approve Submission

Once the paper is approved, the editor merges the pull request to add 
the paper to the journal record as described [here][gh-merge] using 
the "squash and merge" option.

[gh-merge]: https://help.github.com/en/articles/merging-a-pull-request
