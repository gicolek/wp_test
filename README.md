# Code Shakers Entry Test Readme #

(For a more visually appealing description please visit: http://gicolek.github.io/wp_test/) 

The files which are part of the repo have been slightly modified https://wordpress.org/themes/twentyfifteen theme files.

## Purpose of the test ##

The test aims in evaluating your basic .git skills as well as intermediate WordPress knowledge. Familarity with WordPress actions
and filters is highly anticipated. Moreover we value knowledge of fast debugging and catchy-eye which can easily identify common spelling problems.
Needles to say with a properly configured debugger and IDE this test should be fairly simple, hence there are no tips whatsoever. We praise
individuals who can solve common problems given a fair description.

## Test Requirments ##

Your job as a submitee is to do the following:

* create new git branch for the work.
* fix the php bugs (make the code run without any errors or warnings with the theme being activated).
* fix the bug which prevents scripts and styles from loading.
* create a filter which hooks to 'get_search_form' and adds a custom CSS class to the form button element. The class should read as follow 'cs-search-class'. Remove the default hook coming up with the theme.
* create an action which hooks to 'twentyfifteen_credits' that adds the following text: "Code Shakers Entry Test". There should be no more actions bound to that hook (including theme default actions).

## Notes ##

* The bugs have only been added to the following files: functions.php, header.php, footer.php. You can complete the job by loading the default theme page only.
* Custom actions and filters should be placed within functions.php file below the /* Code Shakers Entry Test Code */ text.
* Overwriting these files with original TwentyFifteen theme files will not make the job complete. The requirements herein modify theme's base structure.
* There are certain comments hidden here and there: /* CodeShakers */, absence of these will result in immediate failure.
* Once completed push the new branch to the repository.