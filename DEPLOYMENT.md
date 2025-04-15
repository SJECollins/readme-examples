## Deployment

Describe the process used to deploy the project to a hosting platform.
For the first two projects, this will typically be GitHub Pages like the Love Running project.
The other projects are usually deployed to Heroku which requires more detailed deployment steps.

---

### Example steps to deploy to GitHub Pages:
- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Main Branch and save
  - Wait for the site to build, then refresh the page for the link to the deployed site

The live site can be found here: [Project Live Link](https://example.com/)

---

### Example steps to deploy the site using Heroku:

*This is a basic example, however, you may want to include further details like the database creation, the specific config vars (not their values!) added on Heroku, and the steps to setup your external host (e.g. Cloudinary, AWS).*

- Create a new app via the Heroku dashboard:
  - Choose a unique app name and select the region.

- Connect the GitHub repository under the **Deploy** tab:
  - Search for the repository and link it.
  - *(Optionally)* Enable automatic deploys from the main branch.

- Add environment variables under the **Config Vars** section in the **Settings** tab:
  - Include keys for secret management, database connection, media storage, and any third-party services (e.g., Stripe, Cloudinary).

- Set up external media hosting (e.g., Cloudinary, AWS) and link it via environment variables.

- Create a `Procfile` to tell Heroku how to run the app:
  - Add `web: gunicorn project_name.wsgi` in the `Procfile`.

- Generate a `requirements.txt` file with:
  - `pip3 freeze --local > requirements.txt`

- Run database migrations:
  - `python3 manage.py migrate`

- Before deploying:
  - Set `DEBUG = False` in the `settings.py` file.
  - Add the Heroku app URL to `ALLOWED_HOSTS`.
  - Remove any temporary config vars like `DISABLE_COLLECTSTATIC`.

- Deploy the app by selecting **Deploy Branch** under the Heroku **Deploy** tab.
  - The app will be built and deployed automatically.
  - After deployment, you can view the live application via the **Open App** button.

The live site can be found here: [Project Live Link](https://example.com/)

---

*Optionally, but ideally, we should include some basic directions for forking and cloning projects.*

### Steps to Fork a Repository:

1. Go to the GitHub repository page that you want to fork.
2. Click the **Fork** button at the top right of the page.
3. GitHub will create a copy of the repository under your own GitHub account.


### Steps to Clone a Repository:

1. Navigate to the GitHub repository you want to clone.
2. Click the **Code** button (usually green).
3. Copy the URL under "HTTPS" (or "SSH" if you've set up SSH keys).
4. Open your terminal or Git Bash.
5. Navigate to the directory where you want to store the cloned repository.
6. Run the following command to clone the repository:

   `git clone <paste the copied URL here>`

7. After cloning, navigate into the project directory:

   `cd <repository-name>`
