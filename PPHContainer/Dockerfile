#Use django as parent image/repository
FROM django

#Set working directory to /app
WORKDIR /app

#Copy the current directory contents into the container at /app
ADD . /app

#Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

#Make port 80 available to the world outside this container
EXPOSE 8000

#Start the server
CMD ["./PPH_OATHKernel/PolyPasswordHasherOATH_Django/manage.py", "runserver", "0.0.0.0:8000"]







