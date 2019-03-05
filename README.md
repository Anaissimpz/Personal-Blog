 # Beauty Blog

### By **Simpenzwe Anais**
## Description
Beauty blog is a my personal blog whereby i will be posting different blog posts about different beauty hacks all over the world. When I post a user that has subscribed will be receiving emails telling them that there is a new blog post on Beauty blog
## BDD

## User
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| View blogs | Click on a post on the homepage to view the whole blog post| Displays the entire |
| Comment on blogs | Type comment details on the comment text area box in the blog page. The name and email are also required | The comment is displayed on the blog page below the blog content |
| Subscribe | Type your email and name in the subscribe form in the homepage. | Redirects to ```successfully subscribed page```. The user will receive a subscription confirmation email |

## Admin
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| Login | Enter login credentials in the login page | Redirects the writer to the homepage |
| Add Blog | The `create blog` button in the sidebar redirects to the blog form. Fill this form with blog details | Redirects the writer to the new blog post |
| Delete Blog | Press `delete` button just below the blog title  | The blog is deleted and redirects to the homepage |
| Delete Comment | Press `delete` button below the user's comment to delete the comment | Deletes the comment and refreshes the page |
|Edit Blog|Press `edit post` button| Porovides form to edit blog|

##Setup/Installations
### Prerequisites
* Python3.6
* Pip

### Cloning
* In your terminal<br>
   * $ git clone https://github.com/Anaissimpz/Personal-blog.git
   * $ cd Personal-Blog

### Install postgres
[Postgres]()
  
### Create virtual environment
sudo apt-get install python3.6-venv<br>
python3.6 -m venv virtual<br>
source virtual/bin/activate<br>

### Install dependencies
pip3 install -r requirements<br>

### Exporting environment variables
export DATABASE_URL='postgresql+psycopg2://username:password@localhost/blog'<br>
export SECRET_KEY='Your secret key'

## Run database migrations
python manage.py db init<br>
python manage.py db migrate -m "initial migration"<br>
python manage.py db upgrade

### Running
 * In your terminal<br>

     $ chmod +x start.sh<br>
     $ ./start.sh

## Technologies used

* Python3.6
* HTML
* Bootstrap
* CSS
* Postgresql


## Support and contact details

Having any issues?
Email:anaissimpenzwe@gmail.com

### License
Copyright (c) 2019 **Simpenzwe Anais**