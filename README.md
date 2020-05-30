# BootCampProject2020
Project for the Boot Camp runned by the Erdos Institute, The Ohio State University, May 2020. 

## Team Members
- Joseph Leung
- Francisco Martinez
- Jiawei Sun
- Ling Zhou

# Problem and Goals
Vincent van Gogh is a legendary Dutch painter from the mid 19th century. His huge legacy includes more than 860 oil paintings characterised by bold colors and dramatic, impulsive, and expressive brushwork [Wikipedia 2020].

## Goal
Using digitalizations of Van Gogh’s paintings from the “Web Gallery of Art” (https://www.wga.hu/), create a model than can recognize if a painting is in Van Gogh’s style or not. This as a first step to eventually being able to recognize not only his style, but also if a work is a counterfeit or not. 

# Data Gathering
1. Database: https://www.wga.hu
2. Form sample database:
   - Techniques used by van Gogh for more than 10 times
   - 1000 non-van Gogh paintings with the same techniques

# Packages
We use scikit-learn OpenCv and ripser to fiddle with many features, until we eventually decided to measure:
1. Count Strokes
2. No. of Faces
3. Histogram of grayscale image.

# Persistance
Since computing each of this is very time consuming, we used the package pickle to save a data frame with all the desired features.
