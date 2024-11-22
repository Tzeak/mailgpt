# MailGPT - Easi.Work Demo

MailGPT is a simple email interface for LLMs. Doesn't mess with cloud services, just the services you already own.
To use it, you gotta get the credentials from your mail provider. Gmail and iCloud both provide app-specific passwords for this purpose.
Should be easi.work
```
export ICLOUD_USER_EMAIL="youremail@icloud.com"
export ICLOUD_APP_PASSWORD="xxxx-xxxx-xxxx-xxxx"
export OPENAI_API_KEY="your_key_here"
export EMAIL_ALIAS="alias@custom.domain"
```

Everything except the OpenAI client is in the standard library. 

```
pip install OpenAI
```
should have you covered.

Happy Mailing 💌
