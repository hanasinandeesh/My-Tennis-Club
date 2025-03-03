# My-Tennis-Club

## How This Project Works  

### Homepage (`/`)  
- The main page is loaded from `main.html`.
![Screenshot 2025-03-03 145431](https://github.com/user-attachments/assets/265373dd-cb90-44e6-8652-4fa352aa7edc)


### List Members (`/members/`)  
- Fetches all members from the database.  
- Displays them using the `all_members.html` template.

![Screenshot 2025-03-03 145113](https://github.com/user-attachments/assets/c4e6a74d-ed1b-488d-9d67-d4e0dffaea8d)


### Member Details (`/members/details/<id>/`)  
- Retrieves a specific member using their `id`.  
- Renders details using `details.html`.

![Screenshot 2025-03-03 145131](https://github.com/user-attachments/assets/d8c5d977-6112-4bef-af6f-92e3ca03a32c)


### Django Administration
- The Django admin panel can be accessed at `/admin/`.
- Superusers can manage members, view records, and update the database.
- To create a superuser, run:
  ```sh
  python manage.py createsuperuser
  
![Screenshot 2025-03-03 145210](https://github.com/user-attachments/assets/782cad44-451e-4a53-8c81-38120dfda0f1)


## Project Workflow  
1. User visits a page.  
2. The corresponding view (`views.py`) queries the database.  
3. Data is passed to an HTML template.  
4. The template is rendered and displayed in the browser.  
