# SSO extra click

Use this page as the deep-link target.

Jane is logged into **Microsoft**. She is **not** logged into **Harness**.

## Today

1. Open this page while signed out of Harness
2. Login page appears
3. Click **Sign in with SSO**
4. Microsoft lets her in with no password
5. This page loads

## Wanted

1. Open this page
2. Microsoft lets her in with no password
3. This page loads

No login page. No button.

## Cases

| Situation | What happens |
|---|---|
| Already logged into Harness | Docs open. No login. |
| Microsoft yes, Harness no | Login page + SSO button |
| Logged out of both | Login page, then real Microsoft login |
