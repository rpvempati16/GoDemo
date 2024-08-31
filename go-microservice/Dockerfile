# Start with the official Golang image
FROM golang:1.23.0

# Set the working directory
WORKDIR /app

# Copy the source code to the container
COPY . .

# Build the Go application
RUN go build -o main .

# Expose the application on port 8080
EXPOSE 8080

# Run the application
CMD ["./main"]
