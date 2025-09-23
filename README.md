{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "c4964a77-bbc6-491c-813b-90cbc8b37594",
   "metadata": {},
   "source": [
    "                                                                Data Extraction and NLP\n",
    "\n",
    "### Objective\n",
    "The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables that are explained below. \n",
    "\n",
    "### Data Extraction\n",
    "Input.xlsx\n",
    "For each of the articles, given in the input.xlsx file, extract the article text and save the extracted article in a text file with URL_ID as its file name.\n",
    "While extracting text, please make sure your program extracts only the article title and the article text. It should not extract the website header, footer, or anything other than the article text. \n",
    "\n",
    "### Data Analysis\n",
    "For each of the extracted texts from the article, perform textual analysis and compute variables, given in the output structure excel file. You need to save the output in the exact order as given in the output structure file, “Output Data Structure.xlsx”\n",
    "\n",
    "### Variables\n",
    "The definition of each of the variables given in the “Text Analysis.docx” file.\n",
    "Look for these variables in the analysis document (Text Analysis.docx):\n",
    "    1. POSITIVE SCORE\n",
    "    2. NEGATIVE SCORE\n",
    "    3. POLARITY SCORE\n",
    "    4. SUBJECTIVITY SCORE\n",
    "    5. AVG SENTENCE LENGTH\n",
    "    6. PERCENTAGE OF COMPLEX WORDS\n",
    "    7. FOG INDEX\n",
    "    8. AVG NUMBER OF WORDS PER SENTENCE\n",
    "    9. COMPLEX WORD COUNT\n",
    "    10. WORD COUNT\n",
    "    11. SYLLABLE PER WORD\n",
    "    12. PERSONAL PRONOUNS\n",
    "    13. AVG WORD LENGTH\n",
    "    \n",
    "### Output Data Structure\n",
    "\n",
    "Output Variables: \n",
    "All input variables in “Input.xlsx”\n",
    "    1. POSITIVE SCORE\n",
    "    2. NEGATIVE SCORE\n",
    "    3. POLARITY SCORE\n",
    "    4. SUBJECTIVITY SCORE\n",
    "    5. AVG SENTENCE LENGTH\n",
    "    6. PERCENTAGE OF COMPLEX WORDS\n",
    "    7. FOG INDEX\n",
    "    8. AVG NUMBER OF WORDS PER SENTENCE\n",
    "    9. COMPLEX WORD COUNT\n",
    "    10. WORD COUNT\n",
    "    11. SYLLABLE PER WORD\n",
    "    12. PERSONAL PRONOUNS\n",
    "    13. AVG WORD LENGTH\n",
    "\n",
    "Check out the output data structure spreadsheet for the format of your output, i.e. “Output Data Structure.xlsx”.\n",
    "\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3.10 (tf-env)",
   "language": "python",
   "name": "tf-env"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
