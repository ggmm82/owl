FROM mugglejinx/owl:latest


# Set working directory
WORKDIR /app/owl

COPY  ../owl/.env /app/owl/.env
COPY  ../examples /app/examples
COPY  ./data /app/owl/data

CMD ["python", "webapp.py"]
