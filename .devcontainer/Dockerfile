# Use the official Odoo 17 image
FROM odoo:17

# Install any additional dependencies if needed
RUN apt-get update && apt-get install -y \
    vim \
    git \
    && rm -rf /var/lib/apt/lists/*

# Expose the default Odoo port
EXPOSE 8069
