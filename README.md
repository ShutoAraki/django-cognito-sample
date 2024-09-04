# Sample code to use Amazon Cognito on a Django app

The first commit is the basic login/logout templates using sqlite.

The second commit shows you the Amazon Cognito components and code changes you need in order for this to work.

Keep in mind that you need a `.env` file with the following variables.

```
COGNITO_DOMAIN=<<Amazon Cognito Domain for your hosted domain>>
COGNITO_CLIENT_ID=<<Amazon Cognito application client ID>>
COGNITO_SECRET=<<Cognito application client secret>>
```

Reference: https://qiita.com/MakotoPlus/items/894bc8c6c408fddc79a8
