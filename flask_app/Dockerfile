# Step 1: Use the official Python image as the base
FROM python:3.13

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy the application files to the container
COPY app.py requirements.txt ./

# Step 4: Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Step 5: Expose the application port
EXPOSE 5000

# Step 6: Run the application
CMD ["python", "app.py"]