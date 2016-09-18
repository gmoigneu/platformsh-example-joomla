# Joomla on Platform.sh

## Setup

    git add remote platform [PROJECT-ID]@git.[PROJECT-REGION].platform.sh:[PROJECT-ID].git
    git push platform master

## Sample data:

    platform sql < setup-example.sql
    rsync -r media/. [PROJECT-ID]@ssh.[PROJECT-REGION].platform.sh:./media/

## Login

    Admin user: test
    Admin password: testtest
