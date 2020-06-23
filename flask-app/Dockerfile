FROM python:3

# where are we setting this working directory ? container or where ? 
# user / source code / app code 

WORKDIR usr/src/app

# Copy all the files from our working directory to the app wd that we have specified above 

COPY . .  

# Now that we have the files, let us specify the dependencies 

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000 

CMD ["python"  , "./app.py"]



