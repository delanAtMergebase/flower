# Bit-Booster with Commit Graph and More! - for Atlassian Bitbucket (Server) #

## What is this site? ##

This site contains our project bug tracker, our support wiki, some of our code, and some test repos (for testing the plugin).  

## What does the plugin do? ##

The plugin contains 3 features we believe our essential for users of Bitbucket:

- **Commit Graph** - Display branch history visually on the Bitbucket Commits page.
- **Commit Time** - Display the correct commit time on the Bitbucket Commits page. 
- **Protect First Parent** (Pre-Receive & Merge Hook) - Ensure consistency of the master branch (e.g., protect against 2nd-parent kidnappings.)

### How do I set it up? ###

- **Commit Graph** and **Commit Time** are both automatically enabled for all repositories the moment Bit-Booster is installed.  **Note:** they also automatically disable themselves if your trial license expires (paid licenses never expire).


- **Protect First Parent** appears in the "Hooks" section of your repositories.  It is "disabled" by default, and you must click "enable" inside each repository to activate its function for said repository.  **Protect First Parent** is not affected by license status, and remains fully functional even if your license expires.



### Who do I talk to? ###

* For technical support and general questions about the plugin, you can use our public mailing list: [users@ml.bit-booster.com](mailto:users@ml.bit-booster.com). You can subscribe [here](http://ml.bit-booster.com/listinfo.cgi/users-bit-booster.com)). Or you can email support directly: [support@bit-booster.com](mailto:support@bit-booster.com).
  
* For consulting work, please email me directly (g.sylvie.davies@gmail.com).

### Is Bit-Booster really the best commit graph on Bitbucket Server? ###

* Take a look at our analysis for yourself and see if you agree: [bit-booster.com/best.html](http://bit-booster.com/best.html).