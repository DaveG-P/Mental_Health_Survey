{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Mental Health in Tech Survey"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Survey on Mental Health in the Tech Workplace in 2014"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "ename": "FileNotFoundError",
     "evalue": "[Errno 2] No such file or directory: 'Mental_Health.jpg'",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-6-85aa7522fe76>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mfrom\u001b[0m \u001b[0mIPython\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mdisplay\u001b[0m \u001b[0;32mimport\u001b[0m \u001b[0mImage\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mImage\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mfilename\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;34m\"Mental_Health.jpg\"\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwidth\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;36m400\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mheight\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;36m800\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
      "\u001b[0;32m~/miniconda3/envs/MrLapin/lib/python3.6/site-packages/IPython/core/display.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, data, url, filename, format, embed, width, height, retina, unconfined, metadata)\u001b[0m\n\u001b[1;32m   1149\u001b[0m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0munconfined\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0munconfined\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1150\u001b[0m         super(Image, self).__init__(data=data, url=url, filename=filename, \n\u001b[0;32m-> 1151\u001b[0;31m                 metadata=metadata)\n\u001b[0m\u001b[1;32m   1152\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1153\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mwidth\u001b[0m \u001b[0;32mis\u001b[0m \u001b[0;32mNone\u001b[0m \u001b[0;32mand\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mmetadata\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mget\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'width'\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;34m{\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
      "\u001b[0;32m~/miniconda3/envs/MrLapin/lib/python3.6/site-packages/IPython/core/display.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, data, url, filename, metadata)\u001b[0m\n\u001b[1;32m    607\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mmetadata\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;34m{\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    608\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m--> 609\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mreload\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m    610\u001b[0m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_check_data\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    611\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n",
      "\u001b[0;32m~/miniconda3/envs/MrLapin/lib/python3.6/site-packages/IPython/core/display.py\u001b[0m in \u001b[0;36mreload\u001b[0;34m(self)\u001b[0m\n\u001b[1;32m   1180\u001b[0m         \u001b[0;34m\"\"\"Reload the raw data from file or URL.\"\"\"\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1181\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0membed\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 1182\u001b[0;31m             \u001b[0msuper\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mImage\u001b[0m\u001b[0;34m,\u001b[0m\u001b[0mself\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mreload\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   1183\u001b[0m             \u001b[0;32mif\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mretina\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1184\u001b[0m                 \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_retina_shape\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
      "\u001b[0;32m~/miniconda3/envs/MrLapin/lib/python3.6/site-packages/IPython/core/display.py\u001b[0m in \u001b[0;36mreload\u001b[0;34m(self)\u001b[0m\n\u001b[1;32m    632\u001b[0m         \u001b[0;34m\"\"\"Reload the raw data from file or URL.\"\"\"\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    633\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mfilename\u001b[0m \u001b[0;32mis\u001b[0m \u001b[0;32mnot\u001b[0m \u001b[0;32mNone\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m--> 634\u001b[0;31m             \u001b[0;32mwith\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mfilename\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_read_flags\u001b[0m\u001b[0;34m)\u001b[0m \u001b[0;32mas\u001b[0m \u001b[0mf\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m    635\u001b[0m                 \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mdata\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mf\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mread\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    636\u001b[0m         \u001b[0;32melif\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0murl\u001b[0m \u001b[0;32mis\u001b[0m \u001b[0;32mnot\u001b[0m \u001b[0;32mNone\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
      "\u001b[0;31mFileNotFoundError\u001b[0m: [Errno 2] No such file or directory: 'Mental_Health.jpg'"
     ]
    }
   ],
   "source": [
    "from IPython.display import Image\n",
    "Image(filename=\"NoteBooks/Imag/Mental_Health.jpg\", width=400, height=800)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Dataset Information\n",
    "This dataset is from a 2014 survey that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Content\n",
    "This dataset contains the following data:\n",
    "\n",
    "- Timestamp\n",
    "\n",
    "- Age\n",
    "\n",
    "- Gender\n",
    "\n",
    "- Country\n",
    "\n",
    "- state: If you live in the United States, which state or territory do you live in?\n",
    "\n",
    "- self_employed: Are you self-employed?\n",
    "\n",
    "- family_history: Do you have a family history of mental illness?\n",
    "\n",
    "- treatment: Have you sought treatment for a mental health condition?\n",
    "\n",
    "- work_interfere: If you have a mental health condition, do you feel that it interferes with your work?\n",
    "\n",
    "- no_employees: How many employees does your company or organization have?\n",
    "\n",
    "- remote_work: Do you work remotely (outside of an office) at least 50% of the time?\n",
    "\n",
    "- tech_company: Is your employer primarily a tech company/organization?\n",
    "\n",
    "- benefits: Does your employer provide mental health benefits?\n",
    "\n",
    "- care_options: Do you know the options for mental health care your employer provides?\n",
    "\n",
    "- wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?\n",
    "\n",
    "- seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?\n",
    "\n",
    "- anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?\n",
    "\n",
    "- leave: How easy is it for you to take medical leave for a mental health condition?\n",
    "\n",
    "- mental_health_consequence: Do you think that discussing a mental health issue with your employer would have negative consequences?\n",
    "\n",
    "- phys_health_consequence: Do you think that discussing a physical health issue with your employer would have negative consequences?\n",
    "\n",
    "- coworkers: Would you be willing to discuss a mental health issue with your coworkers?\n",
    "\n",
    "- supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?\n",
    "\n",
    "- mental_health_interview: Would you bring up a mental health issue with a potential employer in an interview?\n",
    "\n",
    "- phys_health_interview: Would you bring up a physical health issue with a potential employer in an interview?\n",
    "\n",
    "- mental_vs_physical: Do you feel that your employer takes mental health as seriously as physical health?\n",
    "\n",
    "- obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:MrLapin]",
   "language": "python",
   "name": "conda-env-MrLapin-py"
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
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
