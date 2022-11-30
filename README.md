{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Team: Pitt is Garbage\n",
    "\n",
    "## Group Members:\n",
    "<br>Greyson Barsotti - gjb46@pitt.edu\n",
    "<br>Ethan Defilippi - ecd57@pitt.edu\n",
    "\n",
    "## Data Sets:\n",
    "- [Police Incident Blotter](https://data.wprdc.org/dataset/uniform-crime-reporting-data) - Worked on by Ethan <mark>(Drug Overdoses.ipynb)</mark>\n",
    "- [Pittsburgh Police Arrest Data](https://data.wprdc.org/dataset/arrest-data) - Worked on by Greyson <mark>(Arrests.ipynb)</mark>\n",
    "- [Household Income in the Past 12 Months](https://data.wprdc.org/dataset/pittsburgh-american-community-survey-2015-miscellaneous-data/resource/b119be7e-1c70-4bbe-bf34-2056fef533ec) - Worked on by Greyson & Ethan <mark>(Household Income.ipynb)</mark>\n",
    "\n",
    "---\n",
    "\n",
    "## Our Mission:\n",
    "We will be investigating the best area in Pittsburgh to do <b>hard drugs</b> (but we do <strong>not</strong> recommend this action). \n",
    "\n",
    "#### Our data will be drawn from the metrics:\n",
    "\n",
    "* Number of drug possesion charges within a neighborhood\n",
    "* Number of arrests within a neighborhood\n",
    "* Number of people who make a lot of money within a neighborhood\n",
    "\n",
    "\n",
    "#### Our single metric will be \"Drug Points\"\n",
    "\n",
    "This metric will be used to rate all of the neighborhoods in the data set based off one linear scale. This number will be calculated using our scientifically perfect formula: \n",
    "> ((1/2 x Number of people who make above 200K) + (2 x Number of drug possesion charges)) x (Average of Arrests / Arrests within that neighborhood)\n",
    "\n",
    "---\n",
    "\n",
    "# Quick Warning!\n",
    "\n",
    "This project uses git large file system in order to store our datasets. In order to download the files, use: \n",
    "\n",
    "`$ git lfs pull`\n",
    "\n",
    "Sorry for the inconvenience!!\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3.11.0 64-bit",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "name": "python",
   "version": "3.11.0"
  },
  "orig_nbformat": 4,
  "vscode": {
   "interpreter": {
    "hash": "aee8b7b246df8f9039afb4144a1f6fd8d2ca17a180786b69acc140d282b71a49"
   }
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
