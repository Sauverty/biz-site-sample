# Static Manpower Services Website (Kochi)

This is a fully static manpower service website with:

- Job listings
- Job application form
- Netlify CMS admin panel
- Git-based updates
- No backend server required

## Editing Jobs

1. Visit `/admin`
2. Login using Netlify Identity
3. Edit job cards in a simple form
4. Click “Publish” to update

Job details update automatically on the site.

## Deployment

Deploy using Netlify:

1. Push repo to GitHub/GitLab
2. Create Netlify site from repo
3. Publish directory = `public`
4. Enable Netlify Identity
5. Enable Git Gateway
6. Invite admin users
