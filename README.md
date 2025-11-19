My Current dashboard & most for the apps I'm using right now.

![Description of your Glance Dashboard](Glance/Glance-Dashboard.png)


Download the files/ codes from here, edit & add your API keys. Enjoy.

Here is how to use these dockerr-compose files:
Lets say you want to deploy Jellyfin-

1. Create a Jellyfin folder on your computer
2. Keep the docker-compose.yml in that folder
3. Inside docker-compose.yml give that folder location for config & cache
4. Give location for your movies/ tv series
5. Save the file
6. On docker CLI: cd "jellyfin-folder-location"
7. Then use this command: docker compose up -d
8. Now you can access Jellyfin on localhost:8096
