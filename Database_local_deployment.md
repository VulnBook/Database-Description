****Note: Must Remove this file in deployment

Database deployment

    sudo apt install postgresql postgresql-contrib
    sudo service postgresql start
    sudo -u postgres psql

execute the following lines in PostgreSQL

    CREATE DATABASE shah_database;
    CREATE USER shah_user WITH PASSWORD 'shah_password';
    GRANT ALL PRIVILEGES ON DATABASE shah_database TO shah_user;
    ALTER DATABASE shah_database OWNER TO shah_user;
    \q  # Exit psql

Check Database Connectivity

    psql -h localhost -U shah_user -d shah_database
