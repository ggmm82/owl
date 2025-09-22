FROM mugglejinx/owl:latest


# Set working directory
WORKDIR /app/owl

COPY  ../owl/.env /app/owl/.env
COPY  ../examples /app/examples

CMD ["python", "webapp.py"]
