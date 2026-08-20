# English Tutor OAuth

Static login and consent page for the English Tutor MCP OAuth flow.

The page supports both existing-account sign-in and email/password account creation. Email confirmation returns to the original OAuth request so consent can continue.

The page uses the public Supabase publishable key for the EnglishTour project. It never contains a service-role key, stores passwords, or stores assessment transcripts and audio.

Production registration requires custom SMTP in Supabase Auth. The default Supabase mailer sends only to project-team addresses and is intended for testing.

Production page:

`https://joycn.github.io/english-tutor-oauth/oauth-consent/`
