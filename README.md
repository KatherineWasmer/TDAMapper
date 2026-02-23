📌 HOW TO INSTALL 📌

1. Download R on your local machine
  * <span style="color:blue">[Download instructions for Mac OS](https://cran.r-project.org/bin/macosx/)</span>
  * <span style="color:blue">[Download instructions for Windows](https://cran.r-project.org/bin/windows/base/)</span>

2. Install RStudio, which is the IDE most frequently used for R. The latest version as of February 2026 is 4.5.2. 
   * Download [here](https://posit.co/download/rstudio-desktop/)
  
3. Open RStudio and click on the bottom left-hand panel (the console).

4. Install the Swirl library in R. ```if (!require(package = "swirl")){install.packages(pkgs = "swirl")}```

5. Load the Swirl library with the command ```library(swirl)``` If you have already installed the package, you should get the following message:

```
> if (!require(package = "swirl")){install.packages(pkgs = "swirl")}
Loading required package: swirl

| Hi! Type swirl() when you are ready to begin.
```

Although the directions tell you to type swirl(), you can ignore that command and proceed to install my course. Copy the following command: `install_course_github("KatherineWasmer", "TDAMapper", "master")`

This should only take a few seconds to download. Now you can type `swirl()` into the command line, and you should get the following output: 

```
> swirl()

| Welcome to swirl! Please sign in. If you've been here before, use the
| same name as you did then. If you are new, call yourself something
| unique.

What shall I call you?
```

Continue to follow the directions. When it's time to choose a course, you should see the following: 

```
| Please choose a course, or type 0 to exit swirl.

1: TDAMapper
2: Take me to the swirl course repository!
```

Please type 1. You should then see the following output: 

```
| Please choose a lesson, or type 0 to return to course menu.

1: PCALesson

```

Type 1 again to start the lesson on PCA. Enjoy learning! 
